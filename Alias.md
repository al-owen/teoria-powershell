Els alias en PowerShell són noms curts o alternatius per a cmdlets, funcions, scripts o altres comandaments. Aquests s'utilitzen per reduir la quantitat de text que has d'escriure i per facilitar la recordació de comandaments llargs o complicats. Els alias permeten als usuaris interactuar amb PowerShell de manera més eficient, especialment quan utilitzen comandaments freqüentment.

### Creació i Ús d'Alias

PowerShell inclou diversos alias predefinits per als seus cmdlets més comuns. Per exemple, `ls`, `dir`, i `gci` són tots alias de `Get-ChildItem`, el qual s'utilitza per llistar els fitxers i directoris.

Podem utilitzar el cmdlet `Get-Alias` per veure una llista dels alias disponibles en la nostre sessió de PowerShell. Per exemple:

``` powershell
Get-Alias
```

Aquest comandament mostrarà una llista dels alias definits i els comandaments als quals estan associats.

Per crear un nou alias, podem utilitzar el cmdlet `New-Alias`. Per exemple, si volem crear un alias per `Get-Process` que sigui `gp`, podem fer-ho amb:

``` powershell
New-Alias -Name gp -Value Get-Process
```

### Persistència d'Alias

Els alias creats amb `New-Alias` són només temporals i existeixen únicament durant la sessió actual de PowerShell. Si volem que els alias siguin permanents i disponibles en totes les sessions, es poden afegir els comandaments de creació d'alias al perfil de PowerShell.

El perfil de PowerShell és un script que s'executa cada vegada que inicies una sessió de PowerShell. Podem editar aquest fitxer i afegir-hi els comandaments per crear els nostres propis alias. Per trobar la ubicació del nostre perfil, podem utilitzar:

``` powershell
$PROFILE
```

Si el fitxer del perfil no existeix, espoden crear amb:

``` powershell
New-Item -Path $PROFILE -Type File -Force
```

Després, es pot editar el fitxer (per exemple, amb `notepad $PROFILE` o qualsevol editor de text) i afegir-hi els comandaments `New-Alias` per als alias que es volen fer permanents.