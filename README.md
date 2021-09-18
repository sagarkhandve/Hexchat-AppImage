# Hexchat - AppImage

![video](https://user-images.githubusercontent.com/90393971/133887800-86401b28-a889-4bc2-8ef7-3e8e25f02888.png)

1. Clone this repository and `cd` into it.
   ```shell
   git clone https://github.com/AppImage/sagarkhandve/HexChat.git
   cd Hexchat/
   chmod +x HexChat.AppImage
   ```
2. Run

   ```shell
   ./HexChat.AppImage
   ```

A configuration for [pkg2appimage](https://github.com/AppImage/pkg2appimage) to build Hexchat in AppImage form.

How to use it?

1. Clone this repository and `cd` into it.
    ```shell
    git clone https://github.com/sagarkhandve/Hexchat.git
    cd Hexchat/
    ```
2. Download pkg2appimage tool and make it executable.
   ```shell
   wget https://github.com/AppImage/pkg2appimage/raw/master/pkg2appimage
   chmod +x pkg2appimage
   ```
3. Build it:

   ```shell
   ./pkg2appimage Hexchat.yml
   ```

4. After a short break you should get an executable inside `out/` directory.

