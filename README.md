# Proyecto de Detección de Monedas y Automatización de Hardware

Este repositorio documenta el desarrollo de un sistema integrador que combina visión por computadora para la clasificación de monedas con la implementación física de sistemas electromecánicos de transporte y movilidad.

## Avances de Software: Visión Artificial
El código principal del repositorio ejecuta una interfaz de clasificación de monedas en tiempo real.
* **Identificación y Conteo:** El sistema reconoce múltiples denominaciones, contabiliza las unidades y calcula el valor monetario total acumulado (ej. $1.050).
* **Medición de Objetos:** El software aplica filtros de contorno para aislar las monedas del fondo, logrando medir su diámetro físico aproximado en milímetros (ej. 21.1 mm).

## Avances Físicos: Prototipos de Hardware
La fase práctica del proyecto incluye el ensamblaje de dos componentes mecánicos diseñados para complementar el sistema de software.
* **Banda Transportadora:** Mecanismo de desplazamiento construido con piezas estructurales y una cinta modular, accionado por un motorreductor. Está proyectado para automatizar el ingreso de las monedas al área de escaneo de la cámara.
* **Carro Robótico:** Vehículo móvil ensamblado sobre un chasis de acrílico con ruedas de tracción. Integra un sensor ultrasónico frontal, baterías y tarjetas de control electrónico para la gestión de los motores.

## Integración y Próximos Pasos
La siguiente fase del proyecto requiere la comunicación directa entre los componentes. El objetivo es que el programa de visión artificial controle el flujo de la banda transportadora y envíe instrucciones de navegación al carro robótico basándose en los datos del escaneo de las monedas.
