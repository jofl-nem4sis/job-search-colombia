# job-scout Report — Fintechs Emergentes LATAM
**Date:** 2026-08-31
**Empresas nuevas esta semana:** 5 (Clara, Alfred, Welli, belo, Belvo)
**Total en watchlist:** 13
**Fuentes fallidas:** latamlist.com (EGRESS_BLOCKED), alfredpay.io (EGRESS_BLOCKED), boards-api.greenhouse.io (EGRESS_BLOCKED), job-boards.greenhouse.io (EGRESS_BLOCKED), api.lever.co (EGRESS_BLOCKED), startup.jobs (EGRESS_BLOCKED), belvo.com (EGRESS_BLOCKED), plata.careers (EGRESS_BLOCKED), reports.cuanticovp.com (EGRESS_BLOCKED), contxto.com (site: operator stripped), iupana.com (no direct search results), forbes.co (no direct search results)

---

## Con vacante activa

*Notas sobre confianza: todos los JDs fueron obtenidos vía snippets de búsqueda — las ATS directas (Greenhouse, Lever, Himalayas) están bloqueadas en este entorno. Los roles fueron cruzados en 2–3 fuentes para confirmar vigencia.*

---

### [96/100] Yuno — Head of Data Engineering

- **URL:** https://himalayas.app/companies/yuno/jobs/head-of-data-engineering *(confirmado activo — brenxor.com lista 3 vacantes de data abiertas; Himalayas, RemoteRocketship también activos)*
- **Funding stage:** Serie B ($45M, agosto 2026)
- **Signal:** hiring_velocity — 3 vacantes remotas de data confirmadas activas; Head of Data Engineering publicado enero 2026, aún abierto agosto 2026
- **Key requirements:**
  - Director-level; remote desde Colombia, Argentina, Irlanda o México
  - Stack exacto: Python, BigQuery, dbt, Airflow, Snowflake, AWS, GCP — data lakes, warehouses, pipelines end-to-end
  - Ownership del roadmap de data engineering a escala $100B en transacciones anuales
- **Fit notes:** Match técnico casi perfecto con el stack de Javier; el título "Head" con ownership estratégico claro y stack GCP/BigQuery/dbt/Airflow es el ideal. Único flag: el rol lleva ~7 meses publicado, lo que puede indicar proceso lento o barra alta — conviene priorizar contacto directo al Head of Engineering.

---

### [84/100] DEUNA — AI Engineering Lead *(upgrade desde objetivo_proactivo)*

- **URL:** https://www.theladders.com/job/ai-engineering-lead-deuna-san-francisco-ca_87055056 *(encontrado vía search snippets — plataforma directa Lever bloqueada)*
- **Funding stage:** sin dato
- **Signal:** hiring_velocity — AI Engineering Lead + Senior Data Engineer en México + Technical Account Manager Colombia; 4 posiciones remotas confirmadas en RemoteRocketship
- **Key requirements:**
  - Diseñar y hacer fine-tuning de modelos ML para optimización de pagos (authorization rate, dynamic routing, fraud)
  - Go y Python para inference layer; GCP + AWS para deployments cloud/on-prem híbridos
  - Arquitectura greenfield para ATHIA — definir tooling, standards y observability para 10M+ transacciones mensuales
- **Fit notes:** Rol de ownership arquitectónico genuino (+15 pts) con match fuerte en Python/GCP/AWS y data pipelines. Dos caveats honestos: (1) listing primario dice "San Francisco, CA" en Ladders — aunque DEUNA opera distribuido por LatAm/US/Europa, conviene confirmar elegibilidad Colombia-remote antes de aplicar; (2) Go es un requisito y no está en el stack de Javier. Score reducido a 84 por estas dos variables.

---

### [80/100] Cashea — Data Engineering Lead

- **URL:** https://to.indeed.com/aa4bn48x2jdw *(Indeed link de run anterior, verificado activo esta semana via RemoteRocketship)*
- **Funding stage:** Serie B ($100M en 2026)
- **Signal:** expansion_colombia — BNPL venezolano expandiéndose a Colombia, equipo de Data & AI en construcción
- **Key requirements:**
  - Lead de infraestructura de datos escalable con rol de mentoring al equipo
  - Contexto BNPL/crédito al consumo; Colombia como mercado de expansión activo
  - Departamento "Data & AI" — señal de intención estratégica
- **Fit notes:** El título es Lead (no Head o Director) y el contexto de ownership es ambiguo en los snippets disponibles (no se confirmó si define roadmap o ejecuta uno definido). El background financiero-crediticio de Javier encaja bien. JD completo no pudo ser fetcheado — confianza media.

---

### [78/100] Clara — Data Scientist Lead

- **URL:** https://job-boards.greenhouse.io/clara/jobs/5180829007 *(fetch directo bloqueado — confirmado vía búsqueda en startup.jobs y búsqueda directa de Greenhouse ID)*
- **Funding stage:** sin dato (>$204M raised en 10 rondas; $70M deuda estructurada para Colombia/México en 2026)
- **Signal:** both — $70M estructurado específicamente para expansión en Colombia (BBVA Spark + IFC + Covalto) + múltiples roles de data abiertos simultáneamente (Data Scientist Lead, Data Engineer, AI Business Operations Expert Bogotá híbrido)
- **Key requirements:**
  - 8+ años en Data Science / ML; liderazgo de equipos de 5–10 personas
  - Python, SQL, ML frameworks (TensorFlow, PyTorch, Scikit-learn); GCP/AWS/Azure
  - A/B testing, experimentación a escala fintech B2B LATAM
