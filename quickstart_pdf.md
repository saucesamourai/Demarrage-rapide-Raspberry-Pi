![](BuildnPlay_small.png)
# Guide de démarrage rapide Raspberry Pi

Vous avez votre Raspberry Pi ? Super ! Commencons par nous assurer que vous avez bien tout les câbles et accesoires nécessaires avant de brancher et démarrer la machine pour la première fois.

## Vérification des équipements

Avant de brancher quoi que ce soit, vérifions que tout est là :

![](images/all-the-things.png)

Nous avons selectionné pour vous faire gagner du temps des produits économiques et de bonne qualité. Les prix affichés sont indicatifs et peuvent varier.

### Le Raspberry Pi et les accessoires indispensables :
Si vous n'avez encore rien acheté, le plus simple est peut être de prendre <a rel="nofollow" href="https://www.amazon.fr/gp/product/B01CI5879A/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01CI5879A&linkCode=as2&tag=curioschron01-21">le kit officiel Raspberry Pi</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01CI5879A" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />, qui comprend tous les éléments de cette section (La carte Raspberry Pi, la carte SD avec NOOBS préinstallé, l'alimentation micro USB et en plus un boîtier) pour un prix total de 66€.

Sinon, vous pouvez acheter les éléments séparément :

<img src="images/raspberry-pi.png" height="150" width="125" >
* Un Raspberry Pi 3, évidemment. 
 * <a rel="nofollow" href="https://www.amazon.fr/gp/product/B01CD5VC92/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01CD5VC92&linkCode=as2&tag=curioschron01-21">Vous le trouverez ici pour 45€ environ. </a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01CD5VC92" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
 
<img src="images/hdmi-cable.png" height="150" width="125" >
* Un câble HDMI
 * <a rel="nofollow" href="https://www.amazon.fr/gp/product/B014I8SSD0/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B014I8SSD0&linkCode=as2&tag=curioschron01-21">Nous vous suggerons ce câble HDMI 2.0 de 1,8 m à 6,5€. Ne prenez pas moins d'un mètre, c'est souvent trop court pour se connecter confortablement à l'ordinateur ou la TV.</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B014I8SSD0" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
 
 <img src="images/power-supply.png" height="150" width="125" >
* Une alimentation micro USB
 * Nous vous conseillons <a rel="nofollow" href="https://www.amazon.fr/gp/product/B01M58O9M9/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01M58O9M9&linkCode=as2&tag=curioschron01-21">cette alimentation Aukru à 13€ </a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01M58O9M9" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> car elle est munie d'un interrupteur. C'est très pratique car nous allons faire des montages et donc nous allons devoir éteindre et allumer fréquemment le Raspberry Pi. Sans ce bouton, on se retrouve à devoir tirer sur la fiche tout en tenant du bout des doigts la carte pour ne pas mettre les mains sur les composants, c'est moins pratique.
 * Si vous voulez aller au plus économique, <a rel="nofollow" href="https://www.amazon.fr/gp/product/B01566WOAG/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01566WOAG&linkCode=as2&tag=curioschron01-21">cette autre alimentation Aukru coûte 11€, est très bien notée</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01566WOAG" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> mais n'a pas d'interrupteur. 


<img src="images/noobs-card.png" height="150" width="125" >
* Une carte SD
 * le minimum est de 8 Go mais nous vous conseillons pour quelques euros de plus de prendre <a rel="nofollow" href="https://www.amazon.fr/gp/product/B013UDL5V6/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B013UDL5V6&linkCode=as2&tag=curioschron01-21">cette carte Mémoire microSDHC SanDisk Ultra 16GB </a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B013UDL5V6" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> très rapide et à moins de 9 €.


### Les périphériques indispensables :

* Un écran de télévision ou un moniteur, dans tous les cas avec une entrée HDMI.
![](images/monitor.png =150x125)
Le plus simple est certainement de prendre votre TV, mais si vous n'avez rien, vous pouvez acheter des écrans de Raspberry pour une somme modique :
 * Nous ne l'avons pas testé, mais <a rel="nofollow" href="https://www.amazon.fr/gp/product/B01HPV7D38/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01HPV7D38&linkCode=as2&tag=curioschron01-21">Cet écran LDC 5 pouces à 35 €</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01HPV7D38" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> est très bien noté par les clients.
 * Ou vous pouvez opter pour <a rel="nofollow" href="https://www.amazon.fr/gp/product/B014WKCFR4/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B014WKCFR4&linkCode=as2&tag=curioschron01-21"> l'écran tactile 7 pouces Raspberry Pi à 84€</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B014WKCFR4" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />.

