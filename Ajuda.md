Per obtenir ajuda sobre un cmdlet específic en PowerShell, espot utilitzar el cmdlet `Get-Help`. Aquest cmdlet proporciona informació detallada sobre l'ús dels cmdlets, incloent una descripció de la seva funció, els paràmetres que accepta, exemples d'ús, i enllaços a informació addicional si n'hi ha disponible.

### Ús Bàsic

- Per obtenir ajuda sobre un cmdlet específic, executem:

```powershell
Get-Help NomDelCmdlet
```

- Per exemple, per obtenir ajuda sobre el cmdlet `Get-Service`, utilitzem:

``` powershell
Get-Help Get-Service
```

### Obtenció d'Ajuda Més Detallada

PowerShell ofereix diferents nivells de detall per a la informació d'ajuda. Es pot especificar el tipus d'ajuda que desitgem utilitzant paràmetres addicionals:

- **-Detailed**: Mostra una descripció detallada del cmdlet, incloent tots els paràmetres.

``` powershell
Get-Help Nom-Comandament -Detailed
```

- **-Examples**: Mostra només exemples d'ús del cmdlet.

``` powershell
Get-Help Nom-Comandament -Examples
```

- **-Full**: Mostra tota la informació d'ajuda disponible, incloent una descripció detallada, paràmetres, exemples, notes, i informació sobre els inputs i outputs. 

``` powershell    
Get-Help Nom-Comandament -Full
```

- **-Online**: Obre la documentació d'ajuda del cmdlet en el navegador web per defecte. Aquesta opció és útil per obtenir la versió més actualitzada de l'ajuda.

```powershell 
Get-Help Nom-Comandament -Online 
```

### Actualització de l'Ajuda

PowerShell permet actualitzar la informació d'ajuda per assegurar-se que tinguis accés a la documentació més recent. Per actualitzar l'ajuda de tots els mòduls instal·lats, executem:

``` powershell
Update-Help
```

Pot ser que necesitis permisos d'administrador per actualitzar l'ajuda amb aquest mètode.