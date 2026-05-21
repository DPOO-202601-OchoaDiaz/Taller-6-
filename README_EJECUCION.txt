Instrucciones para ejecutar el taller

Opción 1: desde Eclipse
1. Abrir Eclipse.
2. Ir a File > Import > Existing Projects into Workspace.
3. Seleccionar la carpeta "Taller Swing Restaurantes Esqueleto".
4. Ejecutar la clase:
   src/uniandes/dpoo/swing/interfaz/principal/VentanaPrincipal.java
5. Presionar Run.

Opción 2: desde terminal
1. Ubicarse en la carpeta del proyecto.
2. Compilar:
   javac -encoding UTF-8 -d bin $(find src -name "*.java")
3. Ejecutar:
   java -cp bin uniandes.dpoo.swing.interfaz.principal.VentanaPrincipal

Qué hace la aplicación
- Muestra una lista de restaurantes.
- Permite ver el detalle del restaurante seleccionado.
- Permite crear un nuevo restaurante seleccionando nombre, calificación, visitado y ubicación en el mapa.
- Permite ver todos los restaurantes o solo los visitados en un mapa.
