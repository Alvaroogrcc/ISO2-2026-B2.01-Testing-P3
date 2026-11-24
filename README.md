# ISO2-2026-B2.01-Testing-P3
Una empresa de domótica agrícola requiere el desarrollo de una aplicación que genere recomendaciones sobre el ciclo de riego para invernaderos, en función de la humedad del suelo, la temperatura ambiente, la previsión meteorológica de lluvia y la franja horaria. Para ello, se considerarán las siguientes reglas:

- Si la humedad del suelo es inferior al 20%, la temperatura es superior a 25 ºC y no hay previsión de lluvia en las próximas 24 horas, la recomendación es activar el "Riego Intenso".
- Si la humedad del suelo está entre el 20% y el 40%, la temperatura es superior a 25 ºC y no hay previsión de lluvia, se activará el "Riego Ligero".
- Si la humedad del suelo es inferior al 40% pero existe previsión de lluvia inminente, el sistema emitirá la instrucción de "No Regar".
- Si la humedad del suelo es superior al 60% y la temperatura desciende por debajo de los 5 ºC, se debe activar el "Drenaje de Emergencia" para prevenir la congelación de las raíces.
- Si el sistema se encuentra en la franja horaria de máxima insolación (de 12:00 a 16:00), se debe posponer cualquier tipo de riego, a menos que la humedad sea inferior al 10%, en cuyo caso se activará el protocolo de "Riego Crítico"
