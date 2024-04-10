Els cmdlets són comandaments lleugers utilitzats dins de l'entorn de PowerShell per realitzar tasques específiques d'administració de sistemes i automatització de tasques. El terme "cmdlet" és una combinació de les paraules "command" (comandament) i "let" (petit), indicant que es tracta d'un comandament petit o especialitzat. Cada cmdlet està dissenyat per realitzar una funció única, com ara gestionar processos del sistema, manipular fitxers i directoris, o administrar els serveis de Windows.

Característiques principals dels cmdlets inclouen:

1. **Nomenclatura Uniforme**: Els cmdlets segueixen una convenció de nomenclatura consistent de "[[Verbs|verb]]-[[Noms|Nom]]", on el verb descriu l'acció que realitza el cmdlet i el nom especifica l'objectiu de l'acció. Per exemple, el cmdlet `Get-Process` llista tots els processos que s'estan executant en el sistema.
    
2. **Objectes Com a Entrada i Sortida**: A diferència dels comandaments de shells tradicionals que treballen amb text, els cmdlets intercanvien objectes. Això permet als usuaris encadenar cmdlets junts en "pipelines", passant l'output d'un cmdlet com a input al següent per realitzar operacions complexes de dades.
    
3. **Extensibilitat**: Els usuaris i desenvolupadors poden crear els seus propis cmdlets personalitzats utilitzant C# o qualsevol altre llenguatge compatible amb .NET, ampliant la funcionalitat de PowerShell per adaptar-se a les seves necessitats específiques.
    
4. **Integració amb .NET Framework**: Com que PowerShell està basat en .NET Framework, els cmdlets poden utilitzar qualsevol de les biblioteques i APIs disponibles en .NET, permetent una potent capacitat d'automatització i configuració.
    
5. **Descobriment i Ajuda Integrats**: PowerShell proporciona comandaments integrats per descobrir cmdlets (`Get-Command`) i obtenir ajuda detallada sobre com utilitzar-los (`Get-Help`), fent més fàcil per als usuaris aprendre i utilitzar diferents cmdlets eficaçment.

