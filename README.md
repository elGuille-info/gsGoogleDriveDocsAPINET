# gsGoogleDriveDocsAPINET
Utilidad para guardar las notas de gsNotasNET en Google Drive. Para hacerlo debes estar autorizado.

> **NOTA:** <br>
> Para poder guardar las notas en **tu Google Drive** debes estar autorizado.
> Pide la autorización según indico en este post del blog:<br>
> [¿Te gustaría obtener más prestaciones de gsNotasNET?](http://www.elguillemola.com/2020/12/te-gustaria-obtener-mas-prestaciones-de-gsnotasnet/)<br>
> Gracias.

Es importante que sepas que lo único que el programa **toca** de Google Drive son los documentos creados según las notas guardadas por el programa.

Las notas **siempre** se guardan en el fichero de texto de la aplicación (ubicado en Documentos\gsNotasNETF.notasUC.txt), independientemente que elijas guardarlos en Google Drive.

## Revisiones<br>
<br>

### gsGoogleDriveDocsAPINET v1.0.0.2<br>
Cambio a public algunos de los métodos usados internamente por el método principal (GuardarNotasDrive) a usar desde la aplicación gsNotasNET.<br>

Los métodos que he puesto como públicos son:<br>
**ExisteFolder** - Comprueba si existe la carpeta indicada. Si existe devuelve el ID, si no, una cadena vacía.<br>
**CrearFolder** - Crea un directorio en el raíz de Drive.<br>
**CrearSubFolder** - Crea un directorio dentro del directorio con el ID indicado.<br>
**CrearFile** - Crear un fichero en la carpeta indicada.<br>
**EliminarDocumentos** - Elimina los documentos que haya en la carpeta indicada. Los nombres de los documentos a eliminar deben empezar con el nombre de la carpeta. folderName_nombre.doc<br>
**LeerNotas** - Lee las notas del programa gsNotasNETF.<br>

