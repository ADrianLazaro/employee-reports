Contexto:
Tenemos dos repositorios:

"employee-app" (Repo A): Aplicación principal que maneja datos de empleados
"employee-reports" (Repo B): Repositorio que genera reportes

El flujo será:

Se activa manualmente un workflow para registrar un nuevo empleado
Si el registro es exitoso, se dispara otro workflow que captura los datos del empleado
Estos datos se envían al repositorio de reportes para actualizar las estadísticas
