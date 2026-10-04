Programa de entrenamiento rápido diseñado para estudiantes con bases oxidadas de programación en C y sin experiencia previa en microcontroladores. El curso utiliza la capa de abstracción de hardware (STM32 HAL) y se enfoca en el desarrollo práctico sobre hardware real desde la primera sesión.

## Requisitos y Herramientas
Hardware
Tarjeta de desarrollo: Blue Pill (STM32F103C8T6) o tarjetas de la familia STM32 Nucleo.

* Depurador/Programador: ST-Link V2.

* Periféricos básicos: LEDs, botones, potenciómetros, servomotor, módulo UART-USB.

Software
* IDE recomendado: STM32CubeIDE o VS Code + extensión PlatformIO.

## Estructura del Repositorio

| Directorio / Carpeta | Descripción |
| :--- | :--- |
| `01_c_recap/` | Ejercicios de nivelación en C (bitwise, stdint, máscaras) |
| `02_gpio_blink/` | Salidas digitales (LED integrado / externamente conectado) |
| `03_gpio_button/` | Entradas digitales y manejo de debounce por software |
| `04_exti_interrupts/` | Interrupciones externas por hardware |
| `05_timer_base/` | Temporización fija por hardware sin bloqueo de CPU |
| `06_pwm_control/` | Modulación por ancho de pulso para LED y servomotores |
| `07_adc_read/` | Conversión analógica a digital |
| `08_uart_tx/` | Transmisión serie y redirección de `printf` para telemetría |
| `09_uart_rx/` | Recepción serie e interpretación de comandos |
| `10_integración/` | Control simultáneo con ADC, PWM y UART |
