# Simulación de Historia de Usuario

**ID:** `HU-001-Registro`


## Descripción

* **Como:** Ciudadano  
* **Quiero:** Registrarme con mi DUI para quedar como beneficiario del plan de refugios  
* **Para:** Acceder de forma segura y recibir la asistencia adecuada ante emergencias  


## Criterios de Aceptación

1. **Diseño de la interfaz de registro:**  
   Crear una pantalla donde el ciudadano ingrese su número de DUI y datos personales básicos.

2. **Validación de formato de DUI:**  
   Implementar una validación estricta para asegurar que el número de DUI cumpla con el formato oficial de El Salvador (`00000000-0`: 8 dígitos, un guion y 1 dígito verificador).

3. **Verificación de duplicidad:**  
   Validar en la base de datos que el DUI ingresado no se encuentre previamente registrado en el plan de refugios.

4. **Mensajes de error en credenciales inválidas:**  
   Mostrar alertas claras en pantalla si el DUI es incorrecto, incompleto o ya está registrado.

5. **Realizar pruebas funcionales:**  
   Ejecutar pruebas de aceptación para verificar el registro exitoso del beneficiario y su almacenamiento en el sistema.