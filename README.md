WallpaperChooserApp
===================

Advanced Wallpaper Chooser App with options to Set, Save and Share Wallpapers.

Download, extract and Import to Eclipse.
Open WallpaperChooserTemplate>res>values>wallpapers.xml:

<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string-array name="wallpapers" translatable="false">
        <item>wallpaper1</item>
        <item>wallpaper2</item>
        <item>wallpaper3</item>
        <item>wallpaper4</item>
        <item>wallpaper5</item>
        <item>wallpaper6</item>
        <item>wallpaper7</item>
        <item>wallpaper8</item>
        <item>wallpaper9</item>
        <item>wallpaper10</item>
        <item>wallpaper11</item>
        <item>wallpaper12</item>
        <item>wallpaper13</item>
    </string-array>
</resources>

Added / Remove <item>...</item> to add wallpaper to the list.
You need to place walpaper image of same name to desired drawable-dpi folder.
You also need to place a smaller sized image for each wallpaper with "_small" in its name such as "wallpaper1_small.png" for "wallpaper1.png"
