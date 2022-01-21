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



## ETAPE1: La creation du Projet

 créer le projet Ensuite, choisir la BaseClass de QMainWindow  car  QMainWindow a une interface utilisateur prédéfinie ; barre de menus, une barre d'état, une barre d'outils et d'autres widgets .
 


![MainWindow](https://raw.githubusercontent.com/souha-ila/TodoApp/main/main.PNG)
## ETAPE2:OVERVIEW
<p>Ouvrez le fichier Votrefile.ui et il ouvrira automatiquement le fichier dans Qt Designer.</p>
<p> Notre application  devrait avoir toutes les fonctionnalités de l'application principale telles que les menus, les actions et la barre d'outils. L'application doit stocker une archive de toutes les tâches en attente et terminées</p>
<p> notre design  d'application est : </p>
![appp](https://raw.githubusercontent.com/souha-ila/TodoApp/main/app.PNG)

```cpp
