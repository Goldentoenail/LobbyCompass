# LobbyCompass

***Please use the other version as this one has an error for the Compass material being a static material***

Vastly rewritten code for MC 1.9.x compatiblity. With ZERO method deprecation at the time of this commit.

This should be compatible with MC versions from 1.8.0 onwards.

Caveats:

The alias /LC is also used by LegendChat. This may only affect ops.

 - solution - do not use this alias for LobbyCompass when another plugin requires the alias.

WordEdit recognises any compass as it's navigation tool. This will only affect ops unless a player has been given the navigation tool permission.

 - solution - In the WordEdit configuration disable the Navigation tool. Or, use an alternative item material for 'compass' in either LobbyCompass or WorldEdit.
