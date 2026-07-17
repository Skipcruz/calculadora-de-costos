# Calculadora de Producción

App web portable para calcular costos de producción, precio de venta y lotes óptimos.

## Características

-   **5 métodos de cálculo:** Cost-Plus, Punto de Equilibrio, Margen de Contribución, ROI Objetivo, EOQ
-   **Materiales dinámicos:** Agrega todos los materiales que necesites, cada uno con su unidad (pieza, lote, lineal, BxH)
-   **Mano de obra flexible:** Por día, por actividad o por pieza
-   **Gastos indirectos:** Lista dinámica de conceptos con toggle incluir/no incluir
-   **Utilidad:** Por porcentaje o monto fijo
-   **Métodos inteligentes:** Solo se activan los cálculos posibles según los datos ingresados
-   **Sin dependencias:** HTML + CSS + JS puro. No requiere instalación.

## Cómo usar

1.  Abre `index.html` en cualquier navegador web
2.  Completa los datos de producción de arriba hacia abajo
3.  Los resultados se actualizan automáticamente

## Despliegue en GitHub Pages

1.  Crea un repositorio en GitHub (ej: `calculadora-produccion`)
2.  Sube los archivos:
    ```bash
    git clone https://github.com/tu-usuario/calculadora-produccion.git
    cd calculadora-produccion
    cp /ruta/a/index.html .
    cp /ruta/a/README.md .
    git add .
    git commit -m "Primera versión"
    git push
    ```
3.  Ve a **Settings → Pages** en GitHub
4.  En "Source", selecciona `main` y carpeta `/ (root)`
5.  Guarda. Tu app estará disponible en `https://tu-usuario.github.io/calculadora-produccion`

## Portabilidad

-   Abre `index.html` directo desde el disco → funciona
-   URL de GitHub Pages → funciona
-   Windows / Mac / Linux → funciona
-   Sin servidor, sin dependencias, sin instalación
