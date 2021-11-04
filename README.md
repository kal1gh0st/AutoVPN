## AutoVPN
Ciao, oggi te lo spiego e ti mostro come realizzare il tuo strumento VPN su Linux.
Questo strumento è scritto in Bash, analizza l'elenco VPN Gate e quindi si connette a configurazioni casuali.

# Cominciamo... =)

1. Scarica openvpn su Linux

Codice:
sudo apt install openvpn

<p align="left">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="bash" width="40" height="40"/>
    </p>

2. Scarica il repository con i soliti comandi:

git clone https://github.com/kal1gh0st/AutoVPN.git
cd AutoVPN

3. Assegna al file il diritto di esecuzione:

Codice:
chmod +x autovpn.sh

4. Esegui lo script

Esegui da sudo:
Codice:
sudo ./autovpn.sh

Lo script raccoglierà informazioni su VPN ed eseguirà openvpn.

P.S. Se non si carica, puoi premere Ctrl + C, la console ti chiederà di selezionare un'altra VPN o di completare il lavoro.
