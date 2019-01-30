# TP4CCNA

## I-Mise en place du lab  

### 1.Création des réseaux
### 2.Création des VMs
### 3.Mise en place du routage statique
* Client1 ping Server1  
![Légende](TP4CCNA/IMG1.PNG)   
* Server1 ping Client1  
![Légende](TP4CCNA/IMG2.PNG)  
* Traceroute depuis le client1 pour voir le chemin pris par server1  
![Légende](TP4CCNA/IMG3.PNG)  
## II-Spéciologie réseau  

### 1.ARP
#### A.Manip 1
![Légende](TP4CCNA/IMG4.PNG)    
On obtient seulement cette ligne puisque aucune autre VM n'a ping sur le client.  

![Légende](TP4CCNA/IMG5.PNG)   
On obtient la aussi une seule ligne etant donné qu'aucune autre VM n'a ping sur le server1.   

![Légende](TP4CCNA/IMG6.PNG)   
Nous avons maintenant l'addresse de celui que nous avons ping

![Légende](TP4CCNA/IMG7.PNG)  
Et inversement pour le server1.

#### B.Manip2  
![Légende](TP4CCNA/IMG8.PNG)  
![Légende](TP4CCNA/IMG9.PNG)
![Légende](TP4CCNA/IMG10.PNG)

#### C.Manip3
![Légende](TP4CCNA/IMG11.PNG)
![Légende](TP4CCNA/IMG12.PNG)
![Légende](TP4CCNA/IMG13.PNG)

#### D.Manip4
![Légende](TP4CCNA/IMG14.PNG)
![Légende](TP4CCNA/IMG15.PNG)

### 2.Wireshark

#### A.Interception d'ARP et ping  
![Légende](TP4CCNA/IMG16.PNG)   
![Légende](TP4CCNA/IMG17.PNG) 
![Légende](TP4CCNA/IMG18.PNG)  
