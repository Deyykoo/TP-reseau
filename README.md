# TP RESEAU 
## I. Affichage d'informations sur la pile TCP/IP locale
```
I.A : commande = ipconfig 
- Nom : IPV4 
- Adresse Mac : 00-93-37-9D-52-7E
- Adresse IP : 10.33.48.114


- Nom : carte ethernet
- Adresse Mac : A0-36-BC-6C-20-80
- Adresse IP : 192.168.56.1


I.B : commande = ipconfig  
- passerelle : 10.33.51.254


I.C : commande = arp -a
- adresse mac de la passerele : 7c-5a-1c-cb-fd-a4


I.D : chemin d'affichage :
panneau de configuration > Réseau et internet > Centre réseau et partage > modifier les paramètres de la carte > WI-FI > détails.

- adresse IP : 10.33.48.114
- adresse Mac : 00-93-37-9D-52-7E
- passerelle : 10.33.51.254
```

### 2. Modifications des informations
```
- 2.B : L'on peut perdre l'accès a internet dû a une mauvaise configuration ou un conflit d'adresses 
```	
## III. Manipulation d'autres outils/protocoles côté client

```
III.A DHCP : 
- commande = ipconfig /all
- adresse IP : 192.168.1.1
- bail DHCP : 29h environ
```

### 2. DNS

```
2.A : commande = ipconfig /all
- adresse IP serveur DNS: 2a01:cb19:31:ab00:5efa:25ff:fe1d:fa50


2.B : commande = nslookup google.com
- Serveur DNS : 2a00:1450:4007:810::200e
- Adresse IP : 172.217.20.206

      commande = nslookup ynov.com
- Serveurs DNS : 2606:4700:20::681a:be9
                2606:4700:20::ac43:4ae2
                2606:4700:20::681a:ae9

- Adresses IP : 104.26.11.233
               172.67.74.226
               104.26.10.233


reverse lookup : 231.34.113.12
- pas de résultat

reverse lookup : 78.34.2.17
- cable 
- bail DHCP : 1h
