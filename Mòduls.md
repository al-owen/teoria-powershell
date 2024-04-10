Els mòduls en PowerShell són paquets que contenen col·leccions de cmdlets, proveïdors, funcions, variables, i altres eines que s'afegeixen a l'entorn de PowerShell per estendre les seves funcionalitats. Els mòduls poden ser desenvolupats per Microsoft, per tercers o pels propis usuaris.

### Característiques Clau dels Mòduls

- **Encapsulació**: Els mòduls encapsulen funcionalitats específiques, fent més fàcil la gestió, actualització i compartició de codi.
- **Reutilització**: Permeten als desenvolupadors i administradors de sistemes reutilitzar codi de manera eficient, facilitant la implementació de tasques complexes amb menys esforç.
- **Extensibilitat**: Els mòduls fan que PowerShell sigui extensible, permetent afegir noves funcionalitats segons les necessitats sense alterar l'entorn bàsic de PowerShell.

### Tipus de Mòduls

1. **Mòduls de Script**: Compostos per scripts de PowerShell (`.psm1`), aquests mòduls poden incloure funcions, variables, i cmdlets. Són fàcils de crear i distribuir.
2. **Mòduls Binaris**: Escrits en llenguatges .NET com C# o VB.NET i compilats en DLLs, aquests mòduls poden proporcionar funcionalitats més avançades i rendiment millorat.
3. **Mòduls de Manifest**: Contenen un fitxer de manifest (`.psd1`) que descriu el contingut del mòdul, incloent informació sobre l'autor, la versió, les dependències, etc. Poden agrupar mòduls de script, binaris, i altres recursos.

### Com Treballar amb Mòduls

- **Importar Mòduls**: Utilitza el cmdlet `Import-Module` per carregar un mòdul i les seves funcions a l'entorn actual de PowerShell.
- **Descobrir Mòduls**: `Get-Module -ListAvailable` mostra tots els mòduls disponibles en el sistema.
- **Instal·lar Mòduls**: Pot utilitzar `Install-Module` per descarregar i instal·lar mòduls des del PowerShell Gallery o altres fonts.