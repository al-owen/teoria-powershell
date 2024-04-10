Dins de PowerShell, els verbs són paraules clau que descriuen l'acció que realitza un cmdlet. Els verbs són part d'una convenció de nomenclatura estricta per ajudar a mantenir la consistència i previsibilitat en l'ús dels cmdlets. Aquí tens alguns dels verbs més habituals utilitzats en PowerShell, juntament amb les seves descripcions generals:

1. **Get**: Utilitzat per obtenir dades. Pot ser informació sobre configuracions, estats, objectes, etc. (`Get-Process`, `Get-Service`).
    
2. **Set**: Utilitzat per modificar dades. Aquest verb s'utilitza per canviar la configuració o estat d'un recurs (`Set-Date`, `Set-Service`).
    
3. **New**: Utilitzat per crear noves instàncies d'objectes. Pot incloure la creació de nous fitxers, directoris, o objectes específics de l'aplicació (`New-Item`, `New-Object`).
    
4. **Remove**: Utilitzat per eliminar objectes. Això pot referir-se a la supressió de fitxers, processos, o qualsevol altre tipus d'objecte (`Remove-Item`, `Remove-Service`).
    
5. **Invoke**: Emprat per executar o invocar accions, com per exemple executar comandaments o operacions que no es classifiquen sota els altres verbs (`Invoke-Command`, `Invoke-RestMethod`).
    
6. **Start**: Utilitzat per iniciar una operació, com arrencar un procés o iniciar un servei (`Start-Service`, `Start-Process`).
    
7. **Stop**: Utilitzat per aturar una operació, com detenir un procés en execució o aturar un servei (`Stop-Service`, `Stop-Process`).
    
8. **Write**: Utilitzat per escriure dades, sovint en un flux de sortida o fitxer (`Write-Output`, `Write-Host`).
    
9. **Export**: Utilitzat per exportar dades a un fitxer o altre destí (`Export-Csv`, `Export-Clixml`).
    
10. **Import**: Utilitzat per importar dades des d'un fitxer o altre origen (`Import-Csv`, `Import-Clixml`).
    
11. **Test**: Utilitzat per comprovar la configuració o estat d'un objecte, sovint retornant un valor booleà que indica si la condició de prova és veritat o fals (`Test-Path`, `Test-Connection`).