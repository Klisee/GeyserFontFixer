<p align="center">
   <img src="https://github.com/user-attachments/assets/595953a0-bdd4-47f5-bc1f-a50d5c399f66" width="500"/>

A solution to the font problems on servers with GeyserMC, modifies the Minecraft Bedrock font to fix the text problems.
<p align="center">
    <img alt="GNU GPL 3.0 LICENSE" src="https://img.shields.io/badge/gnu-gpl?style=for-the-badge&logo=gnu&logoColor=000000&label=License&labelColor=CECECE&color=515050">
	<br>
    <a href="https://github.com/Klisee/GeyserFontFixer/blob/main/README.md">English</a>
     | 
    <a href="https://github.com/Klisee/GeyserFontFixer/blob/main/README_ES.md">Español</a>

This project depends on the following resources:

- Monocraft / Part of the font is taken here: https://github.com/IdreesInc/Monocraft/
- Glyph Tools / Thanks to this tool, it was possible to add some symbols that did not exist in Bedrock: https://github.com/NhanAZ/glyph

Special thanks to:

- coztellation: To her for making much of this project possible, fixing some existing problems and giving me permission to use some of her work.

# How it works?

Simply edit the Bedrock font, changing several glphys to fix the font when using special characters and add some missing characters, allows you to greatly enhance the experience for your Bedrock Edition players
<p align="center">
   <img src="https://github.com/user-attachments/assets/84fb42a2-e349-49cf-9277-307c726b5f4e" width="800"/>

# Current limitations

Unfortunately it is not possible to fix everything, and there are some mistakes you should be aware of before using this fix, here is a list of all the current limitations that you should consider

## - Broken Scoreboard

If you have a very long text in the Scoreboard it will be partially broken, and the text will appear incomplete, this is a Bedrock bug and there is no current fix
<p align="center">
   <img src="https://github.com/user-attachments/assets/e741f0fa-20c7-400e-96e7-c6f04a34c283" width="400"/>

## - Unicodes that are impossible to add

The files used for the font, which are the glphys have a format like this "glyph_1DXX" and apart from being an image with different boxes with different symbols, it only supports those 4 characters, other unicodes have a totally different format

Unlike Java Edition it is impossible to edit unicodes separately and depends on UTF-16 (hex) and this symbol "🗡️" would have a format similar to this "0xD83D 0xDDE1" making it impossible to add to Bedrock

<p align="center">
   <img src="https://github.com/user-attachments/assets/774de86e-6fef-4c3e-9e17-f1ae4a72ec01" width="400"/>


