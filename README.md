# Hypertension_arterielle

<div>
    <img Align="left" alt="Hypertension" width="200px" src="https://github.com/laetdata/Hypertension_arterielle/blob/main/img/hypertension.png" style="padding-right:10px;" />
</div>
<br />
                                                                                                                                           

---

<img Align="left" alt="Sante_publique" width="400px" src="https://github.com/laetdata/Hypertension_arterielle/blob/main/img/sante_publique.png" style="padding-right:10px;" />

L'agence "Santé Publique France" a lancé un appel à projets pour trouver des idées innovantes d'applications en lien avec l'alimentation. 
Nous participons à cet appel à projet et nous avons proposé une idée d'application. 
<br>
✔Le jeu de données fournit pour cet appel à projet est le fichier Open Food Facts disponoble sur le site world.openfoodfacts.org <br>

---
<br />
<br>
Notre mission était de : 
<br>
✔ Traiter le jeu de données en réflecissant à une idée d'application, en répérant des vraiables pertinentes en nettoyant les données et en automatisant les traitements.  <br>
✔ Faire des analyses en rapport avec l'idée d'application et de justifier la faisabilité (ou non) de l'application à partir des données OpenFoodFacts.  <br>

<br />
                                                                                                                                      

---
<br />
Pour répondre remplir à notre mission, nous avons d'abord défini ce qu'est l'hypertension.

L'hypertension artérielle est une maladie cardiovasculaire. 
Elle est caractérisée par une tension élevée. Si elle n'est pas pris en charge, elle provoque des problèmes à long terme comme par exemple l'infractus du myocarde, l'accident cérébrel ou l'insuffisance cardiaque.

Selon l'OMS, elle est responsable de 17 millions de décès par an soit 1/3 de la mortalité totale. Selon Santé Publique France, l'hypertension artérielle est la pathologie chronique la plus fréquente en France et un facteur de risque majeur de pathologies vasculaires.

Pour réduire le risque pour l'hypertension, il faut avoir un poids normal, avoir une activité sportive, limiter la consommation d'alcool et manger sain. 
Il faut faire notamment attention à une alimentation trop riche en sel et pauvre en potassium. 

<br />
                                                                                                                                      

---


<img Align="left" alt="Hypertension_arterielle" width="400px" src="https://github.com/laetdata/Hypertension_arterielle/blob/main/img/application.png" style="padding-right:10px;" />

<br />
L'idée est de créer une application qui lorsqu'on scanne le code d'un produit, elle nous dit si un hypertendu peut le consommer sans moderation, avec modération, ou s'il doit l'éviter. 

Si le produit n'existe pas dans la base de données , il peut-être rajouté. Et, l'application doit automatiquement le classer. 
Pour voir la faisabilité de cette application nous avons nettoyé les données, nous les avons analysées, et nous avons fait une ACP et un clustering. 

<br />
                                                                                                                                      

---
<br />

Pour respecter les contraintes nutritionnels d'un hypertendu, nous avons repérer les variables pertinentes. 


<br />
<img Align="left" alt="traitement_des_valeurs_manquantes" width="300px" src="https://github.com/laetdata/Hypertension_arterielle/blob/main/img/traitement_des_valeurs_manquantes.png" style="padding-right:10px;" />
Nous avons appliqué différentes méthodes de nettoyage de données. Nous avons remplacé les valeurs nulles par la moyenne ou la médiane sur des groupes homogènes. On a aussi fait le traitement des valeurs manquantes par KNN. Et enfin nous avons traité les valeurs manquantes en les supprimant ce qui nous a donné de meilleurs résultats. 

                                                                                                                                      

---

<br />
<img Align="left" alt="box_plot" width="200px" src="https://github.com/laetdata/Hypertension_arterielle/blob/main/img/box_plot.png" style="padding-right:10px;" />

Nous avons traité les outliers. 
<img Align="right" alt="box_plot_sans_outliers" width="200px" src="https://github.com/laetdata/Hypertension_arterielle/blob/main/img/box_plot_sans_outliers.png" style="padding-right:10px;" />

---

<br />

Après avoir fait l'ACP et le clustering, nous pouvons voir dans quelle catégorie appartient chaque aliment par rapport à l'hypertendu. 
<br />
<img  Align="center" alt="classification" width="400px" src="https://github.com/laetdata/Hypertension_arterielle/blob/main/img/classification.png" style="padding-right:10px;" />

