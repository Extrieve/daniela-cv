# 👋 Sistema de Búsqueda de Empleo — Daniela Ciñera

Hola Dani. Este es **tu** asistente personal para encontrar trabajo en Lima.

No tienes que aprender a programar. No tienes que saber comandos raros. **Solo le pegás un link de una oferta y el asistente hace el resto.**

---

## 🤔 ¿Qué hace exactamente?

Cuando le compartís una oferta de trabajo, el asistente:

1. **Lee el aviso** (LinkedIn, practicas.pe, computrabajo, Bumeran, lo que sea)
2. **Lo compara contra tu CV** y te dice si vale la pena postular (puntaje 1-5)
3. **Te genera un CV personalizado** en PDF, ajustado a las palabras clave de esa oferta específica
4. **Te escribe una carta de presentación** lista para copiar y pegar
5. **Encuentra al recruiter en LinkedIn** y te redacta el mensaje para conectarte
6. **Lleva el control** de todo lo que aplicaste, en qué estado está, y cuándo te toca dar follow-up

Pensalo como tu **asistente de talento personal** que trabaja 24/7 y conoce tu CV de memoria.

---

## 🎯 Pensado específicamente para vos

El sistema ya conoce tu perfil:

- **Egresada USF** — Business Analytics and Information Systems, GPA 3.93/4.0, Dean's List
- **2 años de experiencia real** como Coordinadora Tecnológica en Smart Perú International
- **Stack técnico:** SQL/MySQL, Excel avanzado, Tableau, C#/.NET, Power BI (en desarrollo)
- **Trilingüe:** Español (nativo), Inglés (bilingüe), Portugués (B1)
- **Buscás:** Practicante / Junior en Data, BI, Analytics, Sistemas — en banca, seguros, retail multinacional o consultoras

Cuando le pegás una oferta, ya tiene todo este contexto cargado. No tenés que explicarle quién sos cada vez.

---

## 🚀 Cómo arrancar (15 minutos, una sola vez)

### Paso 1 — Instalá Claude Desktop

1. Andá a **https://claude.ai/download**
2. Descargá Claude para Mac o Windows (lo que tengas)
3. Instalalo como cualquier programa
4. Iniciá sesión con tu cuenta de Claude (o creá una gratis)

### Paso 2 — Descargá este proyecto

1. En la página de GitHub de este repo, hacé click en el botón verde **"Code"**
2. Elegí **"Download ZIP"**
3. Descomprimí el ZIP en `Documentos\career-ops-daniela` (o donde te acuerdes)

### Paso 3 — Abrí el proyecto en Claude

1. Abrí Claude Desktop
2. **Arrastrá la carpeta** `career-ops-daniela` a la ventana de Claude
   - O usá: **Archivo → Abrir Carpeta** y elegí `career-ops-daniela`
3. Listo. Claude ya tiene cargado todo tu contexto.

### Paso 4 — Saludá al asistente

Escribile algo simple como:

> **Tú:** Hola, soy Daniela. ¿Estás listo para ayudarme con la búsqueda de empleo?

El asistente te confirma que tu perfil está cargado y te muestra qué podés hacer.

---

## 💬 Cómo usarlo todos los días

### 📋 Caso 1 — Te encontraste una oferta

**Pegale el link.** Así de simple:

> **Tú:** https://pe.linkedin.com/jobs/view/practicante-data-analytics-...

El asistente te responde con:
- ✅ Score (1-5) — qué tan buen match es
- ✅ Si la oferta sigue activa o ya cerró
- ✅ Tu CV personalizado en PDF (te dice dónde quedó)
- ✅ Una carta de presentación lista para copiar
- ✅ Recomendación: "postulate hoy" / "esperá" / "no vale la pena"

### 📋 Caso 2 — Tenés varias ofertas a la vez

Pegale todas juntas:

> **Tú:** Evaluáme estas:
> 1. https://link1...
> 2. https://link2...
> 3. https://link3...

Las procesa en paralelo y te las ranquea.

### 📋 Caso 3 — Querés que busque ofertas nuevas

> **Tú:** Buscá ofertas activas para mí esta semana

Hace un scan de LinkedIn, practicas.pe, Bumeran, Computrabajo e Indeed con tus palabras clave y te trae los mejores matches.

### 📋 Caso 4 — Querés ver tu progreso

> **Tú:** ¿Cuántas ofertas tengo en mi tracker?
>
> **Tú:** ¿Cuáles son las que tienen score más alto?
>
> **Tú:** ¿Hay alguna que necesite follow-up?

### 📋 Caso 5 — Te respondieron de una empresa

> **Tú:** BBVA me citó a entrevista el 15 de mayo

Actualiza el tracker y te ofrece prepararte para la entrevista (preguntas probables + respuestas usando tu experiencia real).

### 📋 Caso 6 — Querés escribirle a un recruiter

> **Tú:** Encontrá al reclutador de Scotiabank y armame un mensaje de LinkedIn

Busca en LinkedIn, identifica al recruiter, y te redacta un mensaje de máx 300 caracteres listo para enviar como solicitud de conexión.

### 📋 Caso 7 — Tenés una entrevista la próxima semana

> **Tú:** Tengo entrevista con Pacífico Seguros el viernes, prepárame

Te arma:
- Investigación de la empresa (qué hacen, números clave, cultura)
- Preguntas más probables que te van a hacer
- Respuestas STAR usando tus proyectos reales (Smart Perú, Hospital DB, KAT Manufacturing)
- Preguntas inteligentes que VOS le hagas a ellos

---

## 📂 Dónde está cada cosa

