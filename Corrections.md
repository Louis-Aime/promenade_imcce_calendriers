# Liste des corrections
Corrections apportée à l'application "Promenade dans le système solaire" de l'IMCCE, version du 28 mai 2019

## Dans toutes les pages corrigées :
 * Le bouton « Agrandir » situé en haut à gauche de l’écran principal est orthographié « Agrandir » au lieu de « Aggrandir » (visible en passant la souris).
 * Les textes sont tous accentués, même en majuscules.
 * Les boutons « Précédent » et « Suivant » donnent lieu aux mêmes contrôles que le bouton « Calcul ». On ne peut donc plus indiquer une date ou une année hors du domaine de validité.
 * Une valeur initiale est donnée dans les champs de saisie, correspondant à la date courante.
## Page « Détermination des calendriers/Correspondance entre calendrier/Origine grégorien (n° 428) » :
 * La page indique bien le 15 octobre 1582 (et non le 10) comme date origine du calendrier grégorien.
 * Toute tentative de spécification d’une date antérieure au 15 octobre 1582 donne lieu à un message d’erreur, au lieu de produire des résultats.
## Page « Détermination des calendriers/Correspondance entre calendrier/Origine julien » (n° 429) :
 * La date limite haute est le 14 décembre 2500 du calendrier julien, soit le 31 décembre 2500 du calendrier grégorien (jour julien 2 634 531).
 * La date limite basse est le 1 janvier -4712.
 * Ces deux limites sont appliquées quel que soit le bouton (Calcul, Précédent, Suivant) par lequel on spécifie la date.
## Page « Détermination des calendriers/Correspondance entre calendriers/Origine Israélite » (n°432)
 * La date limite haute est le 8 Tébeth 6261, soit le jour julien 2 634 531.
 * La gestion des mois selon que l’année est commune ou embolismique est réparée. En année commune, le mois Véadar apparaît dans la liste, mais ne peut être choisi.
## Page « Détermination des calendriers/Correspondance entre calendriers /Jour julien » (n° 433)
 * L’expression « jour julien » est utilisée à l’exclusion de toute variante (date julienne…)
 * La saisie d’un jour julien décimal était possible, mais au moins la moitié des valeurs possibles conduisait à une erreur ou un résultat faux. Désormais le jour julien est saisi en tant que nombre entier exclusivement. Le résultat est alors sans erreur.
## Page « Détermination des calendriers/Début des saisons » (n° 439)
 * Les dates de saisons apparaissent correctement alignées, même aux années à un seul chiffre.
## Page « Phénomènes astronomique/Phases de la Lune » (n° 441)
 * Les dates de phase de lune et le tableau des jours de la Lune par rapport au jour du mois sont correctement alignés, même pour les années à un chiffre.
## Page « Détermination des calendriers/L’heure légale en France » (n° 503)
 * Dans les textes obtenus en réponse manquait à plusieurs endroits la préposition « à », ainsi que « é » de « février ». Ces lettres ont été rétablies.
 * Le contrôle de champ a été laissé à dessein à 1945-2050. Mais un second contrôle en JavaScript envoie un message d’erreur au-delà de 2021, horizon actuel (Commentaire de Patrick Rocher, 2019).
## Page « Détermination des calendriers/Fêtes religieuses/Fêtes chrétiennes » (n°552)
 * La touche « Retour » faisait disparaître l’année et effaçait tous les résultats. Désormais elle permet au contraire de valider l’année et d’afficher les résultats.
 * Au premier calcul, la valeur pour l’Épiphanie était en erreur. Elle est désormais exacte dès le premier calcul.
 * Le mot « Mi-Carême » n’apparaissait pas correctement. 
## Page « Détermination des calendriers/Fêtes religieuses/Fêtes israélites » (n° 553)
 * La touche « Retour » faisait disparaître l’année et effaçait tous les résultats. Désormais elle permet au contraire de valider l’année et d’afficher les résultats.
 * Correction orthographique : « Pâque ».
 * Dans le tableau de présentation, le « : » est retiré là où il n’était pas opportun
## Page « Détermination des calendriers/Fêtes religieuses/Fêtes musulmanes » (n° 554)
 * La touche « Retour » faisait disparaître l’année et effaçait tous les résultats. Désormais elle permet au contraire de valider l’année et d’afficher les résultats.
 * Dans le tableau de présentation, le « : » est retiré là où il n’était pas opportun.
