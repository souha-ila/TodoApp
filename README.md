![logo](https://ueuromed.org/sites/default/files/2020-02/eidia.png)
# **RAPPORT DE TP: [ToDo Application using containers](https://anassbelcaid.github.io/CS311/todoapp/)**
## OBJECTIFS DE TP:
<ul>
  <li>Le but du devoir est de créer une application pour gérer vos tâches. Il devrait avoir toutes les fonctionnalités de l'application principale telles que
    les menus, les actions et la barre d'outils. </li>
  <li>L'application doit stocker une archive de toutes les tâches en attente et terminées.</li>
</ul>


## INTRODUCTION: 
<p>Qt est un logiciel puissant qui permet aux développeurs de développer des applications dans un cadre de base de code pour n'importe quelle plate-forme.
Qt se compose de 2 parties ; Qt Designer et partie codage.
 </p>
 <p>  Qt Designer est l'endroit où vous construisez l'interface utilisateur (UI) pour l'application et la partie code est l'endroit où la fonction logique de l'UI est implémentée.</p>


## Caractéristiques :

<p>Dans cette application de la ToDoList, l'utilisateur aura les options suivantes :</p>
<ul>
  <li>  Un utilisateur devrait pouvoir fermer l'application bien sûr. </li>
  <li> Une application Todo ne peut être utile que si elle offre la possibilité de créer de nouvelles tâches .  </li>
  <li>  La vue du widget principal doit être divisée en trois zones :
  <ul>
   <li> La première zone (et persistante) affiche la liste des tâches du jour .  </li>
    <li> Le second est réservé aux tâches en attente (tâches pour le futur).  </li>
    <li> Enfin, le troisième montre l'ensemble des tâches terminées .  </li>
  </ul>
  </li>
  <li>  les tâches saisies dans votre application doivent rester dans l'application lors d'une utilisation future.  </li>
</ul>

## La creation du Projet

 créer le projet Ensuite, choisir la BaseClass de QMainWindow  car  QMainWindow a une interface utilisateur prédéfinie ; barre de menus, une barre d'état, une barre d'outils et d'autres widgets .
 


![MainWindow](https://raw.githubusercontent.com/souha-ila/TodoApp/main/main.PNG)

L'utilisation des connaissances reçues dans le cour permet de créer une mise en page simple pour notre application "TodoAPP" avec mainwindow.ui comme indiqué sur l'image ci-dessous:

![MainWindow](https://raw.githubusercontent.com/souha-ila/TodoApp/main/app.PNG)








