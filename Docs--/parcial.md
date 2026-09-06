# Definición de la Historia de Usuario (HU-002)

- *ID:* HU-002-Codigo
- *Título:* Generación de código QR de acceso único

## Descripción

- *Yo como:* Usuario registrado
- *Necesito:* Generar un código QR único
- *Para:* Ingresar de forma rápida a los refugios

## Criterios de Aceptación

1. *Visualización del perfil:*  
   El sistema debe contar con una sección de perfil del usuario donde se muestre su información básica y un botón activo para *"Generar Código QR de Acceso"*.

2. *Generación y unicidad del token:*  
   Al presionar el botón, el sistema debe generar un código QR cifrado basado en el ID único del usuario y una marca de tiempo (timestamp) temporal para evitar duplicidades o clonaciones.

3. *Diseño y descarga:*  
   El código QR generado debe visualizarse claramente en la pantalla del dispositivo móvil con la opción de descargarlo o guardarlo localmente para acceso offline.

4. *Control de validez y escaneo:*  
   El sistema del refugio debe poder escanear el código QR mediante la aplicación del personal autorizado para registrar la entrada exitosa del usuario en tiempo real.

5. *Manejo de errores:*  
   Si el usuario no cuenta con una cuenta activa o validada, el sistema debe mostrar un mensaje emergente impidiendo la generación del código y redirigiéndolo al soporte.