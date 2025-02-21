# Pick-Your-Adventure
a Pick Your Adventure game to find the treasure, and it uses a lot of if/elif/else statements
      |                   |                  |                     |
|.="";=.||______
| | ,-",="" "=.|                  | |___________________|__"=._o"-. "=.______________|___________________ |                "=.o"=._      _"=. |
|:=.o "=..".-="'"=.|
| | .--" , ; "=._o." ,-"""-._ ".   | |___________________|_._"  ,. . `` , "-."-. ". '|___________________
| |o"=._ , " ; .". , "-."-.; ; |
|| ;-.o"=._; ."  '."\ . "-._ /_______________|_______ |                   | |o ;   "-.o"=._``  ' " ,.--o; |
||| ; (#) -.o "=._.--"_o.-; ;___|___________________ ____/______/______/___|o;._    "      ".o|o.--" ;o;///___
////"=.o--. ; | ; ; ;////
////"=.o--. ;o|o; .;o;///
/////"=.o.; | ;.--"o.--"////
/////"=.o|o_.--""////_
///////////_____ /

''')
#if you can't tell, the ASCII at the beginning is supposed to be a pretty treasure chest lol
##you can find more ASCII art here: https://www.asciiart.eu/


#instead of \n
##you also could've just put a linebreak into the code, like
##this

#the \ around the quotation'd words is to ensure that Python acknowledges these words has quotes
##instead of breaking up the string variable entirely. Python will get confused by all the straight up """"" marks
###you also could've put the whole string in ' lala ' , and then put the quotations around the words "wait"
###but you had the "You're" ... so if you went that route you would've done 'You\re at a crossword"

lower() makes it so that the user input can put Right or right, and the capital letter won't mess anything up
##so if they responded with RIGHT or Right, the code would lowercase the response in the background
##before proceeding to the next command/function
#'elif' is a special Python word for "but wait: there's more!" in the conditional coding sense
