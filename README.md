# vscode_amiga_asm_ks13_cfg
A collection of files to configure VSCode Amiga Assembly to match KS 1.3 style.

VScode extensions needed:  https://github.com/prb28/vscode-amiga-assembly  -  https://github.com/be5invis/vscode-custom-css

How to use files:

M68k-Assembly.tmLanguage.json > replaces https://github.com/prb28/vscode-amiga-assembly/blob/master/syntaxes/M68k-Assembly.tmLanguage.json - This file has modification to separate Data and Address registers from variables, enabling them to be styled separately. Also to separate instructions from opcodes sizes, enabling ".B", ".W", ".L" and ".S" extensions to be styled with different colors from instructions. 

settings.json > VScode config, adjust as needed. Here styles are set so that some new classes area added to the markup, allowing custom css from next file to be applied.

custom.css > copy anywhere and adjust previous file accordingly.

TOPAZPLUS_A1200_V1.0.TTF install it, this comes from https://github.com/rewtnull/amigafonts

PREVIEWS:

![alt text](https://github.com/KONEY/vscode_amiga_asm_ks13_cfg/blob/main/AMIGA_VSCODE_ASM_PREVIEW_1.png?raw=true)
![alt text](https://github.com/KONEY/vscode_amiga_asm_ks13_cfg/blob/main/AMIGA_VSCODE_ASM_PREVIEW_2.png?raw=true)
![alt text](https://github.com/KONEY/vscode_amiga_asm_ks13_cfg/blob/main/AMIGA_VSCODE_ASM_PREVIEW_3.png?raw=true)
