PowerShell ofereix una àmplia gamma de cmdlets dissenyats per a la gestió d'arxius i directoris, permetent realitzar operacions com crear, llegir, escriure, modificar i eliminar fitxers, així com navegar i manipular l'estructura de directoris. 

### Navegació i Llistat
- `Get-ChildItem` (`ls`, `dir`): Llista els fitxers i directoris dins d'un directori. Pot utilitzar-se amb paràmetres per filtrar els resultats.
- `Set-Location` (`cd`): Canvia el directori actual a la ubicació especificada.
- `Get-Location` (`pwd`): Mostra el directori de treball actual.

### Creació i Eliminació
- `New-Item`: Crea un nou fitxer o directori. El tipus d'element (fitxer o directori) es pot especificar amb el paràmetre `-ItemType`.
- `Remove-Item` (`rm`): Elimina un o diversos fitxers o directoris. Pot requerir paràmetres addicionals per confirmar l'eliminació de directoris no buits o elements de lectura protegida.

### Lectura i Escriptura
- `Get-Content` (`cat`, `type`): Llegeix el contingut d'un fitxer i el mostra a la consola.
- `Set-Content`: Escriu o substitueix el contingut d'un fitxer amb el text especificat. No afegirà el text al contingut existent, sinó que el substituirà.
- `Add-Content`: Afegeix text al final d'un fitxer existent sense sobreescriure el contingut previ.
- `Out-File`: Redirigeix l'output d'un cmdlet a un fitxer, similar a `Set-Content`, però amb més opcions de personalització.

### Modificació
- `Copy-Item` (`cp`): Copia fitxers i directoris a una nova ubicació.
- `Move-Item` (`mv`): Mou o canvia el nom d'arxius i directoris.
- `Rename-Item` (`ren`): Canvia el nom d'un fitxer o directori.

### Informació d'Arxius i Directoris
- `Get-Item`: Obté l'objecte que representa un fitxer o directori específic, proporcionant informació detallada sobre aquest.
- `Get-ItemProperty`: Mostra les propietats d'un fitxer o directori, com ara mida, data de modificació, atributs, etc.

### Permisos i Propietat
- `Get-Acl`: Mostra la llista de control d'accés (ACL) per a un fitxer o directori, detallant els permisos.
- `Set-Acl`: Modifica l'ACL d'un fitxer o directori, permetent canviar els permisos.

Aquests cmdlets formen la base de la gestió d'arxius i directoris en PowerShell, oferint una potent eina per a l'automatització de tasques relacionades amb el sistema de fitxers. Utilitzant aquests comandaments, juntament amb les capacitats de scripting de PowerShell, pots realitzar operacions complexes sobre arxius i directoris de manera eficient.