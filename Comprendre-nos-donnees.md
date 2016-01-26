#CaptaData
####La revue pour capter les capteurs

####31 juillet 2015 

 TN-DS-TVV FR

#Les données de validations
Plusieurs outils sont utilisés pour évaluer la mobilité de la population en Ile de France, des enquêtes aux traces
GSM en passant par des comptages automatiques, manuels ou encore des capteurs innovants tels que des
caméras thermiques ou des tapis de comptage. Tous ces « capteurs » présentent à la fois des avantages et des
inconvénients qui leurs sont propres, mais aussi des coûts non négligeables de mise en place. La seule méthode qui
permette aujourd'hui de remonter des données de mobilité quotidiennement, sur l’ensemble des réseaux et grâce
à du matériel déjà existant consiste en l'exploitation des données de validations et de passages. Néanmoins,
celles-ci sont encore imparfaites car souvent incomplètes pour les gares dites « ouvertes » (avec des bornes de
validations mais sans ligne infranchissable) et pour certains jours particuliers de gratuité, travaux, grèves etc.
 
 
##Qu'est-ce qu'une donnée de validation ?
Lorsqu'un usager utilise un moyen de transport collectif, *il achète un titre qu'il doit valider* avant ou pendant sa
montée en bus/métro/RER/train. Cet acte de validation renseigne sur le titre possédé et sur l'horaire de validation.
Ainsi, au-delà de la fonction première de contrôle du billet, il s'agit bien là *d'une donnée récoltée qui permet de
donner des informations sur le taux de fréquentation d'une gare.*

En plus du nombre total de validations dans une gare, le principe de recueil permet d'avoir des renseignements
complémentaires. On peut connaître *le tarif associé*, c’est-à-dire s’il s’agit d’un abonnement et lequel, s’il s’agit d’un
ticket t+ ou d’un billet origine-destination, s’il est issu d’un *carnet* ou non, avec des *tarifs réduits* ou non, sur quelle
*période de validité*. Pour les forfaits, on connaît la *zone de validité*. Pour les billets, l’origine et la destination. Les
informations concernent aussi la technologie de validation, c’est-à-dire savoir si le titre de transport est
« magnétique » (cartonné, qu’il faut glisser dans une « fente ») ou « télébilletique » (qu’il suffit de « bipper »,
comme les pass Navigo, les ImagineR…). Une validation est associée à *une date et une heure*, ainsi qu’à un
*identifiant de valideur*, ce qui permet de savoir à quel endroit il est situé *dans la gare (quel accès)*, quel est le *type
de validation (entrée, sortie, correspondance).*

En Ile-de-France, près de 8,3 Millions de voyages sont réalisés chaque jour sur les réseaux de trois transporteurs. La
*RATP* gère le métro, les RER A et B (conjointement à la SNCF), la plupart des Tramway, de nombreuses lignes de bus,
l’Orlyval. *OPTILE* rassemble des entreprises privées exploitant des lignes d'autobus. La *SNCF – Transilien*, branche de
SNCF Mobilités, exploite 5 lignes RER (A et B avec la RATP, C, D, E), 8 lignes de train (H, J, K, L, N, U, P, R), une ligne
de tramway (le T4) et les lignes de bus Noctilien. La donnée de validation permet donc également de connaître le
mode de transport, l'exploitant, le vendeur du titre.

Contrairement à une l’idée que l’on s’en fait souvent, il n'est pas possible aujourd'hui d'avoir, à partir de cette
donnée de validation, des informations sur le type de client concerné. *Les numéros de cartes sont anonymisées et
l'identifiant est modifié tous les trois mois.*


##Les différents types de valideurs et les détecteurs de passage
*Trois types de valideurs co-existent :*
- *Les composteurs*, pour les tickets et billets magnétiques, qui ne bloquent pas le passage mais permettent de
valider. On ne remonte aucune donnée de ces valideurs ;
- *Les bornes*, qui ne bloquent pas non plus le passage (ce sont, en quelque sorte, des composteurs pour
Navigo). Elles permettent de remonter les validations télébilletiques ;
-  *Les CAB et PEC* (Passage Elargi Contrôlé), qui constituent une ligne fermée à franchir en validant pour
accéder au quai. Ils permettent de remonter les validations télébilletiques et magnétiques. On en trouve
environ 3000 en Ile-de-France.

Bornes et Composteur
CAB G1
CAB M1

*On différencie les CAB tripode ancienne génération (G1) des CAB M1 nouvelle génération (porte effaçable)*. En sus
des données de validations, ces derniers permettent de détecter les passages et de compter les personnes qui
franchissent l’obstacle :
- Sur les CAB Tripode (G1), le comptage est effectué lorsque le Tripode est activé par le client. *Une validation
correspond à une rotation*. Le capteur est alors un interrupteur qui tourne. De ce fait, sur un CAB G1 en
entrée ou sortie contrôlée, le comptage est, théoriquement, identique au nombre de validations. On parle
« d’entrée ou sortie contrôlée » lorsqu’il est obligatoire de valider pour franchir la ligne. On parle « d’entrée
libre » lorsque les portes sont ouvertes et que l’on peut passer dans n’importe quel sens (double sens sur
M1, un seul sens sur G1). Sur un CAB positionné en sortie libre, il n’y a pas de données de validations mais il
y a bien un comptage des franchissements.
- Sur les CAB et PEC M1, toute personne franchissant le passage est comptée, même si elle n’a pas validé.
Tous les franchissements sont donc comptabilisés, en entrée / sortie contrôlées comme en entrée / sortie
libres. Le *système de détection est composé de cellules émettrices et de capteurs de zone*, protégés par
des bandeaux de plexiglas.

CAB M1 

