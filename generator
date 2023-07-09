

import random
password = []

letter = "q w e r t y u ı o p ğ ü a s d f g h j k l ş i z x c v b n m ö ç Q W E R T Y U I O P Ğ Ü A S D F G H J K L Ş İ Z X C V B N M Ö Ç"

number = "1 2 3 4 5 6 7 8 9 0"

symbol = "! '  + % & / ( ) = ?"

letter = letter.split()
number = number.split()
symbol = symbol.split()

psw_letter = int(input("How many letter would you like in your password:\n"))
psw_number = int(input(f"How many number would you like in your password:\n"))
psw_symbol = int(input(f"How many symbol would you like in your password:\n"))

password_list = []

for char in range(1, psw_letter + 1):
    hwm_password = random.choice(letter)
    password_list += hwm_password


for char in range(1, psw_number + 1):
    hwm_number = random.choice(number)
    password_list += hwm_number

for char in range(1, psw_symbol + 1):
    hwm_symbol = random.choice(symbol)
    password_list += hwm_symbol

random.shuffle(password_list)

password = ""
for char in password_list:
    password += char
print(f"Your password is: \"{password}\" ")
    
