## Guide to Install MK11 on Linux

1. Install the Latest version of Proton-GE-Custom: https://github.com/GloriousEggroll/proton-ge-custom/releases/latest
2. Run the game with this command just for the first time to see Proton logs ( it may take a while ) and then exit the game

```sh
steam steam://run/976310
```

3. Use this fix for desync issues in online mod : https://github.com/ValveSoftware/Proton/issues/2594#issuecomment-833121204
4. Install mf-install with following command

```sh
git clone git@github.com:z0z0z/mf-install.git
WINEPREFIX="/home/<username>/.steam/steam/steamapps/compatdata/976310/pfx" PROTON="/home/<username>/.steam/steam/compatibilitytools.d/Proton-VERSION" ./mf-install.sh -proton
```

7. Run the game with steam launcher

Enjoy !
