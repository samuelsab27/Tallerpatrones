# Tallerpatrones
En este taller pudimos aplicar los conceptos de la clase, los patrones y demas conceptos, aqui describo mas a detaller
# Parte I, 
Se aplicó el patrón Fábrica Abstracta para desacoplar la lógica principal de preparación de pizzas de las implementaciones concretas de amasado, moldeado y horneado. Se definieron interfaces para cada proceso y una fábrica abstracta que provee los objetos adecuados según el tipo de masa (delgada, gruesa, integral, etc.). Así, el flujo de preparación no cambia, y la adición de nuevas variantes de máquina solo requiere crear nuevas fábricas y productos concretos, sin modificar el núcleo del programa.

# Parte II 
Se refactorizó el juego aplicando Inversión de Dependencias y el patrón Fábrica Abstracta para desacoplar la lógica del juego del estilo visual. Se definieron abstracciones para el jugador, balas y fondo, junto con fábricas que crean las implementaciones concretas (sprites, vectoriales y vectoriales a color). Esto permitió cambiar completamente el estilo visual modificando únicamente la configuración de la fábrica, sin tocar la lógica central. Además, se implementó el nuevo estilo colorful-vectorial-style,

hecho junto a Julian Vasquez y Samuel Sabogal
