
#########################################################
##################INFO###################################
#########################################################

Joe Zambrano Suárez GEA FORESTAL
Fecha creación:23/08/2022
Fecha última actualización: 23/08/2022
Nombre:Toolbox_GIS_general.tbx
Estas herramientas fueron creadas en ArcGIS 10.5p.

#########################################################
##################INCORPORACIÓN A ARCGIS###################################
#########################################################
1. Abrir Arcgis
2. Botón derecho en la caja de ArcToolbox
3. Seleccionar Add Toolbox...
4. En el cuadro de diálogo seleccionar Toolbox_GIS_general.tbx



#########################################################
##################TOOLS###################################
#########################################################

########## Reproject_files_batch

Input_folder: Carpeta donde están los archivos a reproyectar. Da igual que estén en distintas proyecciones los shapefiles.

Pattern: Si quieres coger unos archivos que su nombre cumplan un patrón de letras específicos. Ej: "quiero reproyectar sólo los shapefiles que empiecen por rio_"-->rio_*. Default[empty].

Input Feature Type (optional): Si quieres coger un tipo de shapefile (punto,polígono,línea...).Default[empty].

CRS_target : A qué CRS quieres reproyectar todos los input shapefiles.Default[ETRS 89 UTM ZONE 30n  EPSG:25830].

Output_folder: Ruta del archivo output en cada iteración. Ej: "C:\Users\USER\OneDrive\Documentos\TRABAJO\GIS_general\eliminar\%name%". "C:\Users\USER\OneDrive\Documentos\TRABAJO\GIS_general\eliminar\" hace referencia a la carpeta donde quieres guardarlo. 
"%name%" Hace que se guarde cada archivo output con el mismo nombre del archivo input. Si quieres añadirle un prefijo, se podría hacer "C:\Users\USER\OneDrive\Documentos\TRABAJO\GIS_general\eliminar\rio_%name%".





