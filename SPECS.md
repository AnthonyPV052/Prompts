# ARCHIVO HTML
- Propósito: plataforma SaaS diriga a empresas, donde pueden alquilar agentes de IA — asistentes inteligentes preconfigurados que pueden equiparse con distintas skills (habilidades como navegar por la web, leer documentos o gestionar calendarios) y desplegarse para tareas de negocio específicas.
## Requisitos Iniciales
- Uso de HTML semántico
- Uso de Tailwind
## Especificaciones de contenido

### Barra de Navegación
- Lateral y persistente
- Boton toggle para cambiar entre modo oscuro/claro usando clase :dark de Tailwind

### Dashboard
- Tarjetas organizadas con los siguientes contenidos:
 - Sección: Ingresos mensuales totales generados
 - Sección: Pérdida total por descuentos y cupones
 - Sección: Número de agentes activos en todos los clientes
 - Sección: Número de agentes actualmente marcados como fallando
### Tabla de gestión de usuarios
- Información de cada usuario: Nombre, email, plan y estado
- Dropdown de acciones en cada fila (activado con un batón "⋮" )
 - Acción-Ver detalles: Abre un modal overlay con el registro completo del usuario. Se debe poder cerrar el modal con un botón en la esquina superior derecha o con un click en el backdrop
### Lista de agentes registrados
- Nombre, agente, propietario, estado actual (activo / inactivo / fallando) y lista de skills colapsada.
- Dropdown para cada agente con las opciones: Configurar(Abre modal con el prompt de sistema del agente), Eliminar.
### Catálogo de skills
- Propósito:Muestra las capacidades (De los agentes IA) adjuntables disponibles. 
- Formato: Cada skill va con su nombre, breve descipción y un contador con la cantidad de agentes que la tienen actualmente.
- Dropdown con "Ver detalle" y "Eliminar
### Tabla de gestión de contratos de alquiler
- Información por fila: Cliente, agente alquilado, skills contratadas, fecha de contrato, importe total pagado.
- Dropdown  de acciones para cada fila.
 - Ver detalles: Abre un modal con el desglose completo del contrato, skills contratadas y precios individuales.
### Registro de errores de agentes
- Información: Timestamp, nombre del agente, tipo de error y breve descripción.
- Categorización visual por tipo o gravedad.
- Dropdown de acciones
 - Ver Detalles: abre modal con la traza completa del error
 - Marcar como resuelto
 

