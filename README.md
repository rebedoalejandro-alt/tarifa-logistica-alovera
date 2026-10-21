# Tarifa logística Alovera

Incremento a añadir al precio de cada producto (NAVID) que sale de la plataforma de Alovera hacia los centros de Aurgi y Motortown, para cubrir el coste del operador logístico gestionado por Reynasa. Escenario 2026, versión 2 (22-oct-2026).

- Página con buscador por NAVID: rebedoalejandro-alt.github.io/tarifa-logistica-alovera
- Excel descargable: `incremento_precio_por_navid_alovera.xlsx` (hojas Incremento por NAVID, Tarifa y Resumen por categoría; los importes de la hoja Tarifa son editables y recalculan todos los NAVID)

**Incremento €/ud = € tramo de tamaño + € tramo de lote + dm3 por unidad × € por dm3 de la banda de cobertura**

| Tramo de tamaño | €/ud | Tramo de lote | €/ud | Banda de cobertura | €/dm3 |
|---|---:|---|---:|---|---:|
| T1 Micro (≤0,5 dm3) | 0,01 | L1 Unitario | 4,25 | B0 Sana (≤13 sem.) | 0 |
| T2 Pequeño (0,5-2) | 0,07 | L2 Par | 2,24 | B1 Alta (13-26) | 0,0125 |
| T3 Mediano (2-6) | 0,19 | L3 Caja pequeña | 1,22 | B2 Muy alta (26-52) | 0,0413 |
| T4 Grande (6-15) | 0,54 | L4 Caja | 0,62 | B3 Excesiva (52-104) | 0,1177 |
| T5 Pesado (15-40) | 1,27 | L5 Caja grande | 0,33 | B4 Crítica (>104) | 0,4246 |
| T6 Neumático turismo (40-80) | 4,20 | L6 Granel | 0,04 | | |
| T7 Extra grande (>80) | 6,20 | | | | |

Los importes son una tarifa a cuenta: cada mes se regulariza frente a la factura real del operador.
