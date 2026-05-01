# Ejemplo Solemne II

- [link editable a p5js](https://editor.p5js.org/sofialuisa.xyz/sketches/NwXr2fEIj) con código y sketch corriendo. 
- [visor pantalla completa](https://editor.p5js.org/sofialuisa.xyz/full/NwXr2fEIj) de sketch.

![ejemplo](ejemplo.png)

## Por qué este proyecto cumple con los requisitos:

Es un sistema generativo que crea composiciones visuales tipo afiche inspiradas en la Bauhaus.  
No copia una estética, sino que traduce principios de diseño a un sistema computacional.

El sistema:
- Utiliza una **grilla como estructura base**
- Emplea **formas geométricas simples** (rectángulos, círculos y texto)
- Usa **color limitado e intencional** acorde al referente
- Responde de forma continua al mouse:
  - `mouseX` → controla columnas  
  - `mouseY` → controla filas  
- Genera variaciones en cada ejecución mediante **reglas y aleatoriedad**

## Sistema generativo

El comportamiento se construye a partir de:

- **Repetición** → bucles `for` recorren la grilla  
- **Reglas** → condicionales `if` definen qué dibujar  
- **Variación** → `random()` cambia el resultado en cada celda  
- **Transformación** → `map()` convierte input en estructura visual  
- Esto produce un sistema dinámico: mismo código, resultados distintos.


## Requisitos técnicos

El proyecto cumple con los mínimos requeridos:

- Variables propias (`columnas`, `filas`, etc.)  
- Condicionales (`if / else`)  
- Bucles (`for`)  
- Función propia (`dibujarGrilla`, `dibujarTexto`)  
- Uso de `map()` y `random()`  
- Input continuo (mouse)  
- Output visual dinámico y reactivo  


> ⚠️ **Importante**
>
> Este repositorio es solo para ejemplificar un proyecto de solemne II. Usar solo para referencia de **código, el funcionamiento del sistema y de diagrama de flujo**.
>
> **NO es un modelo de cómo deben hacer su README ni la estructura de su repositorio.**
>
> Úsenlo como referencia para:
> - entender la lógica del sistema  
> - ver cómo se relacionan input, proceso y output  
> - revisar un ejemplo de diagrama de flujo  
>
> Cada estudiante debe desarrollar su propio proyecto, documentación y organización del repositorio según las instrucciones de la Solemne II.
