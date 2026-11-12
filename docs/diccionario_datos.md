
# Diccionario de datos

## Descripción

Base sintética de experiencias adversas en la infancia
y consumo de sustancias.

Unidad de análisis: participante ficticio.
Cada fila representa un registro simulado.

## Variables

| Variable | Descripción | Tipo | Valores |
|---|---|---|---|
| id | Identificador ficticio | Texto | P001, P002... |
| edad | Edad simulada en años | Entero | 18 a 65 |
| abuso_emocional | Adversidad emocional | Binaria | 0=No, 1=Sí |
| abuso_fisico | Adversidad física | Binaria | 0=No, 1=Sí |
| negligencia_emocional | Negligencia emocional | Binaria | 0=No, 1=Sí |
| negligencia_fisica | Negligencia física | Binaria | 0=No, 1=Sí |
| violencia_hogar | Exposición a violencia doméstica | Binaria | 0=No, 1=Sí |
| consumo_familiar | Consumo problemático en familiares | Binaria | 0=No, 1=Sí |
| salud_mental_familiar | Problemas de salud mental familiares | Binaria | 0=No, 1=Sí |
| separacion_familiar | Separación familiar | Binaria | 0=No, 1=Sí |
| total_eai | Suma de las ocho adversidades | Entero | 0 a 8 |
| consumo_sustancias | Consumo simulado en último año | Binaria | 0=No, 1=Sí |

## Reglas de codificación

- 0 representa ausencia de la característica.
- 1 representa presencia de la característica.
- total_eai se calcula sumando las ocho variables EAI.
- No se incluyen datos perdidos en esta versión.
- Todas las variables son ficticias.

## Advertencia

Las variables no constituyen por sí mismas
un instrumento psicométrico validado.
