# CONTEXT · Estado del proyecto y guía para continuar

> Documento vivo. Pensado para retomar el trabajo desde cualquier máquina o sesión nueva con todo el contexto.

## 1. Misión del proyecto

Programa de **1 hora** llamado **"¿Muere el patrón dólar?"** — presentación para Neura. Tesis central:

> Tres tendencias en paralelo: (1) competencia de monedas estatales en curso, (2) el dólar pierde fuerza relativa y se defiende con SWIFT + poder militar, (3) activos neutrales (oro físico, Bitcoin digital) capturan demanda de hedge porque son inconfiscables, libres y con oferta verificable.

Tono: **analítico, datos duros, sin moralizar**. La presentación responde la pregunta "¿muere el patrón dólar?" con tres pilares.

## 2. Estructura de archivos

```
neura-yayi/
├── index.html                    # Landing con accesos a ambas presentaciones
├── presentacion-neura.html       # Deck para vivo · 20 slides
├── presentacion-extendida.html   # Deck preparación · 35 slides (con notas)
├── imagenes/
│   └── fiat.png                  # Mapa-mundi norte/sur usado en slide 6
├── CONTEXT.md                    # Este archivo
├── README.md                     # Resumen + atajos de teclado
├── MACHETE.md                    # Versión extendida narrativa (texto)
├── PROGRAMA_1H.md                # Escaleta de 60 minutos
├── SLIDE_STORYBOARD.md           # Storyboard visual base
└── SOURCES.md                    # Fuentes verificadas con cifras
```

## 3. Pilares (definitivos)

1. **Dólar / guerra** — Por qué el dólar manda y cómo sostiene la demanda por un token de exportación de déficit fiscal.
2. **BRICS / China** — Competencia de monedas estatales: CIPS, yuan, monedas locales, energía. Todas fiat, emisión infinita.
3. **Oro / Bitcoin / Activo neutralidad soberano** — Activos que no dependen de permiso; oro para Estados, Bitcoin para individuos y red digital.

Colores asociados (CSS vars):
- `--p1: #d7432f` (rojo) · Dólar y guerra
- `--p2: #2b66ff` (azul) · BRICS / China
- `--p3: #d7ad45` (dorado) · Oro / Bitcoin

## 4. Orden de slides de Neura (20 slides)

| # | Pilar | Slide |
|---|---|---|
| 1 | P0 | ¿Muere el patrón dólar? (apertura con dolar-mask CSS) |
| 2 | P1 | El dólar en 2000: pico histórico 71% (donut + leader lines) |
| 3 | P1 | El dólar todavía manda · 56,77% Q4 2025 (donut + leader lines) |
| 4 | P1 | USD cayendo: 71% → 56,77% (line chart trayectoria) |
| 5 | P1 | Top tenedores de dólares por continente (4 grupos: Asia, Europa, América, África) |
| 6 | P1 | Token de exportación de déficit fiscal (con fiat.png) |
| 7 | P1 | Déficit fiscal EE.UU. histórico 1980-2025 (line chart) |
| 8 | P1 | Estrecho de Ormuz: el cuello del sistema (tabla decisiones por país) |
| 9 | P1 | Sanciones: US$300B congelado |
| 10 | P2 | El Yuan como moneda global (1.93% reservas, 3% SWIFT) |
| 11 | P2 | Poder adquisitivo fiat 1971-2025 (line chart 7 monedas) |
| 12 | P2 | Yuan + CIPS + petroyuan |
| 13 | P3 | Oro: % de las reservas globales (~20%) |
| 14 | P2 | BRICS+: países y capital previsto (NDB $100B, CRA $100B) |
| 15 | P3 | Oro: bancos centrales compran (+1.000t/año) |
| 16 | P3 | Oferta histórica: oro vs Bitcoin (vsgrid comparativo) |
| 17 | P3 | Bitcoin: red digital sin permiso (21M cap, ~20M minado) |
| 18 | P3 | Empresas con Bitcoin en treasury (Strategy ~818K) |
| 19 | P3 | Estados y ETFs con Bitcoin (incluye China ~190K) |
| 20 | P3 | Síntesis: tres tendencias en paralelo |

**Nota técnica:** orden no-monotónico en posición 14 (BRICS · P2) entre Oro % reservas (P3 · 13) y Oro: bancos centrales (P3 · 15). Intencional — el usuario lo pidió así.

## 5. Datos duros verificados (snapshot mayo 2026)

