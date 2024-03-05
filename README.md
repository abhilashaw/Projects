# Projects
def minion_game(string): # your code goes here vowels = ['A', 'E', 'I', 'O', 'U'] kevin = 0 stuart = 0

for i in range(len(string)):
    if string[i] in vowels:
        kevin += len(string) - i
    else:
        stuart += len(string) - i

if(kevin<stuart):
    print('Stuart',stuart)
else:
    print('Kevin',kevin)

return
if name == 'main': s = input() minion_game(s)