- **Fit notes:** Clara es el match más estratégico nuevoen la watchlist: top-3 emisor de tarjetas corporativas en Colombia con capital dedicado al mercado. El rol "Data Scientist Lead" es sólido (8+ años, gestión de equipos) pero orientado a ML/experimentación más que a data engineering/platform arquitectura — el core de Javier. El score refleja ese ángulo menos alineado: si emerge un rol de "Head of Data Engineering" o "Data Platform Lead", saltaría a 90+. También hay un "AI Business Operations Expert" híbrido en Bogotá (agosto 26, 2026) que podría ser de interés secundario.

---

## Objetivo proactivo (mercado oculto — sin vacante activa aún)

- **Alfred** — Señal: $15M Series A (enero 2026); operaciones activas en Colombia, México, Brasil, Argentina; +4M transacciones procesadas; expandiendo corredores Asia–LatAm
  Por qué encaja: B2B payments infrastructure en plena escala post-Serie A — el stack de data engineering para multi-region payment rails es exactamente el tipo de arquitectura que Javier ha construido en GCP/Python.
  Ángulo sugerido: contactar al CTO o Head of Engineering vía LinkedIn (alfredpay.io / linkedin.com/company/alfredpay)

- **Welli** — Señal: fintech colombiana de crédito de salud expandiéndose a Perú, luego México/Ecuador/Chile; $9M equity + $75M deuda; respaldada por Krealo (Credicorp)
  Por qué encaja: multi-country credit expansion con respaldo bancario regional (Credicorp) significa que la infraestructura de data de crédito debe escalar rápido — Javier's financial-sector data pipeline experience es la pieza que les falta para ese build-out.
  Ángulo sugerido: contactar al CEO / Head of Engineering vía LinkedIn (welli.co)

- **belo** — Señal: $14M Serie A (Tether, abril 2026); 3M+ usuarios; rentable 3 años consecutivos; entrando a Colombia + 5 países LATAM; contratando en engineering y operaciones
  Por qué encaja: wallet de stablecoins con expansión a 6 países LATAM necesita infraestructura de datos de pagos a escala regional; el stack GCP/Python de Javier y su experiencia en finanzas multinacionales alinea bien.
  Ángulo sugerido: contactar al VP Engineering vía LinkedIn (belo.com.ar)

- **Belvo** — Señal: plataforma de Open Finance API para LATAM con HQ en Bogotá; 150+ clientes enterprise; datos financieros como producto principal; equipo de data-integration contratando (jul 2026)
  Por qué encaja: los datos son el producto en Belvo — sus pipelines de API financiera necesitan liderazgo de data engineering senior; Javier's GCP/Python/financial-data experiencia es el exact core del product de Belvo.
  Ángulo sugerido: contactar al Head of Engineering o VP Data vía LinkedIn (belvo.com / linkedin.com/company/belvofinance)

- **Plata** (Banco Plata) — Señal: $405M raised, valuación $5B, licencia bancaria CNBV; Colombia con debit+savings products live; 161+ roles abiertos globalmente; Analytics Lead Colombia y Data Engineer Mid open — ninguno a nivel senior-leadership aún
  Por qué encaja: neobank de $5B valuación entrando a Colombia con ambición bancaria plena — cuando la plataforma de datos escale al ritmo de su capital, necesitarán un Head of Data Engineering. Momento ideal de contacto proactivo.
  Ángulo sugerido: contactar al Director of Engineering / CTO México vía LinkedIn (plata.careers)

- **Druo** — Señal: paytech colombiana $160M procesados; expansión a Chile y Brasil
  Ángulo sugerido: contactar al CTO vía LinkedIn

- **Trii** — Señal: investment platform 600K+ usuarios, break-even, expansión a México
  Ángulo sugerido: contactar al Head of Technology / CTO vía LinkedIn

- **Global66** — Señal: remesas en 60 países, $3.7B transacciones 2025, licencia bancaria 2026
  Ángulo sugerido: contactar al VP Engineering o Head of Data vía LinkedIn

- **Kravata** — Señal: crypto infra con partnership Mi Claro (millones de usuarios Claro)
  Ángulo sugerido: contactar al CTO vía LinkedIn

---

## Verdict

**Match más fuerte esta semana:** Yuno (96/100) sigue siendo el rol estrella — Head of Data Engineering con stack técnico casi perfecto (BigQuery, dbt, Airflow, GCP, Python), fully remote desde Colombia, y Serie B reciente. La novedad más importante es el **upgrade de DEUNA a con_vacante** (84/100): su rol de AI Engineering Lead para la plataforma ATHIA es arquitectura greenfield con ownership estratégico real, aunque hay que confirmar si Colombia-remote es elegible dado que el listing primario dice San Francisco. **Clara** es la empresa nueva más relevante de esta semana — top-3 corporativo en Colombia con $70M dedicados al mercado; el Data Scientist Lead es un rol sólido aunque más ML que data-platform.

**Evolución del watchlist:** la lista creció de 8 a 13 empresas (+5 nuevas: Clara, Alfred, Welli, belo, Belvo). Las 8 de la semana anterior pasaron a "vista". El total de con_vacante activas sube de 2 a 4 — Yuno, Cashea, DEUNA (nuevo) y Clara (nuevo). El pipeline de mercado oculto sigue siendo rico con 9 empresas en objetivo_proactivo, destacando Plata (Banco Plata) que con $5B de valuación y licencia bancaria en México es la más probable en generar un rol senior de data en los próximos meses.
