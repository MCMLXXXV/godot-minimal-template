# Godot Minimal Project Template [![Made for Godot 4.0+][badge]][godot]

An absolutely minimal Godot project template for 2D games.


## Project Settings

-   Default viewport dimensions at 1152x648 (16:9 aspect ratio)
-   Window stretch mode set to `canvas_items` and aspect set to `keep`
-   Sane defaults for pixel-art rendering:
    -   Textures imported using the `2D` preset by default
    -   Texture filter configured to `Nearest` on Project Settings
    -   2D pixel snapping options enabled on Project Settings
-   No application icon – bring yours if you need one!
-   Includes an empty main scene with an attached empty script.


## Quick setup guide

1.  [Download][download] this repository, unzip the file containing the
    template project folder and rename it to your liking.

2.  Use Godot's Project Manager to import the template project.

3.  Select the newly imported project, typing "minimal" in the filter field if
    needed, and click "Rename" to change its title.

4.  Open the game project to start editing it.

>   **💡 Hint**: Keep your game projects organized and let Godot's Project
    Manager discover them for you, automatically. With the Godot Engine editor
    open, find the "Editor Settings" under the "Editor" menu, scroll to
    "Filesystem > Directories" on the left-side panel and pick the folders of
    your choice under "Autoscan Project Path" and "Default Project Path".


## Motivation

As I am frequently starting projects using those same settings, be it short
lived games or just my usual throw away ideas, I made this little template to
help me get to the interesting stuff faster.


## License

[CC0-1.0](LICENSE.md).


[godot]: https://godotengine.org/
[badge]: https://flat.badgen.net/badge/made%20for/Godot%204.0%2b/478cbf
[download]: https://github.com/MCMLXXXV/godot-minimal-template/archive/refs/heads/main.zip
