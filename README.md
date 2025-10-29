<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo_dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/logo_light.png">
    <img
        alt="Neurotek Firmware"
        src="assets/logo.png">
  </picture>
</p>

<h2 align="center">
  <a href="#install">Install</a> · <a href="#list-of-changes">Features</a> · <a href="#community">Discord</a> · <a href="#support">Donate</a>
</h2>

Ce firmware personnalisé est basé sur le [Official Firmware](https://github.com/flipperdevices/flipperzero-firmware) pour [Flipper Zero](https://flipperzero.one/), et inclut de nombreuses fonctionnalités communautaires populaires. Il s'agit d'une continuité de projets communautaires antérieurs et d'un travail mené sous le nom **Neurotek Firmware** par l'auteur principal **DariusIstoc1**.

<br>
<h2 align="center">Modus Operandi</h2>

L'objectif de ce firmware est d'élargir sans cesse les possibilités du Flipper Zero, d'introduire des fonctionnalités innovantes tout en offrant une expérience utilisateur simple et hautement personnalisable. Corriger rapidement les bugs et garantir une stabilité et une compatibilité maximale sont également parmi nos priorités.

- <h4>Riche en fonctionnalités : Nous intégrons des applications tierces utiles et stables, et implémentons régulièrement de nouvelles fonctions.</h4>

- <h4>Stable : Nous visons une expérience la plus stable possible grâce à des ajustements réfléchis et à la compatibilité inter-versions.</h4>

- <h4>Personnalisable : Personnalise quasiment tout : menus, animations, icônes, nom de l'appareil, apparence du menu principal, raccourcis et bien plus — le tout depuis l'appareil, sans configurations complexes.</h4>

<br>

Pour la liste complète des ajouts, consulte la section "List of changes" plus bas.

<br>
<h2 align="center">NTK Settings</h2>

Nous proposons une application de configuration puissante, conçue pour ce firmware, qui te permet de modifier tout ce que tu imagines :

<img src="assets/settings.png" align="left" height="160vh"/>
<img align="left" height="180vh" width="10" src="https://upload.wikimedia.org/wikipedia/commons/3/3d/1_120_transparent.png">

- <ins><b>Interface :</b></ins> Modifie les animations de bureau, le menu principal, le comportement de l'écran de verrouillage, le navigateur de fichiers, etc.

- <ins><b>Protocoles :</b></ins> Configure les paramètres Sub-GHz, ajoute/supprime des fréquences personnalisées, étend les plages Sub-GHz (281-361, 378-481, 749-962 MHz) et choisis les pins GPIO pour les modules externes.

- <ins><b>Misc :</b></ins> Tout le reste : change le nom de ton Flipper, le niveau XP, les options d'écran, et configure le [RGB backlight](https://github.com/Z3BRO/Flipper-Zero-RGB-Backlight) si tu l'utilises.

<br>

<br>

<h2 align="center">Animations / Asset Packs</h2>

Nous avons développé un système d'Assets / Animations qui te permet de créer et de basculer entre tes propres `Asset Packs` en quelques pressions de boutons. C'est comme un système de thèmes simple d'utilisation.

<img src="assets/packs-folder.png" align="left" width="200px"/>
Tu peux créer ton pack ou en récupérer sur la communauté. Voir la documentation sur les formats d'Asset Packs pour savoir comment structurer un pack (Anims, Icons, Fonts).

<br clear="left"/>

<br>

<img src="assets/packs-select.png" align="left" width="200px"/>
Après avoir mis tes packs dans `SD/asset_packs/PackName/`, installe-les via l'interface du firmware.

<br clear="left"/>

<br>

<img src="assets/packs-done.png" align="left" width="200px"/>
Une fois installé, va dans `NTK Settings > Interface > Graphics` pour choisir ton pack et ajuster les options, puis redémarre.

<br clear="left"/>

<br>

<h2 align="center">Bad Keyboard</h2>

<img src="assets/badkb.png" align="left" width="250px"/>
L'application Bad-KB étend les possibilités du BadUSB natif en proposant plus d'options pour USB et Bluetooth.

En mode Bluetooth tu peux notamment usurper le nom d'affichage et l'adresse MAC pour simuler différents périphériques (ex. enceinte, clavier sans fil).  
En mode USB tu peux personnaliser le nom du fabricant, le produit et manipuler VID/PID pour des tests avancés.

<br>

<h2 align="center">List of changes</h2>

Voici une **liste non exhaustive** des changements et ajouts les plus notables pour l'utilisateur final. Pour un détail complet, consulte les changelogs et les commits du dépôt.

```txt
[Added]

- NTK App (Configuration simplifiée du firmware)
- Asset Packs (Thématisation & personnalisation)
- Plus d'options d'UI, redesigns et optimisations
- Bad-Keyboard App
- BLE Spam App
- FindMy Flipper App
- NFC Maker App
- Wardriver App
- Recherche de fichiers sur la carte SD
- Nouveaux parsers NFC et protocoles
- Sauvegarde de coordonnées pour Sub-GHz
- Spoofing simplifié (Nom, MAC, Serial)
- Configuration couleur pour modules jeux
- Modes avancés pour rétroéclairage RGB
- Gestion de fichiers sur l'appareil (Couper/Copier/Coller...)
- Mémoire des paramètres IR et support IR Blaster
- Mesures de sécurité améliorées (verrouillage au boot, reset sur codes faux)
- Gestion d'images disque (montage, affichage, Mass Storage)
- API JavaScript étendue (UsbDisk, opérations fichiers)
