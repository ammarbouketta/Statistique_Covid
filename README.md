# Statistique_Covid
Statistiques sur Covid-19
   On désire faire des statistiques sur la pandémie actuelle. Pour chaque pays, on recense les personnes qui ont eu un résultat (Outcome). Le résultat peut être
Death ‘D’ (mort) ou Recovery ‘R’ (guéri). On peut organiser les données dans un tableau T[1..n] d’arbres de recherche binaire
d’enregistrements dans lequel T[I] est l’arbre associé au pays I. Une personne est décrite par l’enregistrement suivant : Nom, Prénom, Age, Résultat
    Les arbres de recherche binaire sont ordonnés selon l'age. De cette manière, l’arbre de recherche
binaire peut contenir plusieurs exemplaires de l'age. 
1. A partir de données générées aléatoirement créer la structure. Pour chaque pays, le nombre de personnes (m) et les différents champs des enregistrements sont tous
générés aléatoirement. 
2. Afficher la structure par pays et ordonnée selon l'age.
    En vue de faire des statistiques globales, on regroupe tous les arbres dans un même arbre de
recherche binaire ordonné cette fois-ci selon l'age et le résultat. De plus, l'age n'est pas dupliqué. Chaque nœud de l'arbre est alors le triplet (Age, Occurrence, Résultat) où Occurrence désigne le nombre de personnes avec l'age Age. Les noms et prénoms sont ainsi éliminés. 
3. Créer la nouvelle structure à partir de l’ancienne. 
4. Afficher la nouvelle structure
5. Développer sur la nouvelle structure un seul algorithme efficace permettant de répondre aux
  requêtes suivantes: 
  - % de ‘D’ tels que l’age est dans l’intervalle [50, 60]
  - % de ‘D’ tels que l’age est supérieur à 70
  - % de ‘R’ tels que l’age est inférieur à 30
  - Etc
