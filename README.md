# Template pour la rédaction de thèse

Ce template est issu du dépôt github [suivant](https://github.com/JeanCollomb/Template_rapport_these) qui compilent des templates du laboratoire SYMME.
Le template initial a été largement modifié, les packages ont été mis à jour et la page de garde entièrement changée.

## Fonctionnement

* Le fichier "*Manuscrit/manuscrit.tex*" est le document maître.
* Chaque section du manuscrit de thèse peut être rédigée dans son fichier .tex indépendant.
* Toutes les sections avant l'introduction générale (Dédicace, Remerciements, Table des matières, Table des figures, Liste des tableaux, Nomenclature) se situent dans le dossier "*Intro/*".
* Chaque chapitre se rédige dans le dossier correspondant.
* La bibliographie peut être modifiée à travers le fichier "*Conclusion/references.bib*".
* Toutes les annexes se gèrent dans le dossier "*Annexes/*".
* Il est possible d'ajouter/supprimer des sections (chapitre ou annexe) en créant les fichiers/dossiers adéquats et en ajoutant les correspondantes dans le fichier "*Manuscrit/manuscrit.tex*".


## Modification

* Des packages peuvent être ajoutés/supprimés dans le fichier "*Manuscrit/Packages.tex*".
* Des commandes personnalisées peuvent être ajoutées/supprimées dans le fichier "*Manuscrit/Commands.tex*".
* Les couleurs (Tableaux, références, liens ...) peuvent être modifiés dans le fichier "*Manuscrit/Packages.tex*" via le package "hyperref".
* Toutes les informations relatives à la thèse (ED, spécialité de l'ED, laboratoire d'accueil, titre de la thèse, direction de thèse, rapporteurs, jury et invités) peuvent être modifiées dans le fichier "*Page_de_garde/Page_de_garde.tex*".
* Pour modifier en profondeur la page de garde (langue, grade des membres du jury, ...), il faut regarder le fichier "*Manuscrit/meta-donnees.sty*" (section "*Definition des variables*").