# Tombola
**Demo Applications**
https://4passion.net/gam/bingo.php
https://4passion.net/gam/tombola.php
**Configuration File**
The configuration files have the following syntax

#      layout
title  =Agile Bullshit Bingo
style  =_abb
numbers=%02d
#        board
tokens =56
rows   = 7
cols   = 8
#       cartel
columns= 4
#       path & file-extension for the action-buttons
fmtbtn =./button_abb/%s.gif
#       path & file-extension for the cards
fmtcrd =http://dataonthe.net/img/deck/Bingo/0%s.jpg
#       SFX
//      to disable speach, set the first char to 0| a different number select how many different voices will be used
voices =0|UK English Female|UK English Male
phrases=5|the new number is|and now, I've pulled the|unbelievable: we have now the|and ony for you we have the|wow, you are lucky if you have the   
sound  =on
//      on = sounds enabled | off = sounds disabled
prizes =6||Ambo|Terno|Quaterna|Cinquina|Tombola
#      initial nuber of players/cartels displayed
players= 3
#        cartel caption
cartel =cartel %02d
