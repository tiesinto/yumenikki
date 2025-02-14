<p align="center">
  <h><i><b>IN PROGRESS</b></i></h>
</p>

<p align="center">
  <img style="display:block; margin:auto; width:75%; border:1px solid skyblue;" src="https://raw.githubusercontent.com/tiesinto/yumenikki/refs/heads/main/yume.png" alt="Yume Nikki">
</p>

### To simply run the game, download <b><ins>[THIS](https://github.com/tiesinto/yumenikki/releases/download/custom_made/yumenikki_for_dummies.zip)</ins></b> and run START.exe
### [Instruktionen auf Deutsch](./.github/README_de.md)

<b>_Yume Nikki_</b> (ゆめにっき) is a 2004 "walking simulator" made in RPG Maker 2003 and created by [Kikiyama](https://www3.nns.ne.jp/~tk-mto/). You play as a <i><a href="https://en.wikipedia.org/wiki/Hikikomori">hikikomori</a></i> or reclusive girl named Madotsuki as you explore her dreams and collect effects acquired by various entities and objects throughout the environment. Development for the game ended in 2007, and in 2012 ownership was handed over to Playism. 

## Table of Contents

- [Download Links](#download-links)
- [Running](#running)
- [Controls](#controls)
- [Online Versions](#online-versions)
- [Additional Resources](#additional-resources)

## Download Links
- Uboachan Translation[^1] (0.10, with yumesyuusei patch): https://uboachan.net/yumenikki_portable.zip
- Steam[^2] (0.10a, there are no anti-piracy measures taken to protect the game, so if you don't have Steam you can just have a friend share the files with you):[^3] https://store.steampowered.com/app/650700/Yume_Nikki/
- Original 0.10 (JP): http://www.vector.co.jp/soft/win95/game/se332192.html (<a href="https://assets.ymbr.site/misc/yumenikki0.10.lzh">Mirror</a>)
- yumesyuusei (Official Kikiyama patch intended to be applied to the original Japanese version of 0.10.[^4] Identical to 0.10a versions): https://www3.nns.ne.jp/~tk-mto/yumesyuusei.lzh (UPDATE: The download has now been removed for some reason, I have re-uploaded the exact file here: https://assets.ymbr.site/misc/yumesyuusei.lzh)

- Playism (Playism's JP and ENG versions of 0.10a): https://archive.org/details/yume-nikki-010a
- Historic Versions: https://gatobot.neocities.org/lainvestigacionyn/links.html

## Running
### All the following can be avoided by using [EasyRPG](https://easyrpg.org/player/downloads/)
- Additional RTP is often needed to run most of these games. RTP are game assets that are downloaded separate so multiple games can use the files to cut down on storage. Both English and Japanese RPGM2003 RTP should be downloaded if you plan on playing these games.
English RTP: https://www.rpgmakerweb.com/run-time-package (<a href="https://dl.komodo.jp/rpgmakerweb/run-time-packages/rpg2003_rtp_installer.zip">Direct</a>)
Japanese RTP: https://tkool.jp/products/rtp.html (<a href="https://tkool.jp/products/rtp/2003rtp.zip">Direct</a>)
<a href="https://assets.ymbr.site/misc/rtp.7z">Yumebooru Archive</a>
- Additional RM2k fonts may be needed for text to render properly on Japanese versions. I'm not exactly sure where you could download these before but there is an archive currently stored here:
https://assets.ymbr.site/misc/mubyni.zip

- Additionally, system locale (and date and time, but less often) may need to be changed to Japanese to get Japanese and English-translated versions of _Yume Nikki_ to render text and load properly. The Japanese language should be downloaded through settings to avoid complications and problems being afflicted to your computer. If you would like to avoid changing system locale, Locale Emulator is often used:
https://xupefei.github.io/Locale-Emulator/

<b>N.B: Although these steps were outlined with the intent of being applied to _Yume Nikki_, you really need to do this for every RPG Maker 2000 and 2003 game.</b>

The standard experience for most people is either the Steam version or the Uboachan translation played with EasyRPG. The English versions translated by Uboachan, Playism, and Steam are all essentially 0.10a[^1][^2] but translated slightly differently. The Uboachan translation is often considered the most accurate, while the Steam and Playism versions take some liberties with the text.

## Controls
- Arrow keys/hjkl/Numpad arrow keys - Move
- Z/Enter/Space - Select/Action
- X/0 - Back/Menu
- 1 - Primary effect action
- 3 - Secondary effect action
- 5 - Drop effect in nexus
- 9 - Wake up

## Online Versions
- Yumebooru: <s>https://yumenikki.online/nikki/</s> [Discontinued; now see <a href="https://archive.yumeboo.ru/play/">https://archive.yumeboo.ru/play/</a>]
- YNO: https://ynoproject.net/yume/

Additional translations of the game can be applied but only by the use of EasyRPG. Patches applied to the native RPG_RT can be found across various sources.
YNO Translations: https://github.com/ynoproject/ynotranslations/tree/master/yume

## Additional Resources
- 16:9 Mod (by poyouli): https://poyouli.itch.io/yumenikki169
- Archive.org "collection" of RTP, ENG and JP—unofficial: https://archive.org/details/RPG_Maker_RTP_Collection

[^1]: There currently exists a bug in all instances of this translation downloaded before July of 2023 where all the FC Worlds can not be accessed with all 25 effects, due to a misnamed file. To fix this, rename <code>FCM2ALL.xyz</code> in the folder <code>Picture</code> to <code>FCM２ALL.xyz</code> (with the superscript <code>２</code> character) or redownload the game. To this date, the bug has only been fixed in the portable version, the installer version still possesses the bug.

[^2]: Although the Steam version should just be 0.10a but with its own translation, there are reportedly a number of graphical and technical issues with this version (that are exclusive to the Steam version, not 0.10a) including but not limited to:<ul><li>Towel effect not slowing you down;</li><li>The screen does not fade to black when you sleep in the spaceship;</li><li>In the credits, one of the blocks of text appears abruptly, rather than slowly fading in like they're supposed to;</li><li>Backslash instead of Yen symbol in the menu;</li><li>Incorrect Playism translations of effects still appear when effects are dropped and in FC World menu;</li><li>One of the candles becomes what appears to be light when extinguished;</li><li>If the player equips the Stoplight effect, switches it to its red light, and interacts with the desk Toriningen to make their menu theme red, the popup text for changing the menu theme will appear as garbled, untranslated text.</li></ul>
<br><br><br>The Uboachan translation also lacks a translation for the effect-pickup text specifically in the large variant of Guillotine World.

[^3]: https://assets.ymbr.site/misc/yume_nikki_0.10a_steam.7z

[^4]: Copy and paste the map files into the folder where the map files are (the main one) of the copy of 0.10 you intend to patch.