<img src="images/keyboard.png" height="150" width="125" ><img src="images/mouse.png" height="150" width="125" >
* Un clavier et une souris.
 * Si vous ne voulez pas vous en servir tous les jours, vous pouvez opter pour cet ensemble premier prix clavier souris Bluestork à environ 9€. <a rel="nofollow" href="https://www.amazon.fr/gp/product/B005MMIG02/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B005MMIG02&linkCode=as2&tag=curioschron01-21">Bluestork BS-PACK-FIRST-II/F Clavier multimédia AZERTY + Souris filaire - Noir</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B005MMIG02" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
 * Si vous ne voulez pas vous encombrer d'un grand clavier, <a rel="nofollow" href="https://www.amazon.fr/gp/product/B01B17SSYU/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01B17SSYU&linkCode=as2&tag=curioschron01-21">ce mini clavier avec trackpad intégré Geartist</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01B17SSYU" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> fonctionne sans fil et s'installe hyper quelques secondes. Pour 16€, vous avez un clavier qui rentre dans tiroir, et qui peut vous servir pour votre Google TV, Xbox, PS3, etc. Attention en revanche, le clavier est en QWERTY et le trackpad est moins pratique qu'une souris à main.
 * Si vous voulez investir dans un clavier et une souris de bonne qualité avec un budget restant raisonnable, <a rel="nofollow" href="https://www.amazon.fr/gp/product/B00BF5QDZU/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B00BF5QDZU&linkCode=as2&tag=curioschron01-21">cet ensemble clavier + Souris - Logitech Combo MK270 sans fil</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B00BF5QDZU" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> est une valeur sûre et une des meilleurs ventes de la catégorie, pour moins de 25€.


### Les éléments facultatifs mais pratiques
* Un volmètre pour mesurer les courants et les tensions pour mieux comprendre vos montages et résoudre les problèmes.
 * Nous avons testé <a rel="nofollow" href="https://www.amazon.fr/gp/product/B011NP2DGY/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B011NP2DGY&linkCode=as2&tag=curioschron01-21">ce premier prix à moins de 10€. Il ne durera pas toute une vie mais il fait le boulot correctement</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B011NP2DGY" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />.
 * Sinon, <a rel="nofollow" href="https://www.amazon.fr/gp/product/B00S7J7L7Q/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B00S7J7L7Q&linkCode=as2&tag=curioschron01-21">ce multimètre à 19€</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B00S7J7L7Q" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" /> semble être une valeur sûre et plus robuste.
 
### Le système d'exploitation
Pour commencer, il vous faudra également un système d'exploitation (OS). NOOBS est un installateur d'OS hyper facile à utiliser pour Raspberry Pi. Raspbian est l'OS le plus répandu dans le monde Raspberry Pi.


## Solution n°1 : Acheter un carte SD avec NOOBS préinstallé

Le moyen le plus simple est le plus rapide est d'acheter une carte SD où le software est déjà installé. Si vous avez déjà acheté une de ces carte, alors vous pouvez sauter jusqu'à la section 'Brancher for Raspberry Pi' un peu plus bas.

<a rel="nofollow" href="https://www.amazon.fr/gp/product/B01CCM6B1K/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01CCM6B1K&linkCode=as2&tag=curioschron01-21">Carte SD officielle de 8 Go</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01CCM6B1K" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

<a rel="nofollow" href="https://www.amazon.fr/gp/product/B01CCM6B1K/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B01CCM6B1K&linkCode=as2&tag=curioschron01-21"><img border="0" src="http://ws-eu.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B01CCM6B1K&Format=_SL110_&ID=AsinImage&MarketPlace=FR&ServiceVersion=20070822&WS=1&tag=curioschron01-21" ></a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B01CCM6B1K" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />


## Solution n°2 : Charger vous-même NOOBS ou Raspbian sur une carte SD vierge.

L'autre solution est de télécharger NOOBS ou Raspian gratuitement et de l'installer sur votre carte. Prenez une carte d'au minimum 8 Go. Si vous n'en avez pas, pour moins de 10 euros, nous vous conseillons cette <a rel="nofollow" href="https://www.amazon.fr/gp/product/B013UDL5V6/ref=as_li_tl?ie=UTF8&camp=1642&creative=6746&creativeASIN=B013UDL5V6&linkCode=as2&tag=curioschron01-21">carte microSDHC SanDisk Ultra 16GB classe 10, avec une vitesse de lecture élevée.</a><img src="http://ir-fr.amazon-adsystem.com/e/ir?t=curioschron01-21&l=as2&o=8&a=B013UDL5V6" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

## Formatez votre carte SD
Le mieux est de formater votre carte SD sur votre PC ou portable avant d'y copier les fichiers NOOBS ou l'image Raspbian.
Pour ce faire:

