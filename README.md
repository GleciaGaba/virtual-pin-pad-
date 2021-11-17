>>Virtual-Pin-Pad

>>DWWM P25 Project to a bank client: static web page with an input screem pin code and a numeric keypad.

>>Un petit projet pour un banque: écran web représentant une zone d'écran et une zone de pavé numérique, avec un code pin de 4 chiffres, de 0 à 9.

>>Nom du groupe: KISS (keep it simple, stupid).

>>Membres: Mahomed, Glécia, Mahomed Ali, Ida(scrum master).

>>Plataforme collaborative: Github(espace de stockage de travaux collaboratifs).

>>Repository: repertoire où sont stoké les fichiers du projet.

>>Kanban: tableau visuel, outil pour réduire le temps de cycle d'un processus.

>>Le intérêt de diviser le travail en petits morceaux est d'avancer de façon rapide et organisé, en identifiant nous priorités.

>>Sketch
<br>
<img src= https://user-images.githubusercontent.com/45296020/141976470-a17ca932-ef1b-40a4-bcd3-b5cfd34a4f96.jpg width=250px>


>>Sketch: la définition du sketch pour notre maquette.


>>Wireframe ( fase intermédiaire entre le sketch et la maquette)

>>Wireframe: utilisation d'un utile en-ligne pour la creation de notre wireframe, MockFlow.


<img src= https://user-images.githubusercontent.com/45296020/141993769-2c8a8e96-bdf4-4472-a1ad-a362f8c4498f.png width=250px>


>>DOCTYPE: permet de mentionner la version du langage HTML utilisée. Il est utilisé au début du document HTML, afin que les navegateurs peuvent le gérer avec les modes standarts du web. 

>>HTML: HYPER TEXT MARKUP LANGUAGE, est le code utilisé pour structurer une page web et son contenu.

>>L'élément de métadonnés (en_tête) <head>: fournit des informations générales titre et des liens des définitions vers des scripts et feuilles de style.
  
  
>> Pourquoi est-il recommandé d'avoir les styles dans un fichier à part? C'est le moyen plus pratique d'ajouter un style CSS à le site web. De cette façon, toutes les modifications apportées à un fichier CSS externe seront visibles globalement sur votre site.
  
  
>> Modèle de boîtes CSS: "The basic box model" est un module CSS qui définit les boîtes rectangulaires (y compris leurs zones de remplissage (padding) et de marges).
  
>> Sélecteurs CSS: détermine les éléments HTML à cibler avec la regle CSS.

>>Propriété CSS: spécifient le style des éléments HTML ciblés.
  
>>Liste des principaux liens utilisés pour s’aider à réaliser la maquette HTML/CSS:
  http://tutorials.jenkov.com/css/css-properties-css-rules.html
  https://developer.mozilla.org/fr/docs/Web/HTML
  https://www.codecademy.com/learn
  https://openclassrooms.com/fr/courses/1603881-apprenez-a-creer-votre-site-web-avec-html5-et-css3

  
  
  form {
  width: 390px;
  margin: 50px auto;
  background: #fff;
  padding: 35px 25px;
  text-align: center;
  box-shadow: 0px 5px 5px -0px rgba(0, 0, 0, 0.3);
  border-radius: 5px;
}

input[type="password"] {
  padding: 0 40px;
  border-radius: 5px;
  width: 350px;
  margin: auto;
  border: 1px solid rgb(228, 220, 220);
  outline: none;
  font-size: 60px;
  color: transparent;
  text-shadow: 0 0 0 rgb(71, 71, 71);
  text-align: center;
}

input:focus {
  outline: none;
}

.pinButton {
  border: none;
  background: none;
  font-size: 1.5em;
  border-radius: 50%;
  height: 60px;
  font-weight: 550;
  width: 60px;
  color: transparent;
  text-shadow: 0 0 0 rgb(102, 101, 101);
  margin: 7px 20px;
}

.clear,
.enter {
  font-size: 1em !important;
}

.pinButton:hover {
  box-shadow: #506ce8 0 0 1px 1px;
}
.pinButton:active {
  background: #506ce8;
  color: #fff;
}

.clear:hover {
  box-shadow: #ff3c41 0 0 1px 1px;
}

.clear:active {
  background: #ff3c41;
  color: #fff;
}

.enter:hover {
  box-shadow: #47cf73 0 0 1px 1px;
}

.enter:active {
  background: #47cf73;
  color: #fff;
}




































