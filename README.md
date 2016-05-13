# Découverte du refactoring au travers d'un exemple
<!-- => retour à la ligne, 2 espaces .... -->


> **[Un refactoring (remaniement) consiste à changer la structure interne d’un logiciel 
> sans en changer son comportement observable](http://refactoring.com/)** *(M. Fowler)*


Ce tutoriel s'appuie sur l'exemple *simplifié* du premier chapitre du livre [Refactoring, Improving the Design of Existing Code de Martin Fowler](http://martinfowler.com/books/refactoring.html) <img src="http://www.martinfowler.com/books/refactoringBook.jpg" alt="Livre Refactoring" width="70">
<!--[Livre Refactoring"](http://www.martinfowler.com/books/refactoringBook.jpg)-->

[Martin Fowler](https://twitter.com/martinfowler) propose en ligne une rubrique dédiée au [refactoring](http://refactoring.com/) dans laquelle un [catalogue de refactoring ](http://refactoring.com/catalog/) est disponible. Ces exemples de refactoring sont justement ceux décrits dans les autres chapitres de son livre.


L'exemple de refactoring va être déroulé pas à pas sous Eclipse selon les étapes suivantes :


* [Présentation de l'exemple à refactorer](refactoring_presentationExemple.md)
* [Pas de refactoring sans test !](refactoring_Step0_miseEnPlaceTests.md) 
* [Isoler le calcul du montant des frais d'une location, de l'affichage du relevé (à l'aide d'un **`Extract method`**)](refactoring_Step1_ExtractMethod.md)
* [Rendre la classe `Rental` responsable du calcul des frais de location (à l'aide d'un **`Move method`**)](refactoring_Step2_MoveMethod.md) 
* [Isoler le calcul de la somme des frais de toutes les locations de l’affichage du relevé (à l'aide d'un **`Replace Temp with Query`**)](refactoring_Step3_ReplaceTempWithQuery.md) 
* [Mettre en place le nouvel affichage au format HTML via la méthode `htmlStatement`](refactoring_Step4_Ajout_htmlStatement.md)
* [Déléguer la gestion des règles de tarification à la vidéo](refactoring_Step5_DeleguerGetCharge.md)
* [Mettre en place un système de tarification évolutif et modulable grâce au **State Pattern**](refactoring_Step6_StatePattern.md)  




Et il se terminera par :   

* [Quelques remarques en images sur l'intention du code et les commentaires](commentaires.md)  
* [Des katas pour s'entraîner au refactoring](katas.md)  
* [Quelques références autour du refactoring](references.md)  


Pour vous aider à suivre plus facilement ce tutoriel, la présentation du tutoriel disponible [ici](Refactoring_PremierExempleStepByStep.pdf) peut vous servir de roadmap.  
  

### Continuez le tutoriel par la [présentation de l'exemple à refactorer](refactoring_presentationExemple.md)  


## Licence
This material may NOT be used as course material without prior written agreement.

















