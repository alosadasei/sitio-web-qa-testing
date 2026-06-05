Test 1: W3C Validator
    - Sin errores ni advertencias.
Test 2: WAVE
    - La extensión no se activa en la página solicitada.
Test 3: Responsive
    - 320px:
        * Sin scroll horizontal
        * Tarjetas en 1 columna
    - 768px:
        * Tarjetas en 2 columnas
    - 1440px:
        * Tarjetas en 3 columnas
Test 4: Contraste de color
    - Ratio: 17.74
Test 5: Navegación por teclado
    - Todos los elementos interactivos son alcanzables y visibles
Test 6: Lighthouse
    - Rendimiento: 0/1
        * Advertencias: (Las imágenes no tienen ancho ni alto explícitos)
    - Accesibilidad: 19/20
        * Errores: Los colores de fondo y de primer plano no tienen una relación de contraste adecuada
    - Prácticas recomendadas: 3/4
        * Errores: Muestra imágenes con una resolución baja
