<p align="center">
   <img src="https://github.com/user-attachments/assets/595953a0-bdd4-47f5-bc1f-a50d5c399f66" width="500"/>

Una solución a los problemas de fuentes en servidores con GeyserMC, modifica la fuente de Bedrock en Minecraft para arreglar los problemas de texto.
<p align="center">
    <img alt="GNU GPL 3.0 LICENSE" src="https://img.shields.io/badge/gnu-gpl?style=for-the-badge&logo=gnu&logoColor=000000&label=License&labelColor=CECECE&color=515050">
	<br>
    <a href="https://github.com/Klisee/GeyserFontFixer/blob/main/README.md">English</a>
     | 
    <a href="https://github.com/Klisee/GeyserFontFixer/blob/main/README_ES.md">Español</a>

Este proyecto depende de los siguientes recursos:

- Monocraft / Parte de la fuente está tomada aquí: https://github.com/IdreesInc/Monocraft/
- Glyph Tools / Gracias a esta herramienta, ha sido posible añadir algunos símbolos que no existían en Bedrock: https://github.com/NhanAZ/glyph

Agradecimientos especiales a:

- coztellation: A ella por hacer posible gran parte de este proyecto, arreglar algunos problemas existentes y darme permiso para utilizar parte de su trabajo

# ¿Como funciona?

 Simplemente cambia la fuente Bedrock, cambiando varios glphys para arreglar la fuente cuando se utilizan caracteres especiales y añadir algunos caracteres que faltan, le permite mejorar en gran medida la experiencia para sus jugadores Bedrock Edition
<p align="center">
   <img src="https://github.com/user-attachments/assets/c0422616-3369-4835-912f-2032d12c9c2d" width="800"/>

# Limitaciones actuales

Unfortunately it is not possible to fix everything, and there are some mistakes you should be aware of before using this fix, here is a list of all the current limitations that you should consider

## - Scoreboard rota

If you have a very long text in the Scoreboard it will be partially broken, and the text will appear incomplete, this is a Bedrock bug and there is no current fix
<p align="center">
   <img src="https://github.com/user-attachments/assets/e8f04287-282e-440a-9af7-41016c940b00" width="400"/>

## - Unicodes imposibles de añadir

Los archivos usados para la fuente, que son los glphys tienen un formato como este "glyph_1DXX" y aparte de que es una imagen con diferentes casillas y con diferentes simbolos, solo soporta esos 4 caracteres, otros unicodes tienen otro formato totalmente diferente

A diferencia de Java Edition es imposible editar unicodes por separado y depende de UTF-16 (hex) y que este simbolo "" tendria un formato similar a este "0xD83D 0xDDE1" haciendolo imposible de agregar a Bedrock

<p align="center">
   <img src="https://github.com/user-attachments/assets/774de86e-6fef-4c3e-9e17-f1ae4a72ec01" width="400"/>

## - Bug en la calidad del texto

GeyserFontFixer contiene dos version, la version normal y la version Fidelity, la version normal tiene glyphs de 128x128 y crea una version mas reducida de otros iconos lo cual puede arruinar la experiencia para algunos usuarios mas exigentes en el maximo Crossplay

Y GeyserFontFixer Fidelity tiene sus glyphs de 256x256 pero con la desventaja de pixelear la letra en resoluciones altas, para otros usuarios mas exigentes esto sera algo molesto, asi que toma eso en consideracion
<p align="center">
   <img src="https://github.com/user-attachments/assets/0567381f-46d9-43a9-82bb-b2d1a0415cf0" width="400"/>


