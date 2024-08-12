# Conceptos Fundamentales

## ¿Qué es un servicio REST?

Un servicio REST (Representational State Transfer) es un estilo de arquitectura para el diseño de servicios web. En este tipo de servicio, se utilizan los métodos HTTP para realizar operaciones sobre los recursos, que se representan en formato JSON o XML. REST se basa en un conjunto de principios y restricciones, como el uso de URIs para identificar recursos, y es ampliamente utilizado por su simplicidad y escalabilidad.

## ¿Cuáles son los principios del diseño RESTful?

1. **Identificación de Recursos**: Cada recurso es identificado por un URI único.
2. **Manipulación de Recursos a través de Representaciones**: Los clientes interactúan con los recursos a través de sus representaciones, como JSON o XML.
3. **Autodescripción de Mensajes**: Los mensajes HTTP llevan suficiente información para describir cómo debe procesarse el mensaje.
4. **Uso de HTTP y sus Métodos**: Uso adecuado de los métodos HTTP (GET, POST, PUT, DELETE, etc.).
5. **Hipertextos como el Motor del Estado de la Aplicación (HATEOAS)**: Los clientes navegan la API a través de enlaces provistos en las respuestas.

## ¿Qué es HTTP y cuáles son los métodos HTTP más comunes?

HTTP (Hypertext Transfer Protocol) es un protocolo de comunicación que se utiliza para la transferencia de información en la web. Los métodos HTTP más comunes son:

- **GET**: Solicita un recurso.
- **POST**: Envía datos para crear un nuevo recurso.
- **PUT**: Actualiza un recurso existente.
- **DELETE**: Elimina un recurso.

## ¿Qué es un recurso en el contexto de un servicio REST?

Un recurso es cualquier entidad o dato que puede ser accedido o manipulado a través de un servicio REST. Los recursos son identificados mediante URIs.

## ¿Qué es un endpoint?

Un endpoint es una URL específica en una API que permite interactuar con un recurso particular. Cada endpoint está asociado con un método HTTP que define la operación a realizar sobre el recurso.

# Estructura de un Servicio REST

## ¿Qué es un URI y cómo se define?

Un URI (Uniform Resource Identifier) es una cadena de texto que identifica un recurso en una API RESTful. Un URI suele tener la forma `http://example.com/recurso`.

## ¿Qué es una API RESTful?

Una API RESTful es una interfaz de programación que sigue los principios de REST. Permite que diferentes sistemas interactúen entre sí utilizando HTTP, donde cada recurso tiene su URI y las operaciones sobre ellos se realizan mediante métodos HTTP.

## ¿Qué son los códigos de estado HTTP y cómo se usan en REST?

Los códigos de estado HTTP son respuestas estándar que indican el resultado de una solicitud HTTP. En REST, se usan para informar al cliente si la operación fue exitosa, si hubo errores, o si se requieren acciones adicionales.

### Tabla de Códigos de Estado HTTP Más Comunes

| Código | Significado                                |
| ------ | ------------------------------------------ |
| 200    | OK - Solicitud exitosa                     |
| 201    | Created - Recurso creado exitosamente      |
| 204    | No Content - No hay contenido              |
| 400    | Bad Request - Solicitud incorrecta         |
| 401    | Unauthorized - No autorizado               |
| 404    | Not Found - Recurso no encontrado          |
| 500    | Internal Server Error - Error del servidor |

## ¿Qué es JSON y por qué se usa comúnmente en APIs REST?

JSON (JavaScript Object Notation) es un formato ligero de intercambio de datos. Es fácil de leer y escribir tanto para humanos como para máquinas, lo que lo hace muy popular en APIs REST para el envío y recepción de datos. JSON se usa comúnmente porque es menos verboso que XML, lo que lo hace más eficiente para la transmisión de datos a través de la red.
