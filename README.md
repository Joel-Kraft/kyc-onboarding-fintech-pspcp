# Simulacro de Proceso de Onboarding KYC — Fintech PSPCP
**Portfolio AML/KYC · Ejercicio con datos simulados**

## Descripción

Este proyecto simula el proceso completo de onboarding KYC para FinPago S.A.S.,
una entidad ficticia que opera como Proveedor de Servicios de Pago que ofrece
Cuentas de Pago (PSPCP) bajo la Res. UIF N° 200/2024. Incluye un diagrama de
flujo de diez etapas con referencia normativa, tres fichas de perfiles de riesgo
simulados (bajo, medio y alto/PEP) y un documento comparativo que demuestra la
distinción entre el marco normativo aplicable a bancos y el aplicable a fintechs.
El objetivo es demostrar la capacidad de traducir un marco normativo en un proceso
operacional documentado y defendible ante un entrevistador técnico del sector.

---

## Distinción normativa clave

Este proyecto utiliza la Res. UIF N° 200/2024 como norma de referencia, no la
Res. UIF N° 14/2023. La distinción es intencional: la Res. 14/2023 aplica a
bancos y entidades financieras bajo la Ley 21.526, mientras que la Res. 200/2024
aplica específicamente a emisores, operadores y Proveedores de Servicios de Cobros
y/o Pagos. FinPago S.A.S. es un PSPCP, no una entidad financiera, por lo que su
marco normativo de referencia es la Res. 200/2024, vigente desde el 20 de
diciembre de 2024. 

---

## Marco normativo aplicado

| Norma | Qué regula en este proyecto | Enlace |
|---|---|---|
| Res. UIF N° 200/2024 | Marco general LA/FT/FP para PSPs; identificación, debida diligencia, diferimiento de 60 días, monedas virtuales | [Ver en BO](https://www.boletinoficial.gob.ar/detalleAviso/primera/318446/20241219) |
| Res. UIF N° 3/2026 | Cotejo de listas FPADM; plazo de 24 hs para congelamiento administrativo | [Ver en BO](https://www.boletinoficial.gob.ar/detalleAviso/primera/337241/20260108) |
| Res. UIF N° 233/2025 | Intercambio de información entre OCEs; verificación de datos del cliente | Ver en BO |
| BCRA Com. "A" 7462/2022 | Verificación de identidad, liveness check y trazabilidad para billeteras digitales | [Ver en BO](https://www.boletinoficial.gob.ar/detalleAviso/primera/258309/20220303) |
| Ley N° 25.246 (mod. Ley 27.739) | Art. 20, inc. 5: PSPs como sujetos obligados ante la UIF | Ver texto oficial |

---

## Contenido del repositorio

| Archivo | Descripción | Formato |
|---|---|---|
| `normativa/corpus_normativo_res200_2024.md` | Síntesis de los artículos clave de la Res. 200/2024 aplicados al proyecto | Markdown |
| `flujo/diagrama_onboarding_10_etapas.pdf` | Diagrama de flujo completo del proceso de onboarding KYC en diez etapas | PDF |
| `perfiles/perfiles_riesgo_kyc.pdf` | 3 Fichas KYC — Riesgo BAJO, MEDIO, ALTO — Diferimiento aplicable | PDF |
| `checklists/checklists_documentacion_por_nivel.xlsx` | Checklists de documentación requerida organizadas por nivel de riesgo | Excel |
| `analisis/banco_vs_fintech_comparativo.pdf` | Documento comparativo Banco vs. Fintech PSPCP con tabla normativa | PDF |
| `infografia/banco_vs_fintech.png` | Infografía comparativa | PNG |

---

## Cómo navegar el proyecto

1. **Empezá por el diagrama de flujo** (`flujo/`) — establece las diez etapas del
proceso de onboarding con su referencia normativa correspondiente.
2. **Revisá los perfiles** (`perfiles/`) — muestran cómo se aplica el proceso a
tres casos simulados de distinto nivel de riesgo, incluyendo un caso PEP con DDUE.
3. **Leé el análisis comparativo** (`analisis/`) — explica por qué la norma
aplicable a esta entidad es la Res. 200/2024 y no la Res. 14/2023, y detalla
las diferencias operativas entre ambos marcos normativos.

---

## Limitaciones

Todos los datos, nombres, entidades y situaciones descritas en este repositorio
son ficticios y fueron creados exclusivamente con fines educativos y de
demostración de competencias profesionales en el área de prevención de lavado de
activos y financiamiento del terrorismo. Los resultados no representan un proceso
real ni la política de cumplimiento de ninguna entidad del mercado. La metodología
aplicada es propia de este ejercicio y no ha sido validada por ninguna autoridad
regulatoria.

---

## Autor

**[Joel Kraft]** · [https://www.linkedin.com/in/kraft-joel-analytics/]
