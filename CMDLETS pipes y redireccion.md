Els "pipes" (també coneguts com a canonades) en PowerShell són un concepte fonamental que permet passar l'output (sortida) d'un cmdlet com a input (entrada) a un altre cmdlet. Aquesta funcionalitat facilita la creació de seqüències de comandaments per realitzar operacions complexes en una sola línia de comandes. El símbol que representa un pipe és `|`.

### Com Funcionen els Pipes

Quan utilitzes un pipe en PowerShell, l'output del primer cmdlet es passa directament com a input al següent cmdlet en la cadena. A diferència d'altres shells que treballen només amb text, PowerShell passa objectes complets entre cmdlets a través del pipe. Això permet manipular i processar dades de manera molt eficient sense necessitat de convertir-les a text o parsejar-les de nou.

La sintaxi es la següent :
``` powershell
cmdlet | Where-Object {<condició>}
```

Exemples:

``` powershell
Get-ChildItem -Recurse | Where-Object {$_.Extension -eq ".txt"}
Get-ChildItem -Recurse | Where-Object {$_.Length -gt 1000}
```
## Com funcionen les redireccions

Els redireccionamient a PowerShell, Bash o altres intèrprets de comandes, són una característica que permet dirigir l'entrada (input), sortida estàndard (stdout) o l'error estàndard (stderr) d'un programa cap a un altre programa, fitxer, dispositiu, etc. Això es fa servir sovint per guardar l'output d'un programa en un fitxer, encadenar diversos comandaments junts, o gestionar els errors de manera més eficaç.

La sintaxi es la següent: 
``` powershell
cmdlet > output.extensió #Sobreescriu el fitxer
cmdlet >> output.extensió #Afegeix al final del fitxer
```

Exemples: 

``` powershell
Get-ChildItem -Recurse | Where-Object {$_.Length -gt 1000} > info.txt
Get-Date >> info.txt
```
