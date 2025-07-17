# RETO: Partes del Cuerpo Humano :b

Este proyecto es una página interactiva donde el usuario puede hacer clic en diferentes partes de una imagen del cuerpo humano para obtener información sobre ellas.

## ¿Cómo Funciona?

- Se muestra una imagen del cuerpo humano (`cuerpa.png`).
- Con la etiqueta `<map>` y varias áreas `<area>`, se definen zonas clicables en la imagen.
- Cada zona redirige a una sección del mismo HTML con `id`, activando el estilo `:target` en CSS para mostrar un cuadro con información (`.info-box`).
- Solo se puede mostrar una parte del cuerpo a la vez. Al hacer clic en otra parte, se reemplaza la información.

## Partes del cuerpo incluidas

Al hacer clic en estas partes, aparece una breve informacion de:

- Cabeza
- Ojos
- Nariz
- Boca
- Orejas
- Torso
- Brazos
- Manos
- Piernas
- Rodillas
- Canillas
- Pies
