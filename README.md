# APIResulatExamenMEN
Web scrapping qui permet d'obtenir les résultats de BEPC et CEPE à Madagascar
## Installation
Inclure simplement le fichier [MENExamResult.class.php](./MENExamResult.class.php) dans votre code
```php
include 'MENExamEesult.class.php';
```
## Exemple d'utilisation
  ### BEPC
```php
Miavaka\MENExamResult::bepc("Miavaka"); //Nom du (de la) candidat(e)
Miavaka\MENExamResult::bepc("12345678-A12/12"); //N° Matricule
```
  ### CEPE
```php
Miavaka\MENExamResult::cepe("Miavaka"); //Nom du (de la) candidat(e)
Miavaka\MENExamResult::cepe("12345678-A12/12"); //N° Matricule
```
  ### Autres
  D'autres fonctions sont disponibles comme 
  ```php
Miavaka\MENExamResult::listCisco(Miavaka\MENExamResult::EXAM_BEPC);
```
N'hésitez pas à regrader le code
## Contribution

Les contributions sont ce qui rend la communauté open source si incroyable pour apprendre, inspirer et créer. Toutes les contributions que vous apportez sont **grandement appréciées**.

Si vous avez une suggestion qui pourrait améliorer cela, veuillez cloner le dépôt et créer une pull request. Vous pouvez également simplement ouvrir une issue avec le tag "enhancement" (amélioration).
N'oubliez pas de donner une étoile au projet ! Merci encore !
