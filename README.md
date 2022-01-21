# USB_Multiboot

Creer une clé USB multi Boot avec Ventoy

Pourquoi Ventoy
- Ventoy soulève la problématique du : 
1 ISO → une clé USB.     
Malheureusement les logiciels connues comme Rufus ou Etcher sont
Limités . 
- Ventoy permet d'utiliser un seul support de stockage : 
une clé USB = 1 partition → boot + 1 partition → stockage de tous les ISO.

Lien:
Lien github : https://github.com/ventoy/Ventoy/rele

Si vous rencontrez une erreur du type :
"An error occurred during the installation. You can replug the USB and try again" à 2:53, vous pouvez la corriger en suivant cette procédure : https://bit.ly/2YlyWDl

Personnaliser la cle USB Mulitiboot Ventoy

Ventoy cree une partition EFI 

Tester la clé USB avec le design si ca fonctionne correctement sans avoir à chaque fois à booter sur la cké
 avec l'émulateur MobaLiveCD
- Aller sur le site Ventoy =>
Site officiel de Ventoy : https://www.ventoy.net/
- clicker sur Documentation
- clicker Theme Plugin
- Séléctionner le script jason
- Ouvrir une page Bolc-note ou visual studio Code
- Coller la sélection et enregiter le fichier avec l'extension .json
- Le site Ventoy propose plusieurs théme GRUB , clicker dessus et séléctionner un théme au choix
- Télécharger le theme et l'extraire
- Copier le chemin du fichier theme.txt et le coller dans le script de json
faire le test sur MobaLiveCD



- Installer MobaLiveCD => Lien:
mobatek.net
- L'executer en tant qu'administrateur


Permet de: 
- Tester Les CD bootables ("LiveCD") par émulation
- On peut soit associer ce programme au menu contextuel des fichiers ISO, soit lancer directement un LiveCD
- Comment tester un système d'exploitation en direct amorçable à partir d'une clé USB et d'un CD / DVD directement sur le système d'exploitation Windows avec l'application MobaLiveCD ou MobaLiveUSB.

- Comment prévisualiser votre CD ou clé USB amorçable directement sur Windows avant, pour voir s'il démarre ou s'il fonctionne ou non.
- exécutez ou testez votre clé USB amorçable sous Windows,
- exécutez ou testez votre iso bootable sur windows,
- lancez ou testez votre live bootable cd dvd ou usb sur windows,

Liens utile pour personnaliser notre périphérique USB Bootable avec #Ventoy sous #Windows10!

Global Control Plugin : https://www.ventoy.net/en/plugin_cont...

Theme Plugin : https://www.ventoy.net/en/plugin_them...

Grub themes : https://www.gnome-look.org/browse/cat...

Menu Class Plugin : https://www.ventoy.net/en/plugin_menu...

Menu Alias Plugin : https://www.ventoy.net/en/plugin_menu...
