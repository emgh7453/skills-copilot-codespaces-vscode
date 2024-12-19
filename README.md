<header>

<!--
  <<< Author notes: Course header >>>
  Lee <https://skills.github.com/quickstart> para más información sobre cómo construir cursos usando esta plantilla.
  Incluye una imagen de 1280×640, el nombre del curso en minúsculas y una descripción concisa en cursiva.
  En la configuración de tu repositorio: habilita el repositorio de plantilla, agrega tu imagen social de 1280×640, y activa la eliminación automática de ramas principales.
  Junto a "Acerca de", agrega descripción y etiquetas; desactiva versiones, paquetes y entornos.
  Agrega tu licencia de código abierto, GitHub usa la licencia MIT.
-->

# Programar con GitHub Copilot

_GitHub Copilot puede ayudarte a programar ofreciendo sugerencias al estilo autocompletar directamente en VS Code y Codespaces._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Elige 3-5 pasos para tu curso.
  El primer paso siempre es el más difícil, ¡así que elige algo fácil!
  Enlaza a docs.github.com para explicaciones más detalladas.
  ¡Anima a los usuarios a abrir nuevas pestañas para los pasos!
-->

## Paso 1: Aprovechar Codespaces con VS Code para Copilot

_Bienvenido a "Desarrolla con sugerencias de código impulsadas por IA usando GitHub Copilot y VS Code"! :wave:_

GitHub Copilot es un programador asistente de IA que te ayuda a escribir código más rápido y con menos trabajo. Extrae contexto de los comentarios y el código para sugerir líneas individuales y funciones completas al instante. GitHub Copilot está impulsado por OpenAI Codex, un modelo de lenguaje preentrenado generativo creado por OpenAI.

**Copilot funciona con muchos editores de código, incluyendo VS Code, Visual Studio, JetBrains IDE y Neovim.**

Además, GitHub Copilot está entrenado en todos los lenguajes que aparecen en los repositorios públicos. Para cada lenguaje, la calidad de las sugerencias que recibas puede depender del volumen y la diversidad de los datos de entrenamiento para ese lenguaje.

Usar Copilot dentro de un Codespace muestra lo fácil que es comenzar a trabajar con la suite de herramientas de [Colaboración en Programación](https://github.com/features#features-collaboration) de GitHub.

> **Nota**
> Este ejercicio de habilidades se centrará en aprovechar GitHub Codespace. Se recomienda que completes la habilidad de GitHub, [Codespaces](https://github.com/skills/code-with-codespaces), antes de continuar con este ejercicio.

### :keyboard: Actividad: Habilitar Copilot dentro de un Codespace

**Recomendamos abrir otra pestaña del navegador para realizar las siguientes actividades, de modo que puedas mantener estas instrucciones abiertas como referencia.**

Antes de abrir un codespace en un repositorio, puedes crear un contenedor de desarrollo y definir extensiones o configuraciones específicas que se usarán o instalarán en tu codespace. Vamos a crear este contenedor de desarrollo y agregar Copilot a la lista de extensiones.

1. Navega de nuevo a la **pestaña Code** de tu repositorio, haz clic en el botón desplegable **Add file**, y luego haz clic en `Crear nuevo archivo`.
1. Escribe o pega lo siguiente en el campo de texto vacío para nombrar tu archivo.
```
devcontainer/devcontainer.json
```
En el cuerpo del nuevo archivo **.devcontainer/devcontainer.json**, agrega el siguiente contenido:
```
{ // Nombre de esta configuración"name": "Codespace para Skills!", "customizations": { "vscode": { "extensions": [ "GitHub.copilot" ] } } }
```
1. Selecciona la opción para **Confirmar directamente en la rama `main`**, y luego haz clic en el botón **Confirmar nuevo archivo**.
1. Navega de nuevo a la página principal de tu repositorio haciendo clic en la pestaña **Code** ubicada en la parte superior izquierda de la pantalla.
1. Haz clic en el botón **Code** ubicado en el centro de la página.
1. Haz clic en la pestaña **Codespaces** en la caja que aparece.
1. Haz clic en el botón **Crear codespace en main**.

**Espera unos 2 minutos para que el codespace se inicie.**

1. Verifica que tu codespace esté funcionando. El navegador debería mostrar un editor web de VS Code y debería haber un terminal presente como el siguiente:
![Screen Shot 2023-03-09 at 9 09 07 AM](https://user-images.githubusercontent.com/26442605/224102962-d0222578-3f10-4566-856d-8d59f28fcf2e.png)
1. La extensión `copilot` debería aparecer en la lista de extensiones de VS Code. Haz clic en la pestaña de barra lateral de extensiones. Deberías ver lo siguiente:
![Screen Shot 2023-03-09 at 9 04 13 AM](https://user-images.githubusercontent.com/26442605/224102514-7d6d2f51-f435-401d-a529-7bae3ae3e511.png)

**Espera unos 60 segundos y luego actualiza la página de inicio de tu repositorio para el siguiente paso.**

<footer>

<!--
<<< Author notes: Footer >>>
Agrega un enlace para obtener soporte, página de estado de GitHub, código de conducta, enlace de licencia.
-->

---

Obtén ayuda: [Publica en nuestro foro de discusión](https://github.com/orgs/skills/discussions/categories/code-with-copilot) &bull; [Revisa la página de estado de GitHub](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Código de Conducta](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [Licencia MIT](https://gh.io/mit)

</footer>
