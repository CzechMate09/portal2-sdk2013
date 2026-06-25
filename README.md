# portal2-sdk2013
Port of Portal 2 assets to SDK 2013

:warning: This is still work in progress! :warning:
- All models that cause crashes have been recompiled, some had to be split into multiple models due to bone limit (max in SDK2013 is 128 bones)
- All materials have been converted from version 7.5 to 7.4
- Some materials had to have their $detailblendmode shader set to 0 to stop issues that occur if used with other shaders

Not all materials can be converted due to some shaders/proxies that do not exist in SDK2013.

Not all particles can be converted due to some funtions that do not exist in SDK2013.

Some models might still crash the game due to their animations, but there is too many animations for me to check them all, so write an issue if you find any. Sometimes the crash may only occur after repacking/compressing the map.

Special thanks to Ficool2 for StudioMDL++ https://ficool2.github.io/HammerPlusPlus-Website/tools.html
