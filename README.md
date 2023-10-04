## Cash-Register-Using-Intel-8086-Processor

The system designed is a Cash Register a modified form of the ones available at billing counters of eateries or grosery stores. The system is a stand-alone with inputs provides via a keyboard. Outputs are available via a LCD display. System gets power via the standard power outlet. System has chargeable battery available with it, that is used a battery back-up of the RAM. The battery charges itself when the system is on. A fully-charged battery has a life-time of 36 hours.

# System Requirements:

Keyboard with following buttons :
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, Y(yes), N(no), Enter, Backspace, Cancel, 
Item No., Quantity, Total, Mode, Trans, Program, Add Item, Del Item, Cost

Display : Display is a Liquid Crystal Display .Size of the Display is 16 x 1 (16 characters on one line). 
        : The LCD is connected to the micro-controller through a display driver in this case HD44780 which is available with the LCD System Operation.

#Folloing are the rules:
o The system is Interactive in nature.
o The system is provided security by a hardware lock. Only when the lock is open the system is functional. 
o The lock system comes with a key. When the key is turned, the lock circuit gives a TTL high output else it gives a TTL low output.
o If the user presses a key on the keyboard when the lock is closed the system turns on a buzzer.
o At any point of time when the system is operational if the lock is closed the system must be disabled.
o A pulse of frequency 4 KHz turns on the buzzer. Buzzer is turned on for 1 Minute and then turned off.
o After the lock is open, the LCD is turned on and it displays “System Ready”.
o The user has to then press the Mode button on the keyboard. The LCD then displays “Select Mode”.
o The user can operate in any of the two modes Transaction/Program. Transaction is the normal function and in the Program Mode, user is allowed to add new items and their cost.
o Every item has an item code and a cost associated with it.
o If the user presses the Trans key the system enters into transaction mode. The LCD displays “Enter Transaction Mode Y/N ?”.
o User then has to press Y to confirm. If user presses N it goes back to Mode Select display.
o In the Transaction mode user is expected to enter the item code and the quantity. Item code has to be entered using the Item No. key followed by the item code. The item code can be entered with the help of the numeric keys 0-9. At the end of the item code the user has to press the Enter key. The item code will be then displayed on the LCD.
o User can press Backspace key to change the value of last key press or he can press Cancel to delete the whole entry.
o After the item code is displayed, user has to enter the quantity by pressing Quantity key followed by quantity of the item (using the numeric keys) a person wishes to buy and the Enter key.
o Automatically the total cost of the item will be displayed on the LCD.
o The user can continue entering all the items and finally press Total to display the total cost.
o In the Program mode user can add new items or delete an item. If the cost of an item is to be updated it has to first deleted and re-added to the item list in memory.
o When you add a new item you have enter the item number by using the Item no. key and the cost using the Cost key. After the cost has been keyed in the user must press Enter.
o The inter-active display will confirm your entry before storing it in the memory.
o If an item is to be deleted it is done using the Del Item key. Then user is required to press the Item No key followed by the item code and then press Enter.
o The inter-active display will confirm your entry before deleting it from the memory
