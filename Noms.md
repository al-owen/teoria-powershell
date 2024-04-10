Els noms (o noms dels objectes) en els cmdlets de PowerShell solen referir-se a l'element sobre el qual actua el cmdlet. Aquests noms són dissenyats per ser descriptius i intuitius, de manera que els usuaris poden fàcilment entendre sobre què operarà el cmdlet. Encara que hi ha una àmplia varietat de noms utilitzats en els cmdlets, segons l'àmbit d'actuació, alguns dels noms més habituals inclouen:

1. **Item**: Fa referència a un element genèric, que pot ser un fitxer, un registre de Windows, o qualsevol altre objecte manipulable per PowerShell (`Get-Item`, `Remove-Item`).
    
2. **Process**: Utilitzat per operar sobre processos del sistema, com arrencar, aturar, o obtenir informació sobre processos en execució (`Get-Process`, `Stop-Process`).
    
3. **Service**: Refereix a serveis del sistema Windows, permetent als usuaris gestionar l'estat i la configuració dels serveis (`Get-Service`, `Start-Service`).
    
4. **EventLog**: Utilitzat per treballar amb els registres d'esdeveniments de Windows, permetent als usuaris llegir, escriure, o filtrar entrades de registre (`Get-EventLog`, `Write-EventLog`).
    
5. **Job**: Fa referència a tasques en segon pla iniciades per PowerShell. Els jobs permeten l'execució de comandaments de manera asincrònica (`Get-Job`, `Start-Job`).
    
6. **LocalUser**: Utilitzat per gestionar comptes d'usuari, incloent la creació, modificació, i eliminació d'usuaris en el sistema o en aplicacions específiques (`Get-LocalUser`, `New-LocalUser`).
    
7. **LocalGroup**: Refereix a grups d'usuaris, permetent la gestió de permisos i membres dins del sistema (`Get-LocalGroup`, `Add-LocalGroupMember`).
    
8. **Content**: Utilitzat per interactuar amb el contingut d'un fitxer, com llegir, escriure, o afegir dades a fitxers de text (`Get-Content`, `Set-Content`).
    
9. **Module**: Fa referència a mòduls de PowerShell, que són col·leccions de cmdlets, funcions, variables i altres components que s'agreguen a l'entorn de PowerShell (`Get-Module`, `Import-Module`).
    
10. **Policy**: Utilitzat en el context de polítiques de seguretat o configuracions de polítiques, com les polítiques de grup o polítiques d'execució de scripts (`Get-ExecutionPolicy`, `Set-ExecutionPolicy`).