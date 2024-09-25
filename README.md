# Guía de Uso - Sherline Mill 5410 con Linux CNC y G-code desde Fusion 360

### **Flujo de Trabajo**

#### Diseño en Fusion 360:

1. **Diseña la Pieza:**
   - Crea tu diseño en el entorno de Fusion 360 creando un nuevo diseño de electronica para crear tu esquematico y PCB.
   - Exporta tu PCB como modelo 3D.
   
2. **Generar la Estrategia de Maquinado:**
   - Ve a la pestaña `Fabricar` en Fusion 360.
   - Crea un nuevo setup para definir el entorno de trabajo.
   - Crea una estrategia de como generar la PCB.
   - Define las operaciones de maquinado, tales como desbaste, acabado, contorneado, etc.
   
3. **Generación del G-code:**
   - Selecciona `Post-Proceso`.
   - Escoge el post-procesador LinuxCNC Enchaned Machine Control (EMC).
   - Genera el archivo G-code (.ngc para este caso).
   - Guarda el archivo y cargalo en una USB para llevarlo a Linux CNC.

#### Configuración de la Sherline 5410 con Linux CNC:

1. **Encender la Máquina:**
   - Conecta la Sherline a la computadora y enciende la máquina.

2. **Cargar el G-code en Linux CNC:**
   - Abre Linux CNC y selecciona el archivo G-code generado por Fusion 360.
   - Verifica la trayectoria de la herramienta utilizando la opción de simulación (`Preview`).

3. **Ajustar los Ejes:**
   - Realiza el "homing" de los ejes X, Y, Z.
   - Asegúrate de que las coordenadas de la pieza estén correctamente definidas.

4. **Iniciar el Maquinado:**
   - Inicia el proceso de maquinado.
   - Supervisa el proceso para asegurarte de que no haya errores o problemas mecánicos.



