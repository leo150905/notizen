# notizen

chatgpt einlogdaten:
ukukiwi@gmail.com
pipikaka3000

https://gbssg.gitlab.io/m347/

---------------------------------------------------------------------------------------------

Theorie:

docker-compose.yml (Chrüzliufgobe):
werded Networks erstellt wemmers definiert oder mue mer da vorher mache?
no 3 meh aber ka

docker compose down (Chrüzliufgobe:
werded container glöscht?
werded volumes glöscht?
werded networks glöscht?
no ein meh aber ka

docker secrets:
Chammer alli environment-configs mit secrets setze wemmer _FILE ahängt?
Secrets sind i container ine verschlüsslet?
Secrest sind i container ine under /run/secrets/... ?
Pro file chan nur 1 Password gspeicheret werde?

Fehler finde imne docker-compose.yml
z.B:
port anstatt ports
depends-on anstatt depends_on
falschi iirückig
MySql anstatt mysql
...


Praktisch:

Mer het eifach mösse e docker-compose file für e redmine (https://hub.docker.com/_/redmine) image erstelle. 
Folgendi vorgabe hets geh:
uf port 8081 erreichbar
Date persistent
Password gsetzt aber nöd im docker-compose file (secret)

Denn e vorgebni dotnet konsoleawendig containerisiere. 
Dockerfile erstelle
compose file erstelle
die konsoleawendig
mariadb
