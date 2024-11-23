
# Proyecto PHP y MySQL - MVC con Promesas

Este proyecto implementa una arquitectura Modelo-Vista-Controlador (MVC) en PHP para la gestión de datos con una base de datos MySQL. Incluye funcionalidades de inserción, consulta, edición y subida de archivos. Ideal como referencia para aprender o desarrollar aplicaciones con PHP usando un enfoque estructurado.

## Características

- **Inserción de datos**: Incluye módulos para insertar datos en la base de datos.
- **Consultas dinámicas**: Realiza consultas mediante controladores especializados.
- **Edición avanzada**: Edición utilizando declaraciones preparadas para mayor seguridad.
- **Subida de archivos**: Manejo de archivos cargados por el usuario.
- **Promesas en JavaScript**: Mejora la experiencia del usuario y la comunicación con el backend.
- **Patrón MVC**: Organización clara y escalable del código.

## Estructura del Proyecto

```
├── index.php                     # Entrada principal
├── Controllers/                  # Controladores para manejar la lógica de negocio
├── Models/                       # Modelos que gestionan las interacciones con la BD
├── Views/                        # Vistas para mostrar datos al usuario
├── Db/                           # Conexiones y scripts SQL
├── Assets/                       # Archivos estáticos (CSS, JS)
├── insercion-con-declaraciones-preparadas.php # Ejemplo de funcionalidad
```

## Instalación y Configuración

1. **Clona este repositorio**:
   ```bash
   git clone <URL del repositorio>
   ```

2. **Importa la base de datos**:
   - Utiliza el archivo `Db/Sql1.sql` para crear las tablas necesarias en tu base de datos MySQL.

3. **Configura la conexión**:
   - Edita el archivo `Db/Con1Db.php` con tus credenciales de MySQL.

4. **Inicia un servidor local**:
   - Puedes usar XAMPP, WAMP o cualquier servidor compatible con PHP.
   - Asegúrate de que el directorio raíz apunte al proyecto.

5. **Accede al proyecto**:
   - Abre tu navegador y visita `http://localhost/<nombre_del_proyecto>`.

## Tecnologías Usadas

- **PHP**: Backend y lógica del servidor.
- **MySQL**: Gestión de datos.
- **JavaScript**: Interactividad en el frontend.
- **CSS**: Estilos personalizados.
- **HTML**: Estructura de las vistas.
