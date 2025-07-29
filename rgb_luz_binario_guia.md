# Actividad educativa: Luz, Colores RGB y Sistema Binario

Esta actividad integra conceptos de física de la luz con programación por bloques en Scratch, proponiendo un enfoque lúdico y visual para los estudiantes de 1er año de la Escuela Experimental PROA de Corral de Bustos-Ifflinger. Se trabaja la dispersión, reflexión y refracción de la luz, la mezcla aditiva RGB, y una introducción al sistema binario.

---

## 1. Introducción teórica y práctica con elementos reales

### Objetivos:

- Comprender los fenómenos ópticos de la **luz blanca**: reflexión, refracción y dispersión.
- Reconocer la composición de la luz blanca como suma de colores (modelo RGB).

### Breve explicación teórica:

La luz blanca está compuesta por muchos colores, como se puede observar al pasarla por un prisma o reflejarla sobre un CD. Los tres fenómenos principales que afectan su comportamiento son:

- **Reflexión**: cuando la luz rebota sobre una superficie, como un espejo.
- **Refracción**: cuando cambia de dirección al pasar de un medio a otro, como del aire al agua.
- **Dispersión**: cuando se separa en distintos colores, como al reflejarse en un CD o en gotas de agua que forman el arcoíris.

### Videos recomendados para introducir el tema:

1. **Reflexión, refracción y difracción de la luz** (2 min) – Explicación clara y visual con animaciones:\
   👉 [Ver en YouTube](https://www.youtube.com/watch?v=PFdowtChLCY)

2. **Reflexión y refracción - Ciencias para niños (Parte 2)** (3 min) – Pensado para público escolar:\
   👉 [Ver en YouTube](https://www.youtube.com/watch?v=6hhm552J_yI)

Estos videos pueden verse antes de los experimentos para activar conocimientos previos y fomentar la curiosidad.

### Actividades prácticas:

#### A. Dispersión con CD o DVD

- Material: CD y linterna o luz de celular.
- Procedimiento: Iluminar el CD en la oscuridad y observar los colores reflejados.
- Concepto: La superficie del CD actúa como una rejilla de difracción, separando la luz blanca en sus componentes.

#### B. Refracción con vaso de agua

- Material: Vaso de agua y lápiz.
- Procedimiento: Colocar el lápiz en el agua y observar cómo se ve “quebrado”.
- Concepto: El cambio de medio hace que la luz cambie de dirección.

#### C. Reflexión con espejo

- Material: Espejo pequeño y linterna.
- Procedimiento: Apuntar la luz al espejo en ángulo.
- Concepto: La luz rebota en superficies pulidas (reflexión especular).

---

## 2. Mezcla de colores con luces RGB en Scratch

### Objetivos:

- Comprender cómo los colores se crean digitalmente combinando rojo, verde y azul.
- Aplicar este conocimiento a través de programación por bloques.

### Proyecto: "Mezclador RGB"

#### Variables necesarias:

- `Rojo`, `Verde`, `Azul` (valores de 0 a 255).

#### Interfaz del proyecto:

- Tres botones (Rojo, Verde, Azul) para modificar cada componente.
- Fondo o sprite que cambia su color al combinar los valores RGB.

#### Lógica de bloques (resumen):

```scratch
cuando presiono bandera verde
  fijar Rojo a 0
  fijar Verde a 0
  fijar Azul a 0

por siempre
  establecer color del sprite a (Rojo, Verde, Azul)
```

Cada botón puede cambiar su componente así:

```scratch
al hacer clic en botón Rojo
  cambiar Rojo por 15 (hasta 255)
```

---

## 3. Introducción al sistema binario aplicado a colores

### Objetivos:

- Entender que las computadoras representan colores como tres números en binario.
- Traducir entre decimal y binario para los colores RGB.

#### Ejemplos:

| Color  | Decimal (R,G,B) | Binario R | Binario G | Binario B |
| ------ | --------------- | --------- | --------- | --------- |
| Rojo   | (255, 0, 0)     | 11111111  | 00000000  | 00000000  |
| Verde  | (0, 255, 0)     | 00000000  | 11111111  | 00000000  |
| Azul   | (0, 0, 255)     | 00000000  | 00000000  | 11111111  |
| Blanco | (255, 255, 255) | 11111111  | 11111111  | 11111111  |
| Negro  | (0, 0, 0)       | 00000000  | 00000000  | 00000000  |

#### Actividad:

- Mostrar el color y pedir que escriban su código binario.
- Dar códigos binarios y adivinar el color.

---

## 4. Juego final integrador (opcional)

### Nombre sugerido: "RGB Master"

### Mecánica:

- Aparece un color aleatorio.
- El jugador debe activar luces R, G y B correctas para reproducirlo.
- Nivel avanzado: ingresar los valores binarios para lograr el color correcto.

---

## 5. Recursos adicionales

- Video de referencia para construir el mezclador RGB en Scratch: [YouTube - How to use RGB Colors in Scratch](https://www.youtube.com/watch?v=kzdal8cSgf8)
- Sitio de programación por bloques: [https://scratch.mit.edu](https://scratch.mit.edu)

### 🌐 Sitios interactivos para explorar RGB

- **Simulador de mezcla RGB (PBS):** [https://www.pbslearningmedia.org/resource/buac20-68-sci-ps-rgbcoloradd/rgb-color-addition-simulation/](https://www.pbslearningmedia.org/resource/buac20-68-sci-ps-rgbcoloradd/rgb-color-addition-simulation/)

- **Paint** Paleta de colores: explorar! 

- **w3Schools** https://www.w3schools.com/colors/default.asp

### Preguntas para guiar la exploración:

- ¿Qué pasa si subís solo el rojo? ¿Y si agregás verde y azul?
- ¿Cómo se obtiene el blanco? ¿Y el negro?
- ¿Podés lograr un color como el amarillo? ¿Cómo?
- ¿Qué diferencia hay entre mezclar colores de luz y de pintura?

---

## 6. Archivos del proyecto

Se incluye en el repositorio:

- `mezclador_rgb.sb3`: proyecto Scratch con mezclador RGB.
- `guia_rgb.md`: esta guía en formato Markdown.
- `colores_binario_tabla.pdf`: tabla de colores y binario para imprimir (opcional).

---

> **Créditos:** Actividad elaborada para uso educativo, integrando ciencia y programación para el nivel primario/secundario. Inspirada en recursos de Scratch, MicroBlocks y experiencias de aula STEAM.

Escuela Experimental PROA - Corral de Bustos-Ifflinger.