### Pilar 1 · Dólar
- **USD share reservas:** 56,77% (IMF COFER Q4 2025) · era 71% en 2000
- **Composición FX globales:** USD 56,77% · EUR 21% · JPY 5,5% · GBP 5% · CNY 2,2% · Otras 9,53%
- **Total global reservas:** ~US$13.0T (Q3 2025, excl. oro)
- **Top tenedores reservas (TOP):** China $3.2T · Japón $1.25T · Suiza $895B · India $680B · Rusia $600B (~$300B congelados) · Taiwán $580B · Arabia S. $430B · HK $425B · Corea $415B · Singapur $370B
- **Treasuries TIC (top):** Japón $1.06T · China $770B · Reino Unido $725B
- **Deuda EE.UU.:** US$37.6T+ FY2025 (+$2.2T en el año)
- **Déficit FY2025:** US$1.8T (5,9% PIB)
- **Intereses anuales:** US$970B (superó gasto militar)
- **Deuda/PIB:** 99,8% FY2025 (era 35% en 1980)
- **Estrecho de Ormuz:** ~20% petróleo mundial · ~21M bbl/día · 33 km

### Pilar 2 · BRICS / China
- **BRICS+ miembros plenos (10):** Brasil, Rusia, India, China, Sudáfrica (2010) + Egipto, Etiopía, Irán, EAU (2024) + Indonesia (2025)
- **Socios BRICS:** Bielorrusia, Bolivia, Cuba, Kazajistán, Tailandia, Malasia, Nigeria, Uganda, Uzbekistán
- **PIB BRICS+ nominal:** ~28% global · **PPP:** ~36% (mayor que G7)
- **Población:** ~45% del mundo
- **NDB (Banco BRICS):** US$100B autorizados · US$50B suscritos · sede Shanghái (2014)
- **CRA (reserva contingente):** US$100B (China $41B · Brasil/India/Rusia $18B c/u · SA $5B)
- **Yuan share reservas:** 1,93% Q3 2025 (pico fue 2,83% en 2022)
- **Yuan SWIFT:** ~3% (jun-2025) vs USD 48%, EUR 24%
- **CIPS volumen anual:** ~¥175T (~US$24.5T en 2024, +43% YoY)
- **CIPS vs CHIPS:** ~$60B/día vs ~$1.800B/día (30× menor)
- **CIPS participantes:** 176 directos + 1.467 indirectos en 119 países (sep-2025)
- **Pipelines bypass Ormuz:** Saudi East-West (~5 Mb/d a Yanbu/Mar Rojo) + UAE Habshan-Fujairah (~1.8 Mb/d a Fujairah/Golfo de Omán) = ~6.8 Mb/d (32% del flujo de Ormuz)
- **Poder adquisitivo desde 1971:** CHF 35 (mejor) · JPY 28 · EUR/DEM 19 · CNY 15 · USD 14 · GBP 7 · INR 3 (ARS ≈ 0)

### Pilar 3 · Oro
- **Oro % reservas globales:** ~20% (cruzó Treasuries 2024-25, primera vez en 30 años)
- **Compras netas bancos centrales:** 2022 1.082t (récord) · 2023 1.037t · 2024 1.045t
- **% oro por país:** Portugal 76% · Alemania 75% · EE.UU. 73% · Italia/Francia 70% · Rusia 30% · Polonia 28% (target 30%) · India 12% · China 7% · Brasil 6% · Japón 5%
- **76%** de CBs encuestados esperan mayor share de oro en 5 años (WGC Survey 2025)
- **Stock total minado:** ~213.000 t · **Crecimiento anual:** ~1,5-2% · **Stock-to-flow:** ~62

### Pilar 3 · Bitcoin
- **Cap absoluto:** 21M BTC
- **En circulación (may-2026):** ~20.01M (~95,3%) · cruzó 20M en mar-2026
- **Inflación anual post-halving:** ~0,82% (cae a la mitad cada 4 años)
- **Hashrate:** ~870-900 EH/s (rango 899-958 EH/s reciente)
- **Block height:** ~949.104
- **Block reward:** 3,125 BTC · próximo halving abr-2028
- **Stock-to-flow:** ~117 (superó al oro tras halving abr-2024)

### Holders Bitcoin (verificado SEC + bitcointreasuries.net + bitbo.io, 12-may-2026)

**Empresas (treasuries corporativos · top):**
- Strategy (MSTR · ex-MicroStrategy): **818.869 BTC** (target 1M EOY26)
- Twenty One Capital (XXI): 43.514 BTC
- Metaplanet (3350.T · Japón): 40.177 BTC
- MARA Holdings (minero): 35.303 BTC
- Bullish (BLSH): 24.300 BTC
- Tesla: 11.500 BTC
- Block (Jack Dorsey): 8.500 BTC
- Otros: GameStop, Semler, KULR, Riot, CleanSpark, Coinbase, Hut 8
- **Total empresas públicas: ~1.188M BTC (~5,6% del supply)**

**ETFs spot (US, enero 2024):**
- BlackRock IBIT: ~775K BTC (~$50B AUM) — **NO es treasury corporativo, es ETF**
- Fidelity FBTC: ~471K BTC (~$31B AUM)
- Total 11 ETFs spot: ~$120B+ AUM · ~1.1M BTC

