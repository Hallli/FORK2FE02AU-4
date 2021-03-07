# FORK2FE02AU-

## A - Heysáta
```py
n = int(input()) 
k = input() #(nálin) sem leitað er af
s = input() #(nafnið) sem leitað er í
if k in s:print("Unnar fann hana!")
#sja hvort k stafurinn sé í s strengnum
else:print("Unnar fann hana ekki!") 
```


## B - Telja
```py
n = int(input()) # input 
for x in range(n):print(x+1) 
```

## D - Hornrétt
```py
import math
#importa fyrir math.sqrt (kvaðradrot)
a,b,c = map(int,input().split()) #Hérna er inputið a,b,c sem táknar hliðanar
if math.sqrt(a**2+b**2) == c:print(a*b//2) 
#píþagoras
else:print(-1) 
```

## E - Star Wars röðun
```py
n=21 #n er 21
deiling=21//3 #deila 21 með 3
listi=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21] #listi
partur1=listi[0:deiling]#partur 1 af listanum 1 / deiling
partur2=listi[deiling:2*deiling] # sama bara 2 nema sinnum 2 með deiling
partur3=listi[2*deiling:] #deilt með 2 i dieling
temp=partur2+partur1+partur3 #plusa allt saman
for i in temp:#for lykkja svo að það prenti svona
	print(i,end=” ”)
```

## F - Eldspýtur

```py
n,k=map(int,input().split())
If n%(k+1)!=0:
	print(“Jebb”)
else: 
	print(“Neibb”)
```

## I - Takkar

```py
a = int(input()) #fæ heiltölu sem er stærð takka Donalds
b = int(input()) #fæ heiltölu sem er stærð takka KimJong
if a > b:print("MAGA!") #maga ! ef trump
elif b > a:print("FAKE NEWS!") #fake news ef kim
else:print("WORLD WAR 3!") 
 ```
 




J -
```py
n = int(input())
aldur = [] 
for x in range(n):
    aldur.append(int(input())) 
print(min(aldur)) 
```


