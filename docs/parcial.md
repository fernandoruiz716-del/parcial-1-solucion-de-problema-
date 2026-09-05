# Historia de Usuario: HU-001-familiar

## Descripción
* **ID:** HU-001-familiar
* **Como:** Responsable de la familia
* **Necesito:** Agregar a mis familiares (cónyuge e hijo/as menores mediante su partida de nacimiento)
* **Para:** Tenerlos bajo mi mismo registro

---

## Criterios de Aceptación

1. **Sección de Gestión Familiar:** 
   * Crear una interfaz o vista de "Mi Núcleo Familiar" accesible directamente desde el perfil del usuario principal.

2. **Formulario de Registro de Cónyuge:** 
   * Implementar campos estructurados para capturar los datos del cónyuge (Nombre completo, Documento de identidad y Vínculo).

3. **Formulario de Registro de Hijos/as Menores:** 
   * Incluir la opción de agregar hijos menores permitiendo adjuntar o ingresar los datos correspondientes de su partida de nacimiento.

4. **Validación de Vínculo:** 
   * Validar que los documentos ingresados no se encuentren duplicados o registrados previamente en otra cuenta principal del sistema.

5. **Mensajes de Confirmación/Error:** 
   * Mostrar una alerta visual de éxito al registrar correctamente a un familiar, o un mensaje de error descriptivo si algún campo obligatorio o formato de documento es inválido.

6. **Pruebas Funcionales:** 
   * Realizar pruebas de flujo completo (añadir cónyuge + añadir hijo/a con partida de nacimiento) para asegurar que queden correctamente asociados al mismo registro del responsable.
   