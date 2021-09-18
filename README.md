# Hexchat - AppImage

![hexchat](https://user-images.githubusercontent.com/90393971/133889996-a0e1ff70-f14e-4845-a47a-a4936c25cc69.png)

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