**Estados / soberanos:**
- EE.UU. Strategic Bitcoin Reserve: ~325K BTC (EO Trump mar-2025)
- Bulgaria: ~213K BTC (seizure 2017, debatido)
- China: ~190K BTC (decomisos PlusToken etc., SIN marco formal de reserva)
- Reino Unido: ~61K BTC (confiscado)
- Bhután: ~13K BTC (minería estatal hidroeléctrica)
- El Salvador: ~6K+ BTC (1 BTC/día desde 2021)
- Pakistán: anunció Strategic Bitcoin Reserve 2026
- Mubadala (UAE) · Wisconsin Investment Board: vía ETF (13F)

## 6. Stack técnico

- HTML + CSS + JS vanilla (sin frameworks)
- SVG inline para todos los gráficos
- Sin dependencias externas
- Navbar con índice expandible (`#menu`)
- Atajos de teclado: `←`/`→` navegar · `1`/`2`/`3` saltar a pilar · `M` menú · `Esc` cerrar · `F` pantalla completa · `Home`/`End` extremos

### Componentes CSS clave
- `.chart` — barras agrupadas por continente
- `.facts` — grilla de data points 2×3 con número grande + label + fuente
- `.vsgrid` — comparativa de 2 columnas (ej: oro vs Bitcoin)
- `.buyers` — tabla de filas (país/empresa + valor)
- `.dolar-mask` — gradiente verde billete USD para text-clip
- Donut chart con `stroke-dasharray` + `transform: rotate(-90)` para empezar arriba

## 7. Cambios pendientes / TODOs

- [ ] Considerar también actualizar todas las menciones de "Q3 2025" remanentes en slides 5, 10, 11 a "Q4 2025" si quedan
- [ ] Refrescar holdings BTC móviles antes de grabar (Strategy puede tener más, ETF AUM cambia diariamente)
- [ ] Verificar última lectura de China gold reserves (PBOC reporta con rezago)
- [ ] Posible slide adicional: stablecoins en Pilar 3 (USDC/USDT como "USD digital privado" — otro ángulo del dólar)

## 8. Cómo continuar este proyecto desde otra máquina

1. **Clonar:** `git clone https://github.com/claudiomolt/neura-yayi.git`
2. **Abrir en navegador:** abrir `index.html` directamente — no necesita build
3. **Editar contenido:** abrir cualquier `.html` y editar las slides directamente
4. **Verificar:** después de cambios estructurales, verificar conteo de slides con `grep -c 'class="slide' presentacion-*.html`
5. **Refrescar datos:** usar las fuentes en `SOURCES.md` para validar cifras antes de grabar

### Convenciones de edición

- **Cada slide** es un `<section class="slide" data-p="N" data-title="...">` donde N=0..3 (pilar)
- **Orden monotónico** por pilar es lo "limpio" pero no obligatorio (ej: BRICS slide 14 rompe orden intencionalmente)
- **Headlines** usan `<h2 class="headline">` · **subs** usan `<p class="sub">`
- **Notas para vivo** (solo en Extendida): `<div class="notes">`
- **Fuentes** al pie de cada slide: `<div class="source">`
- **Watermarks (`bigword`)** ya removidos de la mayoría — solo quedan donde aportan diseño

### Convenciones de datos

- Cifras grandes con punto separador de miles: `US$36T+`, `US$1.8T`, `~$190K BTC`
- Decimales con coma (convención hispana): `56,77%`, `−14,23 puntos`
- Aproximaciones con `~` cuando son rangos o cifras móviles
- Siempre citar fuente: IMF COFER, WGC, CBO, SEC filings, etc.

## 9. Fuentes recurrentes (URLs útiles)

- IMF COFER: https://data.imf.org/en/datasets/IMF.STA:COFER
- US Treasury FiscalData: https://fiscaldata.treasury.gov
- CBO Budget: https://www.cbo.gov/topics/budget
- World Gold Council: https://www.gold.org/goldhub/data
- SWIFT RMB Tracker: https://www.swift.com/our-solutions/compliance-and-shared-services/business-intelligence/rmb-tracker
- CIPS: https://www.cips.com.cn
- Bitcoin Treasuries: https://bitcointreasuries.net · https://bitbo.io/treasuries
- CoinWarz hashrate: https://www.coinwarz.com/mining/bitcoin/hashrate-chart
- Bitnodes (nodos): https://bitnodes.io
- Chainalysis Strategic Reserves: https://www.chainalysis.com/blog/bitcoin-strategic-reserves
- Federal Reserve (M2, Treasuries): https://www.federalreserve.gov/data.htm

## 10. Tono y framing — recordatorios

- **No moralizar.** Datos duros, análisis, no juicios.
- **No usar:** "Bitcoin o muerte", "honestidad intelectual", "no es inevitable" (lenguaje normativo).
- **Sí usar:** "asimetrías", "variables a monitorear", "tendencia secular", "competencia de monedas".
- **Pregunta marco:** ¿muere el patrón dólar? — la respuesta es "pierde fuerza relativa, no muere; aparecen alternativas neutrales".
- Audience target Argentina/LATAM: incluir referencias a ARS, Brasil, México, peso devaluación cuando agregue contexto.
