# Dynamic Member Management / Gestion Dynamique des Membres

## Overview / Vue d'ensemble
This web-based application allows you to manage member data dynamically with the following features:  
Cette application web permet de gérer les données des membres de manière dynamique avec les fonctionnalités suivantes :

- Upload and view Excel files containing member data  
  Téléchargement et affichage de fichiers Excel contenant les données des membres
- Filter members by any column dynamically  
  Filtrer les membres par n'importe quelle colonne de manière dynamique
- Pagination (50 records per page)  
  Pagination (50 enregistrements par page)
- Add, update, or delete members  
  Ajouter, modifier ou supprimer des membres
- Export updated data back to Excel  
  Exporter les données mises à jour vers Excel
- Open member form as a separate page  
  Ouvrir le formulaire d’un membre sur une page séparée
- Visual enhancements: colored headers, hover effects, styled buttons  
  Améliorations visuelles : en-têtes colorés, effets de survol, boutons stylés

---

## Usage / Utilisation

### 1. Upload an Excel file / Télécharger un fichier Excel
1. Click the **Upload Excel File** button  
   Cliquez sur le bouton **Upload Excel File**
2. Select your `.xlsx` or `.xls` file containing member data  
   Sélectionnez votre fichier `.xlsx` ou `.xls` contenant les données des membres
3. The table will populate automatically  
   La table se remplira automatiquement

### 2. Filtering / Filtrage
- Enter text in any filter input to filter the table dynamically  
  Entrez du texte dans n’importe quel champ de filtre pour filtrer la table dynamiquement
- Click **Clear Filters** to reset all filters  
  Cliquez sur **Clear Filters** pour réinitialiser tous les filtres

### 3. Pagination / Pagination
- Navigate through pages using the numbered buttons or `<<` / `>>`  
  Naviguez dans les pages avec les boutons numérotés ou `<<` / `>>`

### 4. Member Form / Formulaire des Membres
- Click a row in the table to open the member form  
  Cliquez sur une ligne du tableau pour ouvrir le formulaire du membre
- Form opens at the top, scrollable if needed  
  Le formulaire s’ouvre en haut, défilable si nécessaire
- **Add / Update Member** button saves new or edited records  
  Le bouton **Add / Update Member** enregistre un nouvel enregistrement ou les modifications
- **Delete Member** prompts a confirmation message before deletion  
  **Delete Member** affiche un message de confirmation avant suppression
- **Clear Form** clears all input fields  
  **Clear Form** efface tous les champs du formulaire
- **Back to Search** returns to the table view  
  **Back to Search** retourne à la vue du tableau

### 5. Export / Exportation
- Click **Export Updated Excel** to save the current data to an Excel file  
  Cliquez sur **Export Updated Excel** pour enregistrer les données actuelles dans un fichier Excel

### 6. README / Aide
- Click **README** to open this help page in a new tab  
  Cliquez sur **README** pour ouvrir cette page d’aide dans un nouvel onglet

---

## Notes
- Ensure your Excel file has column headers in the first row  
  Assurez-vous que votre fichier Excel contient les en-têtes de colonnes dans la première ligne
- All data is stored client-side; no server required  
  Toutes les données sont stockées côté client ; aucun serveur n’est nécessaire
- Maximum rows per page: 50  
  Maximum de lignes par page : 50

---

## Credits / Crédits
Developed using HTML, JavaScript, and [SheetJS](https://sheetjs.com/) for Excel handling  
Développé avec HTML, JavaScript et [SheetJS](https://sheetjs.com/) pour la gestion Excel
