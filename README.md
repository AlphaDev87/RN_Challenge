# React Native Technical Test App

## Bienvenida 👋
¡Bienvenido a la prueba técnica! Este proyecto está diseñado para evaluar tus habilidades con React Native, TypeScript y las buenas prácticas de desarrollo. Asegúrate de leer detenidamente las instrucciones y requisitos antes de comenzar.

---

## Descripción del Proyecto
Esta aplicación debe cumplir con los siguientes objetivos:
- Construir una aplicación con React Native y TypeScript.
- Integrar al menos una API externa de tu elección.
- Implementar pantallas clave que incluyan funcionalidades solicitadas.
- Aplicar buenas prácticas de desarrollo, optimización de rendimiento, y patrones de arquitectura.

---

## Requisitos

### Tecnologías
- **React Native**: Usa el CLI para iniciar la aplicación.
- **TypeScript**: Es obligatorio para tipar tu código.

### Funcionalidades Requeridas
1. **Pantalla de Inicio**:
   - Breve descripción del propósito de la app.
   - Navegación hacia las demás pantallas.

2. **Pantalla con Datos Dinámicos**:
   - Muestra datos obtenidos desde una API externa de tu elección.
   - Implementa paginación y/o "lazy loading".
   - Cachea los datos para evitar solicitudes repetidas innecesarias.

3. **Pantalla de Detalles**:
   - Muestra información detallada de un elemento seleccionado desde la pantalla anterior.

4. **Pantalla de Configuración**:
   - Permite al usuario modificar preferencias que se guarden en el almacenamiento local del dispositivo (e.g., AsyncStorage).

### Parámetros de UX/UI
- Diseño simple y claro con buena jerarquía visual.
- Usa colores y tipografías que sigan un tema consistente.
- Puedes ayudarte de librerias de componentes y estilos.
- Botones y controles que sean intuitivos y accesibles.

### Requisitos Técnicos
- Usa **React Navigation** para la navegación.
- Maneja los estados globales/locales eficientemente haciendo uso de una store.
- Evita renders innecesarios implementando técnicas de optimización y componentes memorizados.
- Es importante tener una estructura de directorios y archivos bien organizada.
- Usa patrones de arquitectura limpia, separando la lógica de negocio de los componentes visuales.

---

## Instrucciones para Empezar

### Prerrequisitos
Antes de empezar, asegúrate de tener instaladas las herramientas necesarias:
1. **Node.js** (versión 16 o superior)
2. **React Native CLI**
3. **Android Studio** o **Xcode** configurados para emular la app en un dispositivo.

### Instalación
1. Clona este repositorio:
   ```bash
   git clone https://github.com/AlphaDev87/RN_Challenge.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd RN_Challenge
   ```

3. Instala las dependencias:
   ```bash
   yarn install
   ```

4. Inicia la aplicación en tu emulador o dispositivo:
   - Para Android:
     ```bash
     npx react-native run-android
     ```
   - Para iOS:
     ```bash
     npx react-native run-ios
     ```

---

## Criterios de Evaluación
Tu proyecto será evaluado en función de los siguientes puntos:

### Funcionalidad
- Cumple con los requisitos solicitados.
- Las pantallas funcionan correctamente y sin errores.

### Código
- Código limpio, bien organizado y comentado donde sea necesario.
- Uso correcto de TypeScript para tipado de datos.
- Estructura tu proyecto de forma clara y modular.

### Rendimiento
- Manejo eficiente del estado y renderizado.
- Optimización de la carga y uso de recursos.

### UI/UX
- Interfaz clara y fácil de usar.
- Implementación de temas y consistencia visual.

---

## Notas Finales
- Puedes usar cualquier API externa que prefieras.
- Incluye en tu entrega una breve descripción de las decisiones que tomaste y por qué.
- Si por alguna razon no logras correr este proyecto puede crear uno propio y compartir el repositorio.
- Este desafío no evalúa solo el resultado final, sino también el enfoque y la calidad del código.
- No olvides agregar tu toque personal y destacar tus fortalezas.

## Cuestionario
1. ¿Qué criterios consideraste para elegir la API externa utilizada?
2. ¿Qué estrategia implementaste para optimizar el rendimiento de la aplicación?
3. ¿Cómo estructuraste tu proyecto y por qué elegiste ese enfoque?
4. ¿Qué desafíos enfrentaste al implementar las funcionalidades solicitadas?
5. ¿Qué cambios realizarías si tuvieras más tiempo para trabajar en este proyecto?
6. ¿Cómo manejaste los errores en las llamadas a la API?

---

## Importante!
- El challenge tiene un tiempo máximo de **48 horas**.
- Una vez terminado, sube tu trabajo a una **rama aparte con tu nombre y apellido**.
- En una carpeta dentro del proyecto, incluye un **video muy corto y liviano** mostrando cómo ejecutas la app y sus funcionalidades.


¡Buena suerte y que disfrutes el desarrollo! 🚀
