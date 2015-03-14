# Vecor based dark skin for Mediawiki #

  * Customized version of Skin:Vector
  * Many background images are removed
  * Personal navigation links are moved to a drop down menu towards the right top corner
  * Border less design
  * The actual development started due to a user request in [MWUsers forum](http://www.mwusers.com/forums/showthread.php?18346-Need-black-Vector-based-skin-for-1.18&p=64248&viewfull=1#post64248)
  * Created by [Abhi\_M\_Balakrishnan](http://www.mediawiki.org/wiki/User:Abhi_M_Balakrishnan) and [Arcane](http://www.mediawiki.org/wiki/User:Arcane21)


![http://upload.wikimedia.org/wikipedia/mediawiki/f/f1/Darkvector_screenshot.jpg](http://upload.wikimedia.org/wikipedia/mediawiki/f/f1/Darkvector_screenshot.jpg)

## Installation instructions ##
```
* Download the zip file

* Extract it to Mediawiki skins directory

* Add the following line towards the end of LocalSettings.php file ( This step is not required for latest version 0.2)
require_once("$IP/skins/DarkVector.php");

* Find $wgDefaultSkin in LocalSettings.php file and make DarkVector as the default skin
$wgDefaultSkin = "darkvector";

```