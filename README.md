# Mi IA con Blazor — Tu propia Inteligencia Artificial local

### Crea tu propio asistente de IA con C#, .NET 10, Blazor y Ollama

**Una aplicación web moderna para interactuar con modelos de lenguaje ejecutados localmente, sin depender de una API comercial para generar respuestas.**

Desarrollado por **render2web**.

---

## Descripción del proyecto

**Mi IA con Blazor** es un proyecto educativo que demuestra cómo integrar inteligencia artificial generativa en una aplicación web desarrollada con tecnologías del ecosistema .NET.

A través de una interfaz conversacional, el usuario puede enviar preguntas y recibir respuestas generadas por un modelo de lenguaje que se ejecuta localmente mediante Ollama.

El objetivo es aprender a conectar una aplicación Blazor con un servicio de inferencia de IA, comprender el flujo de comunicación y construir una base que pueda ampliarse con nuevas funcionalidades.

## Tecnologías utilizadas

| Tecnología | Función |
|---|---|
| C# | Lenguaje de programación principal |
| .NET 10 | Plataforma de desarrollo |
| ASP.NET Core Blazor | Interfaz web interactiva |
| Blazor Server | Interactividad ejecutada en el servidor |
| Ollama | Ejecución local de modelos de IA |
| Modelos LLM compatibles | Generación de respuestas |
| Visual Studio Code | Entorno de desarrollo |
| Git y GitHub | Control de versiones |

## Características principales

- Interfaz web de conversación desarrollada con Blazor.
- Integración con un modelo de inteligencia artificial local.
- Envío de preguntas y recepción de respuestas.
- Comunicación entre la aplicación .NET y Ollama.
- Arquitectura que permite ampliar el proyecto.
- Ejemplo práctico para aprender IA generativa utilizando C#.

## Requisitos previos

Antes de ejecutar el proyecto, asegúrate de tener instalados:

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Ollama](https://ollama.com/)
- [Git](https://git-scm.com/)

También necesitarás descargar un modelo de lenguaje compatible con Ollama y disponer de memoria suficiente para ejecutarlo.

## Instalación paso a paso

### 1. Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/Mi-IA-con-Blazor.git
```

### 2. Acceder al proyecto

```bash
cd Mi-IA-con-Blazor
```

### 3. Restaurar las dependencias

Desde la carpeta que contiene el archivo `.csproj`:

```bash
dotnet restore
```

### 4. Preparar Ollama

Instala Ollama y descarga un modelo compatible. Por ejemplo:

```bash
ollama pull llama3.2
```

Comprueba que el modelo funciona:

```bash
ollama run llama3.2
```

> **Importante:** el nombre del modelo configurado en la aplicación debe coincidir con uno de los modelos instalados en Ollama. Si el proyecto utiliza otro modelo, descarga y configura ese modelo.

### 5. Ejecutar la aplicación

En la carpeta del proyecto Blazor:

```bash
dotnet run
```

Abre en tu navegador la dirección local que aparezca en la terminal.

Para iniciar directamente el navegador, también puedes utilizar:

```bash
dotnet watch run
```

El navegador se abrirá automáticamente cuando el perfil de inicio del proyecto esté configurado para ello.

## ¿Cómo funciona?

El flujo general de la aplicación es el siguiente:

**Usuario → Interfaz Blazor → Aplicación .NET → Ollama → Modelo de IA → Respuesta en Blazor**

1. El usuario escribe una pregunta en la interfaz.
2. Blazor procesa la interacción.
3. La aplicación envía la solicitud al servicio local de Ollama.
4. El modelo de lenguaje genera una respuesta.
5. La aplicación muestra el resultado al usuario.

Este enfoque permite experimentar con inteligencia artificial generativa desde el ecosistema .NET, manteniendo la inferencia del modelo en el equipo local.

## Ventajas de utilizar IA local

**Privacidad:** las solicitudes pueden procesarse localmente, sin enviarse a un proveedor comercial de modelos en la nube.

**Control:** puedes seleccionar los modelos compatibles con Ollama y gestionar su ejecución.

**Aprendizaje:** permite comprender la integración de aplicaciones web con modelos de lenguaje.

**Sin coste por token de una API comercial:** la generación local no requiere pagar por cada solicitud, aunque sí consume recursos de tu equipo.

**Extensibilidad:** el proyecto puede evolucionar incorporando historial, instrucciones personalizadas, nuevos modelos y otras capacidades.

## Posibles mejoras futuras

Este proyecto constituye una base educativa que puede ampliarse con:

- Historial persistente de conversaciones.
- Selección dinámica de modelos.
- Respuestas en streaming.
- Soporte para documentos y archivos.
- Autenticación de usuarios.
- Integración con bases de datos.
- Despliegue en servidores propios.

Estas son ideas de evolución, no funcionalidades necesariamente implementadas en esta versión.

## Aprende más con render2web

En **render2web** encontrarás contenido educativo sobre inteligencia artificial, programación, desarrollo web y tecnologías modernas.

**Academia render2web:**  
https://academia.render2web.com/

**Sitio web:**  
https://render2web.com/

**Canal de YouTube:**  
https://www.youtube.com/@render2web

## Contribuciones

Las sugerencias, mejoras y contribuciones son bienvenidas.

Si deseas colaborar, puedes abrir un *Issue* para reportar problemas o proponer mejoras y enviar un *Pull Request* con tus cambios.

## Autor

**render2web — Desarrollo de software e Inteligencia Artificial**

Proyecto desarrollado con fines educativos para demostrar cómo construir aplicaciones web integradas con modelos de inteligencia artificial utilizando tecnologías modernas de Microsoft.

---

**Si este proyecto te resulta útil, considera darle una estrella en GitHub.**

*Aprende, experimenta y crea tus propias soluciones con inteligencia artificial.*