1. Visitez le site [SD Association](http://www.sdcard.org/) et téléchargez [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) pour Windows ou Mac.
1. Suivez les instructions pour installer l'application.
1. Inserez votre carte SD dans votre lecteur de carte ou prenez note de la lettre du lecteur associé, par exemple: `F:/`.
1. Dans SD Formatter, selectionnez la lettre du lecteur de votre carte SD card et formattez la.

  ![](images/SD-Formatter.jpg)

### Téléchargez les fichiers NOOBS et glissez-déposez dans la carte

1. Toujours sur votre ordinateur, visitez [le site officiel Raspberry](http://www.raspberrypi.org/downloads/).

  ![](images/siteHome.png)

1. Cliquez sur **NOOBS**.

  ![](images/noobs1.png)

1. Cliquez sur le bouton **Download ZIP** sous ‘NOOBS (offline and network install)’, et sélectionnez le dossier de destination.
1. Extrayez les fichiers du zip.
1. Once your SD card has been formatted, drag all the files in the extracted NOOBS folder and drop them onto the SD card drive.
1. The necessary files will then be transferred to your SD card.
1. When this process has finished, safely remove the SD card and insert it into your Raspberry Pi.

<iframe src="https://player.vimeo.com/video/90518800" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p></p>

### Télécharger une image de Raspbian directement

La solution alternative à NOOBS et de télécharger et installer directement une image fonctionnelle sur la carte SD. C'est plus rapide et aussi très pratique lorsque vous devez préparez plusieurs cartes pour un atelier ou un cours.

1. En utilisant un ordinateur muni d'un lecteur de cartes SD, visitez le site officiel Raspberry Pi [page téléchargements](http://www.raspberrypi.org/downloads/).
1. Cliquez sur **Raspbian**.

  ![](images/noobs1.png)

1. Cliquez sur le bouton **Download ZIP** situé sous ‘Raspbian Jessie (full desktop image)’, et sélectionnez un dossier de téléchargement.
1. Décompressez les fichiers du zip.

  ![](images/noobs2.png)

1. Visitez [etcher.io](http://www.etcher.io/), et téléchargez et installez Etcher SD card image utility.
1. Démarrez Etcher et sélecitonnez l'image Raspbian que vous avez décompressée sur votre ordinateur.
1. Selectionnez le lecteur de la carte SD. Remarquez que l'application a peut être sélectionné par défaut le bon lecteur.
1. Enfin, cliquez sur **Burn** pour transferer Raspbian sur la carte SD. Lorsque c'est terminé l'application ejecte automatiquement la carte, qui peut être retirée de l'ordinateur en sécurité.

  ![](images/etcher.gif)

## Brancher votre Raspberry Pi

**Attention**, lorsque vous manipulez votre Raspberry Pi, évitez de toucher les broches ou les composants avec les doigts. Vous pourriez décharger de l'électricité statique qui endommagerait votre carte. Le mieux est de la tenir par les rebords et de ne pas y toucher lorsqu'elle est sous tension.

1. Introduisez votre carte micro SD dans le lecteur du Raspberry Pi, situé en dessous de la carte. Vous ne pouvez pas vous tromper de sens, car il y a un détrompeur.
1. Ensuite, branchez votre clavier et votre souris (ou leur émetteur sans fil) dans les ports USB. 
1. Assurez vous que votre moniteur ou votre TV est allumé(e), et que vous avez bien sélectionné la bonne sortie (HDMI 1, DVI, etc.).
1. Connectez votre câble HDMI du Raspberry à votre écran.
1. Si vous souhaitez connecte votre Raspberry Pi à internet par le réseau filaire, branchez un câble Ethernet.
1. Lorsque tout est prêt, branchez votre cordon d'alimentation micro USB.

  ![Plugging in](images/plug-in.gif)


1. Si c'est votre premier démarrage, vous devez installer le système d'exploitation et le configurer.

<iframe src="https://player.vimeo.com/video/91631396" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

## Premier démarrage

1. Une fois l'alimentation branchée, le Raspberry Pi va démarrer. Si vous utilisez NOOBS, une fenêtre va vous inviter à choisir un système d'exploitation à installer. Nous vous recommandons Raspbian. Cochez la case à cté de Raspbian et cliquez sur **Install**.

  ![](images/noobs.png)

1. Raspbian prendra ensuite quelques minutes pour s'installer.
1. Lorsque l'installation est terminée, le menu de configuration Raspberry Pi (`raspi-config`) va se charger. Suivez les instructions.
1. Si vous avez opté pour la solution d'une image Raspbian alors le démarrage sera automatique et vous arriverez directement sur le bureau de Raspbian.

## Que faire ensuite ?

Votre Raspberry Pi fonctionne! Vous pouvez maintenant passer au [tutorial Internet des Objets](https://github.com/saucesamourai/Raspberry-Pi-tutoriel-debutant-Internet-des-objets-Build-Play/blob/master/README.md), votre premier projet!
