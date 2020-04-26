# TP4_Reseau_Anonyme
Thomas Dumont

Sujet : Anonymat en ligne

## Proxy HTTP

🌞 Lancez Wireshark et observez le trafic émis lors d'un trafic utilisant un proxy HTTP, puis un proxy HTTPS.

* Proxy HTTP :
    * IP:Port : 51.83.166.106:3128

    * Résultat Wireshark :
        ![](https://i.ibb.co/g3yLDsM/01-WS-Proxy-HTTP.png)

* Proxy HTTPS :
    * IP:Port : 163.172.190.160:8811

    * Résultat Wireshark :
        ![](https://i.ibb.co/b5ddLPk/02-WS-Proxy-HTTPS.png)

## Tor

🌞 Lancez Wireshark et observez le trafic émis lors d'un trafic utilisant le Tor Browser, comparé à une connexion classique.

* Site HTTPS :
    ![](https://i.ibb.co/6g7fcvc/04-WS-Tor-HTTPS.png)

* Site HTTP : 
    ![](https://i.ibb.co/nQrdZbf/05-WS-Tor-HTTP.png)

## Hidden service Tor

* 🌞 Lancez tcpdump sur la VM et récupérez la capture sur l'hôte afin de l'exploiter avec Wireshark: 

    * IP de la VM en local : 192.168.1.62 
    ![](https://i.ibb.co/CB5ZVts/06-WS-Centos-Tor.png)

