# 4enRaya
_Juego simple sobre consola del cl�sico 4 en raya para jugar contra el ordenador o 2 jugadores_

El algoritmo utilizado para el juego del ordenador est� basado en el algoritmo del minimax con poda alfa beta. El programa est� desarrollado �ntegramente en C. Para compilarlo, basta con ejecutar en la carpeta del programa:

```
gcc -o 4r.exe *.c
```

**_El juego ha sido dise�ado en Windows y para Windows_** _Si se desea implementar en Linux, antes se deben cambiar tres cosas en el c�digo:_
1. Cambiar los "system("cls")" por "system("clear")"
2. Cambiar las funciones de la librer�a "conio.h" -getch(),gectche()- que no es tenen de
	forma predeterminada a Linux
3. Cambiar las funciones Beep() -que hacen un ruidito cuando se presiona una tecla incorrecta-
	de la librer�a "Windows.h".
