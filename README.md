# PlantUML en IntelliJ

Configurar IntelliJ para que visualice correctamente diagramas [PlantUML](https://plantuml.com/es/).

Al abrir un proyecto cuyo README.md tenga un diagrama UML escrito en PlantUML, aparecerá así si no se han instalado las herramientas adecuadas.

![](./capturas/VirtualBox_Windows_10_09_03_2020_20_48_24.png)

> Nota: Pasos para macOS más abajo.

## Windows

1. Cerrar IntelliJ por completo.

2. Descargar [Graphviz para Windows](https://graphviz.gitlab.io/_pages/Download/Download_windows.html).
 
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_50_18.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_50_35.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_50_49.png)

3. Instalar Graphviz (marcar Everyone en las opciones, el resto por defecto).

	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_51_12.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_51_23.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_51_38.png)

4. Copiar la ruta a la instalación de Graphviz.

	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_52_16.png)

5. Añadir la ruta copiada a la variable de entorno PATH.

	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_52_32.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_52_45.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_53_45.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_54_43.png)

6. Abrir IntelliJ, ir a los ajustes, buscar Languages & Frameworks -> Markdown e instalar la opción PlantUML.

	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_55_46.png)
	
	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_56_08.png)

7. Cerrar la pestaña y volver a cargar el fichero README.md.

	![](./capturas/VirtualBox_Windows_10_09_03_2020_20_57_32.png)

## macOS

1. Cerrar IntelliJ.

2. Instalar [Homebrew](https://brew.sh).

3. Abrir un Terminal e instalar Graphviz.

	```
	brew install graphviz
	```
	
4. Ir al paso 6 de las instrucciones para Windows.
