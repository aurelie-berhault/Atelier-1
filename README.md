# Atelier 1 (20 Mars 2020)

**Capture 1**

1/ Veuillez identifier votre serveur GNS3 qui est capgchambX.goffinet.net où X est le numéro de votre serveur.
Pouvez-vous interpréter de la manière la plus précise la commande suivante adaptée de la valeur X de votre serveur ? 
Quel résultat fournit-elle ?
curl http://capgchamb0.goffinet.net:8003

Mon serveur est capgchamb4.goffinet.net
La commande « curl http://capgchamb4.goffinet.net » donne l’adresse IP (ici en IPv4) de la connexion au serveur. L’adresse IP obtenue est 51.15.202.92

2/ Veuillez capturer le trafic de ce1e commande uniquement et l'enregistrer sous le nom capture1.pcapng.

voir fichier joint : capture1.pcapng

3/ Quel est le numéro du port source u2lisé par le client pour joindre ce6e ressource Internet ?

Le numéro de port source utilisé par le client pour joindre cette ressource est le port 8003.

4/ Quel est le numéro du paquet qui con5ent la commande de couche Application ?

le paquet n°9 contient la commande de couche application (http)

5/ Quel est le paquet qui commence la session ? Quel est le paquet qui termine la session ?

le numéro du paquet qui commence la session est le numéro 6 et le paquet qui termine la session est le numéro 17.

**Capture 2**

1/ Pouvez-vous interpréter de la manière la plus précise la commande suivante ? 
Quel résultat fournit-elle et comment ?dig @ns1.google.com -t TXT o-o.myaddr.l.google.com +short -4

La commande complète indiquée fournit le même résultat qu’à la question 1 de l’exercice Capture 1. 
On obtient l’adresse IP 51.15.202.92. 
Cette commande permet de trouver mon adresse ip publique. Format texte (TXT)

2/ Veuillez capturer le trafic de ce1e commande uniquement et l'enregistrer sous le nom capture2.pcapng.

voir fichier joint capture2.pcapng

3/ Combien de transac1ons sont-elles générées ? Pourquoi y en a-t-il autant ?

il y a deux transactions DNS. 1 question puis 1 réponse.

4/ Pour chacune des transac0ons, quelle est la ques0on (QUERY) qui est posée ?

« quelle est mon adresse IP publique ? »

5/ Pour chacune des transac0ons, à quel ordinateur est posée la question ?

la question est posée à ns1.google.com (216.239.32.10)
