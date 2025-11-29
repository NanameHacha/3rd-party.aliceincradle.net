## How to Create Language Pack ##

> [!IMPORTANT]
> If you are going to translate the game to a currently unsupported language, We urge you to use the original Japanese as the base and not the English version.
> 
> Our English localization uses a lot of slang and colloquial metaphors and text is often moved around to help the flow of dialogue and/or make things more clear since the two languages are so vastly different.
> 
> You run the same risks as "generation loss" if you translate from the English version.

### 1.Download Alice in Cradle Game ###

Download the game and open folder `AliceInCradle_Data\StreamingAssets\localization`

### 2.Create a copy of any exist language pack ###

A Language Pack consists of a family definition file and a directory containing translated texts. Taking English as an example, if you intend to translate your own Language Pack based on English, you need to duplicate `___family_en.txt` and the `en` folder, then rename `en` to your own language, such as `___family_aic.txt` and the `aic` folder.

### 3.Translate all text and change the family code to yours ###

After completing the translation, do not forget to replace the family code in each text file and inside the files with your own. For example, change `en_xxxx.txt` to `aic_xxxx.txt`, and replace `%FAMILY en` with `%FAMILY aic` inside the files.

### 4.Replace the language pack icon ###

Modifying icon.png helps players who are about to use your language pack to quickly locate the options.
