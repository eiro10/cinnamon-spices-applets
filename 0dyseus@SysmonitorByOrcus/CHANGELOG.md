## Change Log

##### 1.09
- Fixed system freeze on applet removal on Cinnamon 3.2.x.
- Cleaned code of unused constants and functions.

##### 1.08
- Re-added compatibility for Cinnamon 2.8.8 (Linux Mint 17.3). Compatibility for this version of Cinnamon was accidentally lost when the dependency on NetworkManager was removed.

##### 1.07
- Removed dependency on NetworkManager. Thanks to [buzz](https://github.com/buzz).

##### 1.06
- Added support for localizations. If someone wants to contribute with translations, inside the Help section of this applet (found in the applet context menu or the Help.md file inside this applet folder) you will find some pointers on how to do it.

##### 1.05
- Re-writed to use Cinnamon's native settings system instead of an external library. This allowed me to remove **gjs** as a dependency for this applet.
- Added an option to use a custom command on applet click.
- Added an option to set a custom width for each graph individually.
- Added an option to align this applet tooltip text to the left. ¬¬

##### 1.04
- Initial release of the fork.
