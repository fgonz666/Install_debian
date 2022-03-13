# Installer debian

L'objet de ce dépôt est de servir de petite référence pour quelques personnes afin de pouvoir installer debian sur un système relativement chiffré.


L'installation décrite ici propose un `/boot` séparé et en clair - c'est la limite de la distribution _debian_ à côté duquel se trouve une partition chiffrée via `dm-crypt` et le logiciel `cryptsetup`, dans cette partition un _logical volume manager_ ou _lvm_ contenant _de facto_ les partitions racine, _swap_ et utilisateurs.

L'installation a été réalisée dans une `virtualbox` sur l'équivalent d'un ordinateur sans `efi` ou en `legacy bios / csm`.

La production elle-même est sous licence creative commons zero pour l'instant, les logiciels utilisés ou cités étant eux soumis aux licences de leurs créateurs.

Le langage de composition du document a été `Markdown` sur l'éditeur de textes `mousepad`, la compilation s'est faite via _pandoc_ et _pdflatex_, une source en LaTeX sera produite ultérieurement.

Un script, le fichier `headers.heads` est utilisé lors de la compilation pour améliorer le visuel du fichier pdf.

Je vous souhaite d'en faire un bon usage !
