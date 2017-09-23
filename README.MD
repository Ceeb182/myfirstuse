![FrSky - Let me set the limits](_media/FrSky_title_728x96.png "Let me set the limits")

# [![Flag FR>](_media/Flag_FR.png "Français")](#FR_Section) **Bienvenue** / [Cliquez sur votre langue](#FR_Section)
# [![Flag EN>](_media/Flag_EN.png "English")](#EN_Section) **Welcome** / [Click on your language](#EN_Section)

----------------------------------------------------------------------------------

![Logo Dépos](_media/Logo-NonofficialFrSkydocuments-h41.png "Traductions de documents FrSky") <a name="FR_Section"></a>

----------------------------------------------------------------------------------

>## ![Warning>](_media/Logo-warning.png "Mise en garde") Attention :  
>Ceci n'est pas un site officiel de FrSky.  
>FrSky n'est pas responsable de l'utilisation des documents présents sur ce site.  
>FrSky est une marque déposée dont le site officiel est https://www.frsky-rc.com/  
>FrSky a donné un accord de principe à la mise en place de ce dépôt.  
>FrSky est informé de toute nouvelle parution de documents sur ce dépos.  
>Pour faciliter le contrôle par FrSky :  
>- l'arborescence des dossiers est volontairement en Anglais  
>- tous les fichiers Readme.md possède une section en Anglais  
>- toutes les notes de versions comportent une section en Anglais  

# ![Flag FR>](_media/Flag_FR.png "Français") De la documentation FrSky en Français ! 
A l'origine, je suis un membre du forum francophone http://frskytaranis.forumactif.org/ pour lequel j'ai posté quelques traductions françaises de la documentation FrSky. Aujourd'hui, compte-tenu du nombre de téléchargement, il est temps de partager ce travail et de l'enrichir avec la communauté.

Vous trouverez sur ce dépos 3 types de documentation en Français dans le repertoire ["Latest_Release/FR"](Latest_Release/FR) :

- Version **Base** : une traduction <label style="text-decoration: underline;";>la plus fidèle possible</label> du document FrSky 
- Version **Plus** : une traduction améliorée du document FrSky <label style="text-decoration: underline;";>enrichie d'informations</label> non-officielles
- Version **Inédit** : une documentation <label style="text-decoration: underline;";>inédite</label> sur un produit ou une procédure

### Tous les documents finalisés sont ici : ![Book](_media/Logo-Book.png "Doc PDF") ["Latest_Release/FR"](Latest_Release/FR) ![Book](_media/Logo-Book.png "Doc PDF")
<br>
Vous voulez en savoir plus ? Voici une mini **FAQ** :