##Quels sont les points d’incomplétude de ces données ?
Il est utile de préciser que *de fortes lacunes peuvent exister dans ces données*. Tout d’abord, seul le STIF possède
les données de validation de l’ensemble des transporteurs. Le STIF est l’Autorité Organisatrice qui organise et
finance les transports publics pour tous les Franciliens. Il est composé de la Région Île-de-France, de la Ville de Paris
et des sept autres départements franciliens. Il porte la vision de l’ensemble des transports d’Île-de-France et fédère
tous les acteurs. Son objectif est de renforcer l’offre de transport et la qualité de service pour le voyageur.
L’ouverture de l’ensemble des données de validations est à l’ordre du jour mais les délais sont encore inconnus. Pour
l’instant, les données sont donc partielles, par transporteur.

En ce qui concerne les données de validations SNCF-Transilien, *le problème majeur concerne les gares dites
« ouvertes »*. Sur 380 gares en Ile-de-France, environ 200 ne sont pas fermées (non « cabbées »), représentant 20%
des entrants. Dans ces gares, les voyageurs doivent valider leur titre de transport (y compris leurs titres
télébillettiques) avant de voyager, sur les bornes de validations (BVT). Cependant, les données remontées sont loin
de vérifier le nombre de voyageurs. Pour ne parler que des comportements « honnêtes », certains voyageurs ne
savent pas qu’ils doivent valider leur titre sur la borne, d’autres ont un abonnement et ne jugent pas nécessaire de
valider avant de voyager. Quoiqu’il en soit, le taux de validation sur les gares dites « ouvertes » reste très faible.

D’autres phénomènes viennent altérer la remontée de données *comme les travaux ou les phénomènes de
saturation*. Les travaux que doit régulièrement mener la SNCF (maintenir les gares en bon état, favoriser les accès
handicapés, etc.) entraînent bien souvent la suppression de lignes de CAB sur la période, ce qui engendre une forte
perte des données. *Il n’est pas rare que les portillons (près des lignes de CAB, cf photo) restent ouverts*, pour
désaturer, pour les accès de maintenance, pour les poussettes…, ce qui permet à de nombreuses personnes de
s’engouffrer sans valider.

Portillon ouvert

Lorsque le flux de voyageurs est trop dense et que cela crée des phénomènes de saturation, il arrive que la gare
décide d’ouvrir ses lignes de CAB (entrée sortie libres) afin de fluidifier le trafic. Les saturations sont constatées plus
généralement en sortie, lors de l’arrivée d’un train, voire de plusieurs simultanément. Une des solutions utilisées est
de passer les CAB en « sortie libre », entraînant une perte des validations de sortie. Quelques gares ne les repassent
pas en « sortie contrôlée » en dehors des heures de pointe.

Par ailleurs, certains problèmes informatiques peuvent altérer également la remontée de données. 

Enfin, notons que la comparaison entre les données de passages et de validations présente des biais et ne permet
pas toujours de bien estimer la fraude, comme on l’imaginerait. Les comportements des usagers peuvent jouer sur la
finesse des données. Par exemple, si une personne valide avant que la personne précédente n’ait franchi la ligne,
cela peut engendrer des désynchronisations de passage. Si deux personnes passent ensemble, collées l’une contre
l’autre, le système risque de n’en compter qu’une. Si une personne de moins de 90 cm passe, il ne sera pas compté.
A l’inverse, certaines poussettes ou bagages peuvent être détectés.

##Quelles solutions envisager pour l’exploitation de ces données
Plusieurs solutions peuvent permettre d’exploiter les données de validations, malgré leurs incomplétudes. D’une
part, il faudrait envisager un déploiement des CAB M1 dans toutes les gares ouvertes, mais cela a un coût non
négligeable et peut prendre du temps. D’autre part, il faut songer à *des techniques statistiques de correction des
données manquantes*, soit à partir des seules données de validation, soit à partir d’autres capteurs complémentaires
testés dans quelques gares, sur une certaine temporalité. Il est également possible d’envisager des capteurs qui
prendraient le relais en cas de défaillance. Par exemple, certains portillons innovants commencent à être déployés
dans les gares, agrémentés d’un système de détection d’ouverture. Il conviendrait d’y ajouter un système de
comptage pour compléter les données de validations lorsque le portillon est détecté ouvert. Enfin, pour améliorer
l'exploitation de ces données et mieux comprendre et analyser leurs variations, *il semble essentiel de constituer
une base des évènements par jour et par gare* (travaux, flux atypiques, ouverture des CAB pour journée de gratuité,
etc.).

##Les validations oui, mais pour quel usage ?
L’exploitation des données de validations *permet une meilleure connaissance de la mobilité* en Ile de France car elle
permet, à l’aide de quelques règles de gestion, de reconstituer des déplacements. Ces analyses permettent de mieux
comprendre les flux et *d’anticiper des problèmes de saturation* aux valideurs, aux guichets/automates de paiement
et sur les quais, engendrant des actions en gare par la suite. *Elles donnent aussi des indications sur les
comportements frauduleux*, en termes de lieux et d’horaires. Elles permettent de mesurer l’impact des actions
déployées dans les gares (impact d’un contrôle, impact de la mise en place de valideurs supplémentaires etc.), des
actions tarifaires (dézonage, compléments de parcours, tarif toute zone), des créations de gare (Créteil Pompadour,
Rosa Parks, Grand Paris).

Ce sont aussi ces données qui risquent de déterminer à l’avenir le partage de recettes entre les différents
transporteurs, puisque l’arrivée du Tarif Toute Zone vient en quelque sorte supprimer les notions de voyages
kilomètre qui existaient jusqu’à présent dans les répartitions financières. 
