# Trabajo Grupal Evaluativo

### Integrantes

- Benitez, Dante
- Pedemonte, Ricardo
- Ruiz Díaz, Alejandro

### 1. Describir de que repositorio o sitio se extrajo el modelo.

El repositorio utilizado para la realización de este trabajo es parte de los repositorios expuestos por `tfjs-models`, en particular es el `face-landmarks-detection`

El modelo utiliza librerías comunes a varios modelos presentes en el repositorio de Tensorflow JS.

### 2. Describir el objetivo de la utilización del modelo.

El modelo reconoce las superficie del rostro humano y resalta los puntos de referencia. La implementación en el repositorio muestra estos puntos de manera gráfica a la par que la visualización de la cámara del dispositivo (ya sea la notebook o la cámara del móvil)

### 3. Datos particulares

El modelo es parte de Tensorflow, por tanto es propiedad de Google. El mismo utiliza otros modelos como ser, el de detección de rostros y una herramienta de manejo multimedia de nombre [MediaPipe](https://ai.google.dev/edge?hl=es-419#mediapipe), que forma parte de [Google AI Edge](https://ai.google.dev/edge).

La fecha exacta de creación de este repositorio no está descrita, pero el primer commit que contiene el modelo fue realizado el 12 de Octubre del 2020.

El modelo hace uso de distintas librerías, cada una con su correspondiente versión, que se describen a continuación:

- "@mediapipe/face_mesh": "~0.4.0",
- "@tensorflow-models/face-detection": "~1.0.0",
- "@tensorflow-models/face-landmarks-detection": "1.0.5",
- "@tensorflow/tfjs-backend-wasm": "^4.13.0",
- "@tensorflow/tfjs-backend-webgl": "^4.13.0",
- "@tensorflow/tfjs-converter": "^4.13.0",
- "@tensorflow/tfjs-core": "^4.13.0",
- "scatter-gl": "0.0.8"

4. Ejecutar paso a paso la implementación del modelo, describiendo que se realiza en cada paso.

Para utilizar el modelo se requiere ejecutar el siguiente comando en la raíz del proyecto:

```bash
npm i && npm run watch
```
Realizará la instalación de las dependencias requeridas para el funcionamiento del proyecto.


### Observaciones:

Tuvimos problemas en cuando a que el repositorio como tal, requería archivos que se encontraban en la raíz del repositorio de TJS.
La solución fue descargar todo el repositorio completo y obtener los archivos requeridos.

