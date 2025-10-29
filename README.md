# Metasploit

## 🧰 Présentation rapide

Metasploit Framework est un outil de pentest (test d’intrusion) open source, utilisé pour :
* Scanner des failles de sécurité,
* Exploiter des vulnérabilités connues,
* Lancer des payloads,
* Créer et tester des exploits personnalisés.
Il est inclus par défaut dans Kali Linux.

## 
Vérifier que Metasploit est bien installé :
```bash
msfconsole --version
```
S'il n'est pas installé, l'installer depuis les dépôts officiels :  
```bash
sudo apt update
sudo apt install metasploit-framework -y
```

Démarrage de "postgresql"  

`systemctl enable postegresql` ou `service postgresql start`  

Une fois le service démarré  

``msfconsole`` permet de lancer metasploit  










## Importer scan Nmap dans MSF

Après enregistrement de la sortie de la commande Nmap en format xml (-oX), nous allons importer le scan dans la console MSF.  




