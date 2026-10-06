# Fitxa tècnica: [Instal·lació del servidor web Apache]

## Objectiu

Instal·lar i comprovar el funcionament del servidor web Apache en un Sistema d'Ubuntus

## Materials

- Un ordinador o MV
- Connexió a Internet
- Tenir instal·lat Visual Studio Core
- Tenir la terminal de linux en la MV


## Procediment

1. Obrir la terminal de Linux 
2. Actualitzar l'informació amb la comanda "sudo apt update"
3. Instal·lar el servidor web Apache amb la comanda "sudo apt install apache2
4. Comprovar que el servei esta funcionant amb "systemctl status apache2"
5. Obrir un navegador web i introduir la adreça IP a la MV
6. Comprovar que tot estigui correcte.



## Comprovacions

- [ ] Apache s'ha instal·lat correctament.
- [ ] El servei Apache està actiu.
- [ ] La pàgina web d'Apache es mostra correctament.
- [ ] La màquina té connexió a Internet.

## Incidències i solucions

Incidencia: Apache no s'instala

Solució: Comprovar la connexió i executar "sudo apt update"

------------------------------------------------------------

Incidencia: El servei Apache no esta actiu 

Solució: Executar "sudo systemctl start apache2"

## Recursos

- [Documentació consultada](https://httpd.apache.org/docs/)