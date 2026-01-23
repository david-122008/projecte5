![Imatge 01](IMG/INGM10.png)

El server manager serà la nostra eina principal 

![Imatge 01](IMG/INGM11.png)

Primer de tot canviarem el nostre nom del nostre server

![Imatge 01](IMG/INGM13.png)

Per fer-ho anirem a l’apartat de local server, i a computer name posarem DC07 i li donarem a ok

![Imatge 01](IMG/INGM17.png)

Després canviarem l’apartat de domini entrant a l'app de configuració de windows, entrant a network i a l’apartat Ethernet editarem els settings el canviarem a manual i posarem 127.0.0.1 i clicarem save

![Imatge 01](IMG/INGM18.png)

Posteriorment, tornarem a srever manager, i a l’apartat de manager li donarem a add roles

![Imatge 01](IMG/INM2.png)

A select installation type seleccionarem la primera opció

![Imatge 01](IMG/INM3.png)

Instalarem el roles de forma centrlitzada,

![Imatge 01](IMG/INM5.png)

Activarem l'opció d’Active directory domain services

![Imatge 01](IMG/INM4.png)

Li donarem a add features,

![Imatge 01](IMG/INM6.png)

Li donem a next

![Imatge 01](IMG/INM7.png)

I install

![Imatge 01](IMG/INM8.png)

Després clicarem post-deployment configuration

![Imatge 01](IMG/INM11.png)

Posarem de nom  translogic07.test, i add new forest

![Imatge 01](IMG/INM12.png)

Posarem Windows server 2025 i a la contrasenya P@ssw0rd

![Imatge 01](IMG/INM13.png)

Després li donarem a next

![Imatge 01](IMG/INM14.png)

Tornem a posar el nom del domini

![Imatge 01](IMG/INM15.png)

En aquest apartat a next, 

![Imatge 01](IMG/INM16.png)

Li donem a next

![Imatge 01](IMG/INM17.png)

Comprovem l’instal·lació.

![Imatge 01](IMG/INM18.png)

I reiniciem la màquina.

![Imatge 01](IMG/INM19.png)

Després modificarem la zona horària però en utc de Madrid

![Imatge 01](IMG/INM21.png)

Ara configurarem un reenviador per fer que sigui més ràpid, però fer-ho anirem a DNS manager,

![Imatge 01](IMG/INM23.png)

Entrarem a forwarders look up zone i li donarem ha edit,

![Imatge 01](IMG/INM24.png)

Aquí afegirem l’IP del DNS de Google,



