## **RGB Colour Mixer – CS Field Guide**

https://www.csfieldguide.org.nz/en/interactives/rgb-mixer/

Una herramienta **online e interactiva** donde los chicos pueden ajustar los valores **R**, **G** y **B** con **deslizadores** y ver al instante el color resultante, además de mostrar el código decimal, hexadecimal y binario según se desea ([csfieldguide.org.nz][1]).

* Ideal para visualizar cómo cada componente influye en el color final.
* Muy intuitiva y compatible con cualquier navegador.

**otro ejemplo de RGB picker:** https://www.google.com/search?q=color+picker

1. Mostrar primero el **RGB Colour Mixer** o la app de Science Kiddo para que experimenten de forma interactiva.
2. Crear su propio proyecto en Scratch que:

   * Tome tres variables (R, G, B).
   * Calcule el color como `R*65536 + G*256 + B`.
   * Muestre el color visualmente cambiando el disfraz/fondo.

3. Finalmente usar esa paleta resultante para construir historias, juegos o animaciones personales.

---
## Mini-script Scratch para convertir RGB a Decimal y Hexadecimal

### ¿Qué hace?

* Toman valores `R`, `G` y `B` (0 a 255)
* Calculan el valor RGB decimal usando `R*65536 + G*256 + B`
* Muestran también su equivalente hexadecimal (usando una tabla)

### 📦 Proyecto base en Scratch:

🔗 **Scratch Link (Turbowarp)**:
[https://turbowarp.org/956143108/editor](https://turbowarp.org/956143108/editor)
(Hecho en TurboWarp para poder usar arrays y bloques personalizados. Compatible con Scratch estándar si se simplifica).

---

## Tabla RGB → Decimal + Hexadecimal (para usar en clase o en Scratch)

| R   | G   | B   | Decimal RGB | Hexadecimal |
| --- | --- | --- | ----------- | ----------- |
| 255 | 0   | 0   | 16711680    | `#FF0000`   |
| 0   | 255 | 0   | 65280       | `#00FF00`   |
| 0   | 0   | 255 | 255         | `#0000FF`   |
| 255 | 255 | 0   | 16776960    | `#FFFF00`   |
| 0   | 255 | 255 | 65535       | `#00FFFF`   |
| 255 | 0   | 255 | 16711935    | `#FF00FF`   |
| 128 | 128 | 128 | 8421504     | `#808080`   |
| 255 | 255 | 255 | 16777215    | `#FFFFFF`   |
| 0   | 0   | 0   | 0           | `#000000`   |


