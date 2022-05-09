# Import Export Excel

> [Aller à la version française (à la fin)](#description-version-française)

## Wiki

In the [wiki](https://github.com/bimone/addins-excelexporterimporter/wiki) section, you will find most of the information from our documentation regarding the Import Export Excel Addin

![image](https://user-images.githubusercontent.com/7872003/125590861-7183a7e7-d321-418d-b446-5244b73d9785.png)


## Description
The Revit add-in Import-Export Excel 2015-2021 allows you to facilitate the management of your data in your digital models by processing it outside of Revit. First, you must export your schedule to an Excel file via the add-in, which allows you to modify your data directly in Excel (or other compatible spreadsheets). Once your information has been modified, all you have to do is import your Excel file via the add-in and your Revit schedule will automatically update with the new data. With this tool, you can ease the data management process by delegating tasks related to the information of digital models to all team members who do not have a Revit license.

As of version 20.1.0.0, a new feature has been added allowing you to export to an Excel file while respecting the layout of the schedule, for viewing purposes only.

## Addin limitations

### Read-only:
Some Revit parameters are considered "read-only" when their value is controlled by Revit. You will not be able to modify this type of parameter even if you modify it in the Excel file because you are not authorized to write in these parameters. Read-only parameters are colored gray and locked when exported to Excel so that you can distinguish them from others.

### Import constraints:
The import works only with files that have been exported in bidirectional mode using this add-in. The schedules are therefore not all importable.

Once the file has been exported, you can only modify the existing data in the fields generated during the export. Adding rows / columns will not work because they will not be recognized by Revit. However, you can fill in empty fields as long as they belong to a row / column generated by the export tool.

---

## Description (version française)
L’outil complémentaire de Revit (Export-Import Excel 2015-2021) vous permet de faciliter la gestion de vos données dans vos maquettes numériques en la traitant à l’extérieur de Revit. Dans un premier temps, vous devez exporter votre nomenclature vers un fichier Excel via l’outil complémentaire, ce qui vous permet de modifier vos données directement dans Excel (ou autre tableur compatible). Une fois vos informations modifiées, il vous suffit d’importer votre fichier Excel via l’outil complémentaire et votre nomenclature se mettra automatiquement à jour avec les nouvelles données. Avec cet outil, vous pouvez donc soulager le processus de gestion des données en déléguant des tâches liées à l’information des maquettes numériques à tous les membres de l'équipe n’ayant pas de licence d’utilisation du logiciel Revit ou ayant des connaissances limitées du logiciel.

À partir de la version 20.1.0.0, une nouvelle fonctionnalité a été ajoutée vous permettant d’exporter vers un fichier Excel en respectant au mieux la mise en forme de la nomenclature, dans un but de visualisation seulement.

## Limitations du complément

### Lecture seule :

Certains paramètres de Revit sont considérés comme «en lecture seule» lorsque leur valeur est contrôlée par le moteur de Revit. Vous ne pourrez pas modifier ce type de paramètres même si vous le modifiez dans le fichier Excel car vous n'êtes pas autorisé à écrire dans ces paramètres. Les paramètres en lecture seule sont colorés en gris et verrouillés lors de l'exportation vers Excel afin que vous puissiez les distinguer des autres.

### Contraintes d'importation :

L’importation fonctionne uniquement avec les fichiers qui ont été exportés en mode bidirectionnel à l’aide de ce complément.Les nomenclatures ne sont donc pas toutes importables.

Une fois le fichier exporté, vous ne pouvez modifier que les données existantes dans les champs générés lors de l'exportation. L'ajout de lignes / colonnes ne fonctionnera pas car elles ne seront pas reconnues par Revit. Cependant, vous pouvez remplir des champs vides tant qu'ils appartiennent à une ligne / colonne générée par l'outil d'exportation.



