TABLA DE PREDICCIONES

Log A || undefined || La variable se usa antes de su asignación.
Log B || "Teclado Mecánico" || La variable ya está en uso.
Log C || 25 || Ámbito de función
Log D || 10 || Ámbito de bloque 
Log E || Error || TDZ Temporal Dead Zone
Log F || Error || TDZ Temporal Dead Zone


COMPROBACIÓN Y CONTRASTE DE RESULTADOS 

<img width="2435" height="293" alt="Captura de pantalla 2026-10-06 102124" src="https://github.com/user-attachments/assets/036e7182-7fb1-47bd-ab73-e5051b0230a8" />

RESULTADOS EN LA COMPROBACIÓN

Log A || undefined || 
Log B || "Teclado Mecánico" || 
Log C || 25 || 
Log D || 10 || 
Log E || Error || 
Log F || Error || 


CONCLUSIÓN CRÍTICA

Según los resultados de los apartados A, D Y E. El uso de var pone en peligro el código porque no lanza los errores,
en cambio let y const no avanzan si hay errores. Mejorando la legibilidad.







