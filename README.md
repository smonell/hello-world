# hello-world

print 'Greetings Usurper!!!'
#This is a comment for the next person... Obvi
print ('''It's a beautiful day in \n"Westeros"''')
name = raw_input('To what house do you pledge allegiance to?')
if name in ['house stark','house bolton','house mormon','house umber']:
    print '''Ahh, your heart lies in the North! My allegiances are pledged to house stark!'''
if name in ['house tyrell','house lannister', 'house tully', 'house riverrun','house tarth']:
    print '''Wonderful!! Westeros houses are all family, united as parts of a greater whole! My allegiances are pledged to house stark!'''
sigil = raw_input('Do you know what the Starks house Sigil is?')
if sigil in ['a direwolf', 'direwolf', 'a wolf', 'a street doge']:
    print ('''That is correct! A Direwolf is the symbol of the 
Stark house and a beacon strength to all northern men''')
else:
    print ('''Not quite, House Stark's sigil is a Direwolf,
a beacon strength to all northern men!!!''')