- [Qui traduit et réalise ces documents ?](#FR_Who)
- [Quels sont les logiciels utilisés pour réaliser ces documents ?](#FR_Soft)
- [Comment s'explique l'arborescence du projet ?](#FR_Tree)
- [Comment contribuer ?](#FR_Contribute)
- [Quelle est la licence des documents ?](#FR_Licence)

<a name="FR_Who"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) Qui traduit et réalise ces documents ? 
Je suis Ceeb182, un bénévole qui est tombé dans le chaudron magique des possibilités offertes par le matériel FrSky et ses OS.

Pour le moment, je réalise seul les documents français présents dans le dossier "Latest Release".

Vous trouverez aussi d'autres de mes documents sur OpenTx directement sur le très bon site web francophone http://frskytaranis.forumactif.org/ à la section "Méga Tuto". Pour avoir un aperçu du travail, il faut en moyenne 8h pour créer une page de documentation si un modèle existe déjà dans une autre langue.

Je fais cela bénévolement, sur mon temps personnel. Je laisse libre d'accès les documents et les fichiers de travail correspondant. 

**Si vous souhaitez me soutenir ou me remercier, alors vous pouvez cliquer sur le lien suivant :** ![Bouton_Donation](_media/Logo-DonateCeeb182.png)

<a name="FR_Soft"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) Quels sont les logiciels utilisés pour réaliser ces documents ?
Les logiciels utilisés sont :

- ![Inkscape>](_media/Logo-Inkscape.png) **Inkscape** : logiciel de dessin vectoriel (http://www.inkscape.org/).
- ![PDFtk>](_media/Logo-PDFtk.png) **PDFtk** : assemblage du document final PDF (https://portableapps.com/apps/office/pdftk_builder_portable)
- ![Gimp>](_media/Logo-Gimp.png) **Gimp** : logiciel de retouche d'image (http://www.gimp.org/)
- ![NotepadPP>](_media/Logo-Notepadpp.png) **Notepad++** : édition de fichier texte (https://notepad-plus-plus.org/)
- ![ZintBCSt>](_media/Logo-ZintBCSt.png) **Zint Barcode Studio** : génération de code barre et de QRCode (https://portableapps.com/apps/utilities/zint_barcode_studio_portable)

Inkscape est l'outil principal de création du document final. Souvent, tous les éléments de la documentation initiale sont redessinnés (dessin et texte) avec Inkscape pour réaliser le document final. Les propriétés du document sont contenues dans un QR code généré avec Zint Barcode Studio. Chaque page d'un document est un fichier SVG unique. Puis chaque page SVG est convertie en PDF, toujours avec Inkscape. PDFtk permet d'assembler les différentes pages.

<a name="FR_Tree"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) Comment s'explique l'arborescence du projet ?
Pour faire simple, il y a deux grands dossiers :

- ![Folder_icon>](_media/Logo-Folder.png) "**Working folder**" est le repertoire de conception des documents (l'usine d'édition/conception),
- ![Folder_icon>](_media/Logo-Folder.png) "**Latest Release**" repertorie uniquement les dernières documentations achevées au format PDF (la bibliothèque finale).

Si nous allons un peu plus dans le détail, vous pouvez noter que "**Working folder**" comporte pour chaque produit, un sous-répertoire distinct comme par exempe "**Receiver - X8R**", "**Sensor - VARIO**"...

Enfin pour chaque produit, il y a trois sous-répertoires. 
Par exemple pour le produit "**Receiver - X8R**", il y a :

 - ![Folder_icon>](_media/Logo-Folder.png) "**X8R-Stock**" pour toutes les données récoltées pour la création de votre document
 - ![Folder_icon>](_media/Logo-Folder.png) "**X8R-Source**" contient toutes les versions des documents au format SVG, accompagnées de sa note de version en MD
 - ![Folder_icon>](_media/Logo-Folder.png) "**X8R-Release**" contient toutes les versions des documents au format PDF, accompagnées d'une note de version globale en MD

Vous souhaitez en savoir plus sur l'organisation du dépot : un fichier *README.MD* est présent dans chacun des grands répertoires de l'arborescence.

<a name="FR_Contribute"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) Comment contribuer ?
Aujourd'hui, avec ce dépos nous pouvons collaborer pour :

- vérifier et corriger les traductions déjà réalisées : orthographe, grammaire, tournure de phrase...
- proposer de nouvelles traductions littérales
- mettre à disposition les liens vers du contenu permettant la création des versions "Plus" ou "Inédites"
- proposer le travail actuel dans d'autres langues

Vous voulez participer : contactez-moi à Ceeb182@laposte.net (faisant cela bénévolement, le délai de réponse peut parfois être aléatoire).

Vous n'êtes ni Anglais ni Français et vous voulez traduire la documentation dans votre propre langue, contactez-moi à Ceeb182@laposte.net

Vous voulez contribuer en me soutenant financièrement, alors cliquez sur ce lien : ![Bouton_Donation](_media/Logo-DonateCeeb182.png)

<a name="FR_Licence"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) Quelle est la licence des documents ?
Les documents sont produits sous la licence "Creative Commons By Sa" (https://creativecommons.org/licenses/by-sa/4.0/) pour permettre au plus grand nombre d'utiliser ce contenu partiellement ou en totalité. Néanmoins, FrSky peut nous demander de retirer ou rectifier tout ou partie du contenu du présent dépos. 

![<Logo CCBYSA>](_media/Logo-CCBYSAh22.png "Creatice Commons By Sa") *Auteur : Ceeb182@laposte.net / 2017 / Source : github/ceeb182/nonofficial_frsky_doc/README.MD*
<br>
<br>
<br>

-------------

![Logo Dépos](_media/Logo-NonofficialFrSkydocuments-h41.png "Traductions de documents FrSky")<a name="EN_Section"></a>

-------------


>## ![Warning>](_media/Logo-warning.png "Warning") Warning :<a name="FR_Section"></a>
>This is not a FrSky website.  
>FrSky is not responsible for the use of documents on this site.  
>FrSky is a registered trademark whose official site is https://www.frsky-rc.com/  
>FrSky agreed to the principle of setting up such a repository.  
>FrSky is informed of any new publication of documents on this repository  
>To make FrSky checks easier :  
>- the folder tree is voluntarily in English  
>- all README.MD files have a section in English  
>- all release notes have a section in English  


# ![Flag EN>](_media/Flag_EN.png "English") From FrSky documentation in French !
Originally, I am a member of the french speaking forum http://frskytaranis.forumactif.org/ for which I did some French translations of the FrSky documentation.
Today, considering the large number of downloads, it is time to share this work and enrich it with the community.

You will find, on this repository, 3 types of documentation in French in the directory "Latest Release/FR":

- **Basic** version: the <label style="text-decoration: underline;";>most faithful</label> translation of the FrSky document
- **Plus** version: an improved translation of the FrSky document <label style="text-decoration: underline;";>enriched with unofficial information</label>
- **Unpublished** version: a <label style="text-decoration: underline;";>new</label> documentation on a product or a procedure

### All finalized documents are here: ![Book](_media/Logo-Book.png "Doc PDF") ["Latest_Release/FR"](Latest_Release/FR) ![Book](_media/Logo-Book.png "Doc PDF")
<br>
You want to know more ? here is a tiny FAQ :

- [Who translates and makes these documents ?](#EN_Who)
- [What softwares are used to make these documents ?](#EN_Soft)
- [How to explain the project tree ?](#EN_Tree)
- [How to contribute ?](#EN_Contribute)
- [What is the license of the documents ?](#EN_Licence)

<a name="EN_Who"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) Who translates and makes these documents ?
I am Ceeb182, a volunteer who has fallen into the magical cauldron of the possibilities offered by the FrSky hardware and its OS.

Currently, I do the French documents in the "Latest Release" folder.

You will also find more of my documents on OpenTx directly on the very good French website http://frskytaranis.forumactif.org/ in the section "Mega Tuto". For an overview of the work, it takes an average of 8 hours to create a documentation page if a model already exists in another language.

I do this on a volunteer basis, during my spare time. I leave free access to the documents and the corresponding work files

If you wish to support me or thank me, then you can click on the following link: ![Book](_media/Logo-DonateCeeb182.png)

<a name="EN_Soft"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) What softwares are used to make these documents ?
Softwares used are :

- ![Inkscape](_media/Logo-Inkscape.png) **Inkscape** : vector drawing software (http://www.inkscape.org/)
- ![PDFtk](_media/Logo-PDFtk.png) **PDFtk** : to merge several pages to do one PDF document (https://portableapps.com/apps/office/pdftk_builder_portable)
- ![Gimp](_media/Logo-Gimp.png) **Gimp** : image editor (http://www.gimp.org/)
- ![NotepadPP](_media/Logo-Notepadpp.png) **Notepad++** : text editor (https://notepad-plus-plus.org/)
- ![ZintBCSt>](_media/Logo-ZintBCSt.png) **Zint Barcode Studio** : barcode generator (https://portableapps.com/apps/utilities/zint_barcode_studio_portable)

Inkscape is the main tool for making the final document. Often all elements of the original documentation are redrawn (drawing and text) with Inkscape to make the final document. The document properties are contained in a QR Code generated with Zint Barcode Studio. Each page of a document is a single SVG file. Then each SVG page is converted to PDF, again with Inkscape. PDFtk allows to assemble the different pages.

<a name="EN_Tree"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) How to explain the project tree ?
To explain it simply, there are two main folders :

- ![Folder_icon>](_media/Logo-Folder.png) "**Working Folder**" is the folder of design documents (editing / factory of design)
- ![Folder_icon>](_media/Logo-Folder.png) "**Latest Release**" lists only the last completed documents in PDF format (the final library).

If we go a bit more in detail, you can note that "**Working folder**" contains for each product a separate subdirectory such as "**Receiver - X8R**", "**Sensor - VARIO**"...

Finally, for each product, there are three subdirectories.
For example, for the product "**Receiver - X8R**", there are:

 - ![Folder_icon>](_media/Logo-Folder.png) "**X8R-Stock**" for all the data collected for the creation of your document
 - ![Folder_icon>](_media/Logo-Folder.png) "**X8R-Source**" contains all the versions of the documents in SVG format, followed by his release note in MD
 - ![Folder_icon>](_media/Logo-Folder.png) "**X8R-Release**" contains all the versions of the documents in PDF format, followed by one global release note in MD
  
You would like to know more about the management of the repository: a README.MD file is present in each of the major directories of the tree.

<a name="EN_Contribute"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) How to contribute ?
Today, with this repository we can collaborate to:

- verify and correct the translations already carried out: spelling, grammar, sentences sense...
- propose new faithfull translations
- make available the links to content allowing the creation of versions "Plus" or "Unpublished"
- propose current work in other languages

You want to participate : contact me at Ceeb182@laposte.net (doing this voluntarily, the response time can sometimes be random).

You are neither English nor French and you want to translate the documentation in your own language, contact me at Ceeb182@laposte.net

You want to contribute by supporting me financially, then click on this link: ![Book](_media/Logo-DonateCeeb182.png)

<a name="EN_Licence"></a>
### ![Puce>](_media/Logo-PuceTriJN.png) What is the license of the documents ?
The documents are produced under the Creative Commons By Sa (https://creativecommons.org/licenses/by-sa/4.0/) license to allow as many people as possible to use this content in whole or in part. Nevertheless, FrSky may ask us to withdraw or correct all or part of the contents of this repository.

![<Logo CCBYSA>](_media/Logo-CCBYSAh22.png "Creatice Commons By Sa") *Author : Ceeb182@laposte.net / 2017 / Source : github/ceeb182/nonofficial_frsky_doc/README.MD*