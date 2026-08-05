🇬🇧 English Version

# Detailed Description: Google HTML Studio

**Google HTML Preview** (also called Google HTML Studio) is a single-page, interactive web application designed for editing and previewing HTML and CSS code in real time. Featuring Google's visual identity, including its four signature colors (blue, red, yellow, green) and the use of the "Roboto" typeface, the tool is divided into two main work areas: a code editor and a dynamic preview area.

### 🎨 Interface and Design

* **Visual Theme:** The interface adopts a clean and uncluttered style with white panels featuring very rounded corners (24px) and soft box shadows that intensify on hover or when focused.
* **Responsive Design:** The interface is responsive; using a media query, the column layout (side-by-side) automatically switches to a vertical layout (stacked) on screens with a width of 768 pixels or less.
* **Header:** The top navigation bar includes a stylized logo, a language switch for the interface, and badges confirming "Live Sync" and the creator's credits ("Foufy_2.0").

### ⚙️ Main Features

* **Synchronized Code Editor:** The left panel contains a `textarea` for entering HTML/CSS code. It is linked to a sidebar that automatically generates and displays line numbers. JavaScript ensures that the editor's vertical scrolling and the line number scrolling remain perfectly synchronized.
* **Real-Time Preview:** The right panel uses an `iframe` element that intercepts keystrokes in the code editor to instantly rewrite and refresh the displayed content.
* **Bilingual System (FR/EN):** A translation object (`i18n`) allows you to instantly switch the entire user interface between French and English. This changes the button text, tooltips, statuses, and even the default HTML code template provided when the page loads.
* **Flexible Fullscreen Modes:** Each panel (the editor and the preview) has its own fullscreen button. When a mode is activated, the application header is hidden, and the selected panel expands to occupy 100% of the window's height and width.
* **Local Download:** An action bar allows you to enter a custom filename in a dedicated field. A "Download" button then uses a JavaScript function (creating a `Blob` object) to convert the entered code into a real `.html` file and force its download to the user's machine. A reset button also allows you to restore the default startup code.

<img width="1919" height="1079" alt="Interface 1" src="https://github.com/user-attachments/assets/6889f33d-3d06-43dd-bdfa-8409e930fd09" />

Here is the link to the online version : https://foufy20.github.io/Preview_HTML_Code_.html/

---

🇫🇷 Version Française

# Description Détaillée : Google HTML Studio

**Google HTML Preview** (aussi appelé Google HTML Studio) est une application web interactive d'une seule page conçue pour éditer et prévisualiser du code HTML et CSS en temps réel. Reprenant l'identité visuelle de Google, notamment ses quatre couleurs emblématiques (bleu, rouge, jaune, vert) et l'utilisation de la typographie "Roboto", l'outil se divise en deux zones de travail principales : un éditeur de code et un espace d'aperçu dynamique.

### 🎨 Interface et Design

* **Thème visuel :** L'interface adopte un style clair et épuré avec des panneaux blancs aux bords très arrondis (24px) et des ombres douces (box-shadow) qui se renforcent lors du survol ou du focus.
* **Responsive Design :** L'interface est adaptative ; grâce à une requête média (media query), la disposition en colonnes (côte à côte) bascule automatiquement en disposition verticale (en pile) sur les écrans dont la largeur est inférieure ou égale à 768 pixels.
* **En-tête (Header) :** La barre de navigation supérieure intègre un logo stylisé, un interrupteur de langue pour l'interface, ainsi que des badges confirmant la "Synchronisation en direct" et les crédits du créateur ("Foufy_2.0").

### ⚙️ Fonctionnalités Principales

* **Éditeur de code synchronisé :** Le panneau de gauche contient une zone de texte (`textarea`) dédiée à la saisie du code HTML/CSS. Il est couplé à une colonne latérale qui génère et affiche automatiquement les numéros de ligne. Le script JavaScript assure que le défilement vertical (scroll) de l'éditeur et celui des numéros de ligne restent parfaitement synchronisés.
* **Aperçu en temps réel :** Le panneau de droite utilise un élément `iframe` qui intercepte les événements de frappe (`input`) dans l'éditeur de code pour réécrire et rafraîchir instantanément le contenu affiché.
* **Système Bilingue (FR/EN) :** Un objet de traduction (`i18n`) permet de basculer instantanément l'intégralité de l'interface utilisateur entre le français et l'anglais. Cela modifie le texte des boutons, les infobulles, les statuts, et même le modèle de code HTML fourni par défaut lors du chargement de la page.
* **Modes Plein Écran Flexibles :** Chaque panneau (l'éditeur et l'aperçu) dispose de son propre bouton plein écran. Lorsqu'un mode est activé, l'en-tête de l'application est masqué et le panneau sélectionné s'étend pour occuper 100 % de la hauteur et de la largeur de la fenêtre.
* **Téléchargement local :** Une barre d'actions permet d'entrer un nom de fichier personnalisé dans un champ dédié. Un bouton "Télécharger" utilise ensuite une fonction JavaScript (créant un objet `Blob`) pour convertir le code saisi en un véritable fichier `.html` et forcer son téléchargement sur la machine de l'utilisateur. Un bouton de réinitialisation permet également de restaurer le code de démarrage par défaut.

<img width="1919" height="1079" alt="Interface 2" src="https://github.com/user-attachments/assets/636ad851-b520-4534-84de-d641752affc0" />

Voici le lien vers la version en ligne : https://foufy20.github.io/Preview_HTML_Code_.html/
