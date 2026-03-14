# Calculadora de Margenes - Canal Online Olivo

Herramienta para calcular la distribucion de ingresos y margenes en ventas online entre OlivoMarket, pasarela de pagos y comisiones de administracion/delivery.

## Demo en Vivo

Accede directamente: https://fabricioseidel.github.io/olivo-margen-calculadora/

## Caracteristicas

- Calculo automatico de IVA (debito y credito)
- Desglose de costos de productos (bruto y neto)
- Calculo de comision de pasarela de pagos
- Calculo de tu comision con retencion de boleta de honorarios
- Visualizacion grafica de distribucion de margenes
- Interfaz simple y responsiva
- Sin instalacion, funciona 100% en el navegador

## Uso Local

1. Descarga el archivo `index.html`
2. Haz doble clic para abrirlo en tu navegador
3. Listo! Ya puedes usar la calculadora

## Parametros Ajustables

- Ventas web totales (con IVA): Monto total recaudado
- IVA: Tasa de IVA (por defecto 0.19 = 19%)
- Costo productos / ventas: Ratio de costo (ej. 0.679)
- % pasarela: Comision de pasarela (ej. 0.025 = 2.5%)
- % tu comision: Tu comision por admin + delivery (ej. 0.125 = 12.5%)
- % retencion boleta: Retencion honorarios (2026 = 0.1525)

## Ejemplo de Uso

Con 2.000.000 CLP en ventas y 12.5% de comision:

- Ventas brutas: 2.000.000
- Tu comision bruta: 250.000
- Tu liquido (15.25% ret): ~211.875
- Utilidad OlivoMarket: ~239.500
- Pasarela (neto): ~50.000

## Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)
- Chart.js para graficos

## Autor

Desarrollado para OlivoMarket - Fabricio Seidel
