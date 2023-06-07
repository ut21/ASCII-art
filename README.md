## Technology Used:
Numpy, Matplotlib, OpenCV

# ASCII-art
Creates ASCII art out of images
The program corresponds pixels to ascii characters based on their brightness values. Finally every nth line is
outputted on the terminal to resize it to fit the screen

## For example:

![image](https://github.com/ut21/ASCII-art/assets/114133139/020544e1-c8bb-4a44-bb0f-55b77eb5955f)


becomes this:
```
________________________________________________________________________11_1111111111___11____111111
________________________________________________________________________11_111111111____11____111111
________________________________________________________________________1_______1111____1__________1
_________________________________________________________________________________11________________1
_______________________________________________________111_________________________________________1
___________________________________________________________________________________________________1
_________________________________________________________1__________________________________________
_______________________________________________________________________________________________11___
______________________________________________________iiii_____________________________________11___
____________________________________________________ii$iiii__1_________________________________1____
_________________________________________________ii$i$___1__________________________________________
________________________________________________$i$i$________1______________________________________
_______________________________________________i$ii$iiiiii__________________________________________
_______________________________________________$ii$i$iiiiiii______1_________________________________
______________________________________________iiii$$iii$iiiii_______________________________________
___________________iii______________iii______i$iii$$$iiiiiiiii___1__________________________________
___________________i$$iii___________iii_____iiiii$i$$i$ii$i$$iii____________________________________
______________________i$$ii_________ii$_____iiiiiiiiii$$i$$$$ii$i___________________________________
________________________i$$ii_______i$$____$$$ii$$iii$$$ii$$iiiii___1______________________________1
__________________________i$iii_____i$$___i$$ii$$$iiiii$$iiiiiiiii__________________________________
____________________________i$iii___i$$___ii$i$$$iii$$i$i$iii$i$iiii__1_____________________________
______________________________$$iii_i$$___iii$i$$$$i$$i$$iii$i$$ii$i_1______________________________
_______________________________$$$ii$$i__iii$$$$$$$$$iiii$$$iii$$$ii______1_________________________
________________________________$$$ii$$__ii$$$$$$$$$$$$$$i$$$$$$$$iii_____1________________________1
________________________________i$$$i$$__i$$$$$$$$$$$$$$$$i$i$i$$$$iii___11________________1________
__________________________________$_i$$$ii$$$$$$$$$$$$$$$$$iii$$$$iiiii_1___________________________
____________________________________i$$$i$$$$$$$$$$$$$i$$iiiiiii$$$$$i______________________1_______
____________________________________$$$$$$$$$$$$$$$$$$$$$$i$$i$i$$$$iii_________________1__________1
____________________________________$$$$$$$$$$$$$$$$$$$$$$$i$$$$ii$$$ii___1________________________1
____________________________________ii$$$$$$$$$$$$$$$$$$$$$$$$i$ii$iiiii____________________________
________________________ii$$ii_____iii$$$$$$$$$$$$$$$$$i$$$$$$$$ii$i$iiii_____1____1________________
_____________________iii$$$$$$ii___i$$$$$$$$$$$$$$$i$$$$$$$$$$$$iiiii$iii_____1__111___________1____
___________________iiii$$$$$$$iiiii$$$$$$$$$$$$$$$$$$$$$$$$$ii$ii$$iiiii___1_1______________________
________________iiiiii$$$$$$$iiiii$$$$$$$$$$$$$$$$$$$$$$$$$$i_$$i$i$i$iii__11_________111___________
____________iiiiiiiii$$$$$$$iiiiii$$$$$$$$$$$$$$$$$$$$$$$$ii$$i$$$$$i$ii$i__1_________111___________
____________i$iii$$i$$$$$$$iiiii$$$$$$$$$$$$$$$$$$$$$$$$$$ii$$$$$$$$i$iiii____111111__111__________1
_____________$$iiii$i$$$$$iii$i$$$$$$$$$$$$$$$$$$$$i$$$iii___$$i$$$$iii$ii___1111111___11__________1
______________iii$$i$$$$iii$$$$$$$$$$$$$$$$$$$$$$$$i$$$i$$_i$_iii$$$iiiiii___1111111__111__________1
_______________iii$$$$$$__ii$$$$$$$$$$$$$$$$$$$$$$$$$$$_$$ii$ii$$ii$i$iiii__1_1111111111______1____1
_________________ii$$$$iiii$$$$$$$$$$$$$$$$i$$$$$i$$$$$i$$ii$i_$$i$iiii$i$i__11111111111__1___1___11
___________________iiii_ii$$$$$$$$$$$$$$$$$$$$$$$$$$$$$i$$__i_i$ii$iiiiiiiii___111111111__1___1____1
_________________________$$i$$$$$$$$$$$$$$$$$$$$$$$$$$$$ii____i$$ii$i$i$i$i$___1111111111111111____1
_______________________i$$$i$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$iii$i$i$$$i$iiiii$_1__111111111111111____1
______________________i$$$$$$$$$$$$$$$$$$$$$$$$$$$$i$$$$i$$i$$i$$$i$iiiiiiii____111111111111111__111
______________________$i$$$$$$$$$$$$$$$$$$$$$$$$$$iiii$$i$$i$$_$$$$$iiiii$iii____11111111111111__111
_____________________$$$$$$$$$$$$$$$$$$$$$$$$$i$$iii$i$$i$iiiii$$iiii$i$ii$ii___1111111111_1111__111
____________________$$$$$$$$$$$$$$$$$$$$$$$$$$i$$$_$$$i$$_iiii$i$$$i$iii$iiii___111111111__111111111
___________________i$$$$$$$$$$$$$$$$$$$$$$$$$$$$$i_$$$ii$iiii$$$$$ii$ii$i$i$i__1111111111__111111111
___________________$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ii$$$i$$$$$$$$$$iiii$i$iiiii__111111111_________111
________________i_i$$$$$$$$$$$$$$$$$$$$$$$$$$$$$iiii$ii$$$$$$$$$i$i$ii$$iiiiii_111111111__1______111
_________________i$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ii$$ii_i$$$$$$$$$$ii$$$$i$iii$i_1_11___11______1_____
________________ii$$$$$$$$$$$$$$$$$$$$$$$$i$$$i_$$$ii$$$$$$$$i$$ii$$i$i$iii$ii_1111___111__11111____
_______________ii$$$$$$$$$i$$$$$$$$$$$$$$$i$$$$ii$$i$$i$$i$$$$$$i$i$i$i$ii$iii___11___111__11111____
______________iii$$$$$$$$$i$$$$$$$$$$$$$$$$$$$$$ii$i$$$i_iii$$$$$i$ii$$$i$$iiii__11___1111_11111____
_____________i_i$$i$$$$$$$$$$$$$$$$$$$$$$$$$$i$$$i$$i$i$$$$$$$$ii$iii$$$$$iii$i_111___1111111111____
_____________iii$ii$$$$$$i$$$$$$$$$$$$$$$$$$$ii$$$$$$$$$$$$$$$ii$$$i$$$$$$$ii$i__111111111111111111_
____________iiiiii$$$i$$ii$$$$$$$$$$$$$$$$$$$$$i$$$$$$$$$$$$$i$$$$$i$$$i$iiiiii__111____1111111_____
____________iiiiii$$i$$iii$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$i$$$$$i$i$$$i$iiii__111____1111111____1
____________iiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ii$$$$$ii$i$$$$i$iii1_11_____11___1_____
___________iiiiiiiiii$iiii$$$$$$$$$$$$$$$$$$i$$$$$$i$$$$$$$$$$$$$i$$$$$$$$$$iiii_1_1_____11___1_____
____________iiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$i$$$i$$$$$$$$iii___1_____11___1_____
___________iiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$i$$$$$i$$$i$$$$ii$iii_1_______11___1_____
___________iiiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$i$$$$$$$i$$$$i$i$$i$i$$$ii$$i$i__1111__111___1_____
____________iiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$$ii$$$$$$ii$iii$$$$$$$iiiii$$ii_1_111111111111____1
____________iiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$$ii$ii$$iiii$ii$$$$$$$$i$$$$iiii1_11111111111______
____________iiiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$iii__iii$ii$$$$iii$$$$$$$$$$$iii__11111111111______
______________iiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$i$$$$iiiii$i$ii$$$$i$$$$i$$i$$i$ii1_11111____________
_______________iiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$iiiiiiiiiiiii$$i$$$$$i$i$$iii$i_1_1111___________1
_______________iiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$i$ii$iiii__$$i$ii$i$$$$$i$$$i$ii__11111___________1
________________iiiiiiiiiiiii$$i$$$$$$$$$$$$$$$$$iii$$iiii$i$$i$$$$i$$$$$i$i$$$$i_111111___________1
_________________iiiiiiiiiiiii$i$$$$$$$$$$$$$$$$$$$$iiii$ii_$$i$$$$$$$$i$i$$$$$iii_11_11____________
__________________iiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$iiii$ii$ii$$$$$iii$i$i$$$$$$$i_11_11111_________
___________________iiiiiiiiiiii$i$$$$$$$$$$$$$$$$$$$$$iiii$$ii$ii$$i$$$$$$$$$$i$i$____1___1_________
____________________iiiiiiiiiiii$i$$$$$$$$$$$$$$$$$$$$$iii$$$$$ii$$$$$$$$i$i$$i$$i_1111___1_________
____________________iiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$ii$$$$i$$$i$$$$$i$$$i$$iiiiii_11_1_____________
____________________iiiiiiiiiiiii$i$$$$$$$$$$$$$$$$$i$$$$$$$$i_i$$i$$_$i$i$$i$$$ii__1_1_1___________
_____________________iiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$i$ii$iii$ii$i$$$i_111_1___________
______________________iiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ii$i$$ii_1_1_____________
_______________________iiiiiiiiiii$$$$i$$$$$$$$$$$$$$i$$$$$$$$$$$$$$$$$i$$$$i$i$iii__11_____________
_______________________iiiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$ii$$$$$$$$i$$i$i$$i$$$i$i_1_1_____________
________________________iiiiiiiiiiiiiiiiii$$$$$$$$$$$$$$$$$$$ii$$i$$i$i$$i$ii$ii$i$___1_____________
_________________________iiiiiiiiiiiiii$$ii$$i$$$$$$$$$$$$$$$$$$$$$$$$$$$$$i$$i$$ii_1_1____________1
__________________________iiiiiiiiiiiiiiii$i$i$i$$$$$$$$$i$$$i$$$$$$$$$$$$$$$$$$$$i_11______________
____________________________iiiiiiiiiiiiiiiiiii$$i$$$$i$$$$$$$$$$$ii$$$$$$$$$$i$$$i_________________
_____________________________iiiiiiiiiiiiiiiii$$$$i$$$$i$$$$$$$$i$ii$i$$$ii$$$i$i$i__1______________
_______________________________iiiiiiiiiiiiiiiiiiiii$$i$iii$iii$$i$$i$$$$i$$$ii$iii_________________
________________________________iiiiiiiiiiiiiiiiiii$iii$$$$$ii$$$$$$$$$i$$$$i$$$$$i_________________
__________________________________iiiiiiiiiiiiiiiiiii$iiiiii$$$i$$$i$iiii$$i$$$$$i___11_____________
_____________________________________iiiiiiiiiiiiiiiiiiii$ii$ii$$$ii$i$ii$$$$$$$ii___1______________
________________________________________iiiiiiiiiiiiiiiiiiiiiiiii$ii$ii$i$iiiiiii___________________
____________________________________________iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii________________________
____________________________________________________iii__i_iiiii_i________________1_________________
_________________________________________________________________________________1__________________
____________________________________________________________________________________________________
____________________________________________________________________________________________________
____________________________________________________________________________________________________
____________________________________________________________________________________________________
_____________________________________________________________________________1______________________
____________________________________________________________________________________________________
_____________________________________________________________________________________1______________
```
