# RayliBPanClicMouse
insertion d une image avec un defilement de carte par touche fléché et clic monde et clic carte.

#  Guide du programme
L'executable vous permet de faire défiler une image dans les 4 sens.
Le clic souris vous donnera les coordonnées x,y (vecteur2d) de l image affichée
ainsi que les coordonnées globales à la fenetre. 
L'image sera "clampée" à sa taille, pas de terra incognita.


# A quoi cela sert-il ?
Cela vous permet de coder de suite des utilitaires afin  positionner sur une image qui dépasse la taille de l'écran des éléments. 
il autorise sur la bordure droite de créer un Gui sans 
#  Installation
Vous collez le tout dans un repertoire. Vous créez ensuite un sous répertoire "ressources"
Vous déplacez le graphique dans ce sous-répertoire.
![image](https://github.com/user-attachments/assets/64f58803-e32f-42ce-a300-d72cad641699)

#  Execution
Il faut un pc avec windows, raylib.dll accessible par l application.

#  Modification du programme en langage pascal
Ecrit sous pascal Fpc, il faut l 'editeur Lazarus ide installable sous windows (https://www.lazarus-ide.org/), unix ou mac. Il installera l'editeur, le compilateur fpc3.22. Il faudra installer
le paquet de guvacode pour les header de la compilation.
![image](https://github.com/user-attachments/assets/f36b9aa5-adb7-4158-8993-e3ad30b622a0)

Si vous faites un nouveau projet, vous obtiendrez cela :
![image](https://github.com/user-attachments/assets/de21b258-aecc-4042-a717-f505acbb08ee)

si vous chargez le fichier.dpr, vous modifiez, compilez et executer. 

#  Modification du programme en un autre langage (c# par exemple, c 'est le même architecte qui a fait Delphi et C#)
 vous l ecrivez simplement,  les begin end doivent etre remplacés par des {}, vous gardez les ;
 l'affectation est = et non := 
 le pascal est strict pour le type des variables, le C# est plus cool donc  vous faites facile en respectant la norme du bindinf c#cs que vous a proposé David.
 ( sinon il y a un peu de baratin pour affichage dans Pascal).
 Si vous suivez pas à pas le code, vous pouvez remplacez ligne à ligne dans votre langage préféré. 
 Rien de spécial ou objet est utilisé, si il y a une creation de vecteur, utilisez la maniere de votre langage ou le sucre de votre binding.
 Sinon, camera2d est une structure et toutes les fonctions appelés sont dans raylib.
 




