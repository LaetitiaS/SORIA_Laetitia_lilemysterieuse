## Objectifs généraux
Dans le cadre d'un projet pour le master Humanités digiatles, j'ai dût produire un document qui analyse une œuvre de fiction. Pour cela, j'ai choisi " L'île mystérieuse "de Jules vernes. Après l'encodage de l'oeuvre, je réaliserais ensuite une analyse du document sur Iramuteq avec les visualisation de type nuages de mots-clés, la classification automatique et le nombre d’occurrences. 

### Étape 1 
Une fois l'oeuvre trouvé sur Wikisource, j'ai ensuite converti le document en txt pour le rendre utilisable. Puis, j'ai nettoyé le documents en supprimant les lignes inutiles et en faisant l'ocodage suivant : 

**** *chapitre1_partie1 

Cela m'a permi de pouvoir distinguer chaque partie et chaque chapitre. 

Voici le lien de ce document : [LÎle-mystérieuse_Jules-Verne.txt](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/LI%CC%82le-myste%CC%81rieuse_Jules-Verne.txt)

### Étape 2

Dans cette étape j'ai dût retrouver la version Epub de l'oeuvre choisi. Pour cela, je l'ai télécharger sur le site beq.ebooksgratuits.com. 

Voici le lien de ce document : [Verne-L_Ile_mysterieuse (1) .epub](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/Verne-L_Ile_mysterieuse%20(1).epub)

### Étape 3 

#### Statistique

Une fois le document chargé dans Iramituq, j'ai obtenu dans "Statistique", le resume, qui décrit l'éatt du corpus CSV. 

<br/> Nombre de textes : 61 
<br/> Nombre d'occurences : 210 618
<br/> Nombre de formes : 7 659 
<br/> Nombre d'hapax : 2 633 
<br/> Moyenne d'occurences par texte : 3 452.75

![zipf.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/zipf.png)

Ici, on peut constater que Iramutuq a égalment crée des fichiers CSV. À savoir : 
<br/> [total.csv] (https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/CSV/total.csv) 
Il s'agit de toute les formes et leur effectif.

<br/> [formes_actives.csv] (https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/CSV/formes_actives.csv)
Il s'agit des formes actives et leur effectif.

<br/> [formes_supplémentaires.csv] (https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/CSV/formes_suppl%C3%A9mentaires.csv) 

<br/> hapax.csv 
Il s'agit du nombre de mots le moins utilisés dans l'oeuvre. 

#### Spécificité et AFC 

Ici, il s'agit de produire une analyse factorielle des correspondances sur un tableau de contingence qui croise formes actives et les variables.

Pour obtenir le résulat ci dessous j'ai séléctionné dans le choix des variables_formes utilisés, les variables actives et supplémentaires avec une fréquence à 60. 
![afcf_row.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/afcf_row.png)

![afcf_col.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/afcf_col.png)

Pour obtenir des couleurs à ce graphiques j'ai sélectionné la case "Taille du texte proportionelle à la fréquence".

![graph_afc_1.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/graph_afc_1.png)

<br/> Ensuite, j'ai voulu comparer les trois premiers chapitres et les trois 2à derniers de la partie 1,2 et 3. 

Voici le rérsulats obtenu pour les chapitres 1 :
![graph_afc_13.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/graph_afc_13.png)

Voici le rérsulats obtenu pour les chapitres 20 :
![graph_afc_11.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/graph_afc_11.png)

#### Analyse des similitudes

Ici, j'ai réalisé l'analyse des similitudes. Pour cela j'ai compté dans un premier temps tout les effectifs (paramètres par defauts) : 3580 avec un indice de coocurrence. 

![graph_simi_1.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/graph_simi_1.png)

Pour obtenir un resulats plus précis, j'ai ensuite restreint à un effectif à 150 et j'ai coché la case Communauté.
![graph_simi_15.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/graph_simi_15.png)

On peut aussi dans cette fonction, regrouper par Communauté et en Halo. Pour avoir quelque chose de plus intéréessant j'ai choisi de comparer encore une fois les chapitres 1 de la partie 1,2 et 3 ainsi que les chapitres 20 de la partie 1, 2 et 3. 

![graph_simi_2.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/graph_simi_2.png)

![graph_simi_3.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/graph_simi_3.png)

























Pour ajouter photos 
![le nom de l'image](mettre url de l'image)
![zipf.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/zipf.png)
![afcf_col.png](https://github.com/LaetitiaS/SORIA_Laetitia_lilemysterieuse/blob/master/images/afcf_col.png)