```
career-ops-daniela/
├── README.md                ← Este archivo
├── cv.md                    ← Tu CV maestro (editable — pedíle al agente que actualice)
├── output/
│   ├── *.pdf                ← Tus CVs personalizados (uno por empresa)
│   ├── cartas/              ← Cartas de presentación listas para copiar
│   ├── outreach/            ← Mensajes de LinkedIn para recruiters
│   └── LEEME.md             ← Índice friendly de qué archivo es qué
├── reports/                 ← Análisis detallado de cada oferta evaluada
└── data/
    └── applications.md      ← Tu tracker — la tabla de todo lo aplicado
```

**Para abrir un PDF:** doble clic.
**Para copiar una carta:** clic derecho → abrir con Bloc de Notas o Word.

---

## ⚡ Tips importantes

### 🟢 El asistente NUNCA postula sin tu OK

- Te genera la carta, prepara el CV, identifica al recruiter
- **Pero el botón final de "Enviar" o "Postular" lo hacés vos**
- Esto es a propósito: vos decidís cuándo es el momento

### 🟢 Te dice cuándo NO postular

- Si una oferta tiene score menor a 4/5, te lo dice directamente
- Tu tiempo vale, el del recruiter también — calidad sobre cantidad

### 🟢 Verifica que la oferta siga abierta

- Antes de gastar tiempo en una postulación, revisa si el aviso sigue vigente
- Muchas ofertas en Perú se cierran en días — el sistema lo detecta y te avisa

### 🟢 Aprende con vos

- Si decís "esta oferta no me interesa porque X", lo guarda para futuro
- Si te rechazan, podés pedirle análisis de patrones para mejorar targeting
- Mientras más conversás con él, mejor te conoce

---

## 📊 Tu estado actual (snapshot)

Al **25 de abril de 2026**, tu tracker tiene **20 ofertas evaluadas**. Las más urgentes:

| Acción | Empresa | Score | Cómo |
|--------|---------|-------|------|
| 🔴 **Email pendiente** | Grupo CREDCO | **4.6/5** | `output/outreach/012-credco-email.md` → enviar a `rrhh@grupocredco.com` |
| 🟡 LinkedIn outreach | Pacífico, BBVA, Credicorp Capital, Falabella, Alicorp, Pacasmayo, Interbank | varios | `output/outreach/*.md` |

Las demás (la mayoría) están marcadas como **Discarded** porque las convocatorias ya cerraron — pero los CVs y cartas quedan listos para reusar cuando reabran.

---

## 🆘 Preguntas Frecuentes

**¿Tengo que pagar algo?**
Claude tiene un plan gratuito. Si lo usás mucho, Claude Pro cuesta ~$20 USD/mes. Pero para uso normal el plan gratuito alcanza.

**¿Mi información personal está segura?**
Tu CV, teléfono y email están en este proyecto. Si lo subís a GitHub público, esos datos quedan visibles. **Recomendación:** mantenerlo como repo privado.

**¿Qué pasa si una oferta ya cerró?**
El sistema lo detecta y te avisa. Igual te puede preparar el CV y un mensaje de LinkedIn al recruiter para quedar en su radar para la próxima convocatoria.

**¿Puedo cambiar algo de mi CV?**
Sí — solo decile al asistente: *"Quiero agregar una certificación de Power BI a mi CV"* o *"Cambiá el resumen para enfatizar más SQL"* y lo edita.

**¿Cómo busca recruiters en LinkedIn?**
Hace búsquedas web públicas (sin tu cuenta). Encuentra perfiles públicos que tienen "Talent Acquisition" o "Recruiter" o "Selección" en su título y trabajan en la empresa que buscás.

**¿Por qué algunas ofertas en Bumeran no se pueden leer?**
Bumeran usa una tecnología que oculta el contenido al asistente. Si te pasa, abrí la URL en tu navegador y copiá el texto del aviso — pegáselo al asistente y funciona igual.

**¿Cada cuánto debería buscar ofertas nuevas?**
Una vez por semana es suficiente. Las ofertas en Lima abren y cierran rápido — más frecuente solo agrega ruido.

**¿Qué hago si el asistente se traba?**
Decile: *"Algo no funcionó, ¿podés intentar de nuevo?"* — o cerrá Claude y abrílo de nuevo.

**¿Puedo usar esto para empleos en otros países?**
Sí — solo decile dónde querés buscar y ajusta el scan a esos portales. Por defecto está configurado para Lima, Perú.

---

## 🎯 Plan recomendado para esta semana

1. **Hoy:** Mandar el email a CREDCO (es tu mejor match — 4.6/5, sin formulario)
2. **Esta semana:** Conectar en LinkedIn con los 8 contactos que ya están identificados (mensajes en `output/outreach/`)
3. **Sábado:** Decirle al asistente "buscá ofertas nuevas para mí" y procesar lo que aparezca
4. **Cuando te respondan:** Avisar al asistente para que actualice el tracker y te ayude con la entrevista

---

## 💪 Cuando te frustres o tengas dudas

Decile al asistente exactamente lo que sentís. Algunos ejemplos:

> *No sé qué hacer ahora.* → Te da los próximos 3 pasos concretos.
>
> *Tengo miedo de que mi inglés en CV no sea lo que buscan.* → Analiza tu CV y te dice qué cambiar.
>
> *No me responde nadie y llevo 2 semanas.* → Analiza patrones y propone ajustes.
>
> *Me ofrecieron menos de lo esperado.* → Te ayuda con guion de negociación.
>
> *No sé si esta empresa es seria.* → Investiga y te da un reporte.

Este sistema es para vos — usalo como te haga sentido.

---

**Última actualización:** Abril 2026
**Construido sobre:** [career-ops](docs/CAREER-OPS-ORIGINAL-README.md) (sistema open source de santifer)
