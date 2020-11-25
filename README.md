# esercizio-24-pag-73
from random import randint
print("le percentuali dei voti dei due canditati x e y sono:")
x = randint(1,100)
y = (100 - x)
print (x,y)
# esercizio-25-pag-73
from random import randint 
print("le percentuali dei voti dei due candidati Giovanni e Marco sono:")
Giovanni = randint(1, 100)
Marco = ( 100 - Giovanni)
print (Giovanni, Marco)
if Giovanni > Marco :
    print ("la lista dei candidati in ordine alfabetico: Giovanni e Marco")
else:
    print ("la lista dei candidati in ordine decrescente: Marco e Giovanni")
# esercizio-26-pag-73
from random import randint
print("in una azienda di 5 dipendenti, ogni dipendente guadagna dai 1500 ai 2000 euro :")
dipendente1 = randint (1500, 2000)
dipendente2 = randint (1500, 2000)
dipendente3 = randint (1500,2000)
dipendente4 = randint (1500,2000)
dipendente5 = randint (1500,2000)
print("il primo dipendente guadagna",dipendente1, "euro al mese") 
print("il primo dipendente guadagna",dipendente2, "euro al mese") 
print("il primo dipendente guadagna",dipendente3, "euro al mese") 
print("il primo dipendente guadagna",dipendente4, "euro al mese") 
print("il primo dipendente guadagna",dipendente5, "euro al mese") 
media = (dipendente1 + dipendente2 + dipendente3 + dipendente4 + dipendente5) / 2
print (media)
print("inserisci un numero")
int (input())
if input != -1:
    print( media)
else :
    print("hai fermato il loop")
# esercizio-27-pag-73
from random import randint 
veicoli = randint(200, 300)
print ("oggi sono transitati in entrata ad un castello autostradale:", veicoli)
veicoli1 = randint(200, 300)
veicoli2 = randint(200, 300)
veicoli3 = randint(200, 300)
veicoli4 = randint(200, 300)
veicolitot = veicoli + veicoli1 + veicoli2 + veicoli3 + veicoli4
print ("nell'arco di 5 giorni sono passati in totale", veicolitot,"veicoli")
print ("scrivi un numero da 0 a 10")
input()
 if input != 0 :
    print (veicolitot)
else :
    print ("stop")
