# Osciloscopio MSOC2002A

##  Uso típico paso a paso
1. Conectar la sonda correctamente (punta + masa).
2. Ajustar **VOLTS/DIV** y **TIME/DIV**.
3. Seleccionar acoplamiento adecuado (normalmente DC).
4. Configurar el **trigger** hasta estabilizar la señal.
5. Realizar las medidas necesarias.

## Conexión de las sondas
1. Conectar la **sonda al canal** (CH1, CH2…) del osciloscopio.
2. Conectar la **punta de la sonda** al punto de medida del circuito.
3. Conectar la **pinza de masa** al GND del circuito (referencia).
4. Seleccionar en el canal:
   - Atenuación de sonda: ×1 o ×10  
   - Acoplamiento: **DC / AC / GND**

📌 **Recomendado**: usar sondas en ×10 para reducir carga sobre el circuito.

## Ajuste vertical (eje Y–tensión)
Controla **cuántos voltios representa cada división vertical**.

-  **VOLTS/DIV**: ajusta la escala vertical.
-  **POSITION**: mueve la señal arriba o abajo.
-  **ACOPLAMIENTO**:
    - **DC**: muestra la señal completa (AC + DC).
    - **AC**: elimina el componente DC.
    - **GND**: referencia a 0 V.

👉 Ajustar hasta que la señal ocupe buena parte de la pantalla sin saturar.

## Ajuste horizontal (eje X–tiempo)
Controla **el tiempo representado por división horizontal**.

-  **TIME/DIV**: ajusta la base de tiempos.
-  **POSITION**: desplaza la señal en el tiempo.

👉 Ajustar para ver uno o varios periodos completos de la señal.

## Disparo (Trigger)
El disparo **estabiliza la señal** para que no se mueva en pantalla.

-  **SOURCE**: canal que dispara (CH1, CH2, EXT).
-  **SLOPE**: flanco de disparo  
    - Ascendente (↗)  
    - Descendente (↘)
- **LEVEL**: nivel de tensión donde se produce el disparo.
- **MODE**:
    - **AUTO**: siempre muestra señal.
    - **NORMAL**: solo muestra cuando hay disparo.
    - **SINGLE**: captura un solo evento.

👉 Ajustar el nivel hasta que la señal quede fija.

##  Medidas que se pueden realizar
-  **Tensión pico (Vp)**
-  **Tensión pico a pico (Vpp)**
-  **Tensión eficaz (RMS)**
-  **Periodo (T)**
-  **Frecuencia (f = 1/T)**
-  **Desfase entre señales** (usando dos canales)
-  **Forma de onda** (senoidal, cuadrada, triangular, ruido…)

## ⚠️ Precauciones de uso
-  **No superar la tensión máxima** de entrada del osciloscopio ni de la sonda.
-  **Conectar siempre la pinza de masa** de la sonda a un punto de referencia común.
-  Evitar medir directamente circuitos conectados a red sin aislamiento.
-  Comprobar si la sonda está en **×1 o ×10** y ajustar el osciloscopio en consecuencia.
-  Empezar siempre con escalas grandes y reducir progresivamente.

---
