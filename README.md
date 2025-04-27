# Uber Pickups

#### Description de l'entreprise 📇
Uber est l'une des startups les plus célèbres au monde. À ses débuts, elle proposait une application de covoiturage pour les personnes n'ayant pas les moyens de payer un taxi. Uber a ensuite étendu ses activités à la livraison de repas avec Uber Eats , à la livraison de colis, au transport de marchandises et même au transport urbain avec Jump Bike et Lime , qu'elle a financés.

L'objectif de l'entreprise est de révolutionner les transports à travers le monde. Elle est aujourd'hui présente dans environ 70 pays et 900 villes et génère plus de 14 milliards de dollars de chiffre d'affaires ! 😮

#### Projet 🚧
L'un des principaux points faibles constatés par l'équipe Uber est l'absence fréquente de chauffeurs lorsque les utilisateurs ont besoin d'eux. Par exemple, un utilisateur peut se trouver dans le quartier financier de San Francisco, tandis que les chauffeurs Uber recherchent des clients à Castro.

(Si vous n'êtes pas familier avec la région de la baie, consultez Google Maps )

Même si les deux quartiers ne sont pas très éloignés, les utilisateurs devraient tout de même attendre 10 à 15 minutes avant d'être pris en charge, ce qui est trop long. Les recherches d'Uber montrent que les utilisateurs acceptent d'attendre 5 à 7 minutes, sans quoi ils annuleraient leur course.

L'équipe de données d'Uber aimerait donc travailler sur un projet dans lequel son application recommanderait des zones chaudes dans les grandes villes où se trouver à tout moment de la journée.

#### Objectifs 🎯
Uber dispose déjà de données sur les prises en charge dans les grandes villes. Votre objectif est de créer des algorithmes qui détermineront les zones sensibles où les chauffeurs doivent se trouver.Vous devrez donc :

- Créer un algorithme pour trouver les zones chaudes
- Visualiser les résultats sur un tableau de bord
  
#### Portée de ce projet 🖼️
Pour commencer, Uber souhaite tester cette fonctionnalité à New York. Vous vous concentrerez donc uniquement sur cette ville.

#### Aides 🦮
Pour vous aider à réaliser ce projet, voici quelques conseils qui devraient vous aider :

Le clustering est votre ami    
Les techniques de clustering sont parfaitement adaptées à ce travail. Imaginez : tous les points de collecte peuvent être regroupés en différents clusters. Vous pouvez ensuite utiliser les coordonnées des clusters pour identifier les zones sensibles 😉

Créez des cartes avec plotly  
Consultez la documentation de Plotly : vous pouvez créer des cartes et les remplir facilement. Bien sûr, il existe d'autres bibliothèques, mais celle-ci devrait faire l'affaire.

Commencez petit et grandissez
Même si Uber souhaite définir des zones sensibles par heure et par jour de la semaine, il est conseillé de commencer petit . Choisissez un jour à une heure donnée, puis généralisez votre approche.

#### Livrable 📬
Pour mener à bien ce projet, votre équipe doit :

- Avoir une carte avec des zones chaudes en utilisant n'importe quelle bibliothèque Python (plotly ou autre chose).
- Vous devriez au moins décrire les zones chaudes par jour de la semaine.
- Comparer les résultats avec au moins deux algorithmes non supervisés comme KMeans et DBScan.
