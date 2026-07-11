<div align="center">
  <img src="./assets/banner.svg" alt="José de Jesús — Construyo y despliego software real y probado" width="100%"/>
</div>

<h1 align="center">José Enrique De Jesús Estévez</h1>
<p align="center"><b>Desarrollador Full-Stack</b> · Estudiante de Ingeniería de Software (INTEC) 🇩🇴</p>

<p align="center">
  <i>No hago ejercicios de clase: construyo productos que se usan y los llevo de la idea al <b>deploy</b>.</i>
</p>

<p align="center">
  <a href="https://dejesusestevez.netlify.app"><img src="https://img.shields.io/badge/🌐_Portafolio_interactivo-1A1712?style=for-the-badge" alt="Portafolio"/></a>
  <a href="https://www.linkedin.com/in/jose-enrique-de-jesus-estevez/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:joseenriquedejesusestevez@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/10_proyectos-EN_VIVO-2ea44f?style=flat-square" alt="10 en vivo"/>
  <img src="https://img.shields.io/badge/900%2B-pruebas_automatizadas-2b6087?style=flat-square" alt="900+ pruebas"/>
  <img src="https://img.shields.io/badge/3_sistemas-facturación_fiscal_DGII-14395e?style=flat-square" alt="DGII"/>
  <img src="https://img.shields.io/badge/TDD_·_CI%2FCD-de_la_idea_al_deploy-6b7280?style=flat-square" alt="TDD"/>
</p>

<p align="center">🔭 Abierto a <b>pasantía o rol junior de desarrollo</b> — Santo Domingo (presencial) o remoto LATAM.</p>

---

### 🌟 Míralo funcionando

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 🎨 [Portafolio interactivo →](https://dejesusestevez.netlify.app)
Cada proyecto **muda de piel** según su dominio y trae **demos que funcionan de verdad**: valida un 606/607/608, calcula prestaciones, anota un fiado. Bilingüe ES/EN.
`JavaScript` · `Canvas` · `data-driven`

</td>
<td width="50%" valign="top">

#### 📄 [e-CF, explicado →](https://facturard.netlify.app)
Una pieza *scrollytelling*: un comprobante de papel **cobra vida y se vuelve electrónico** mientras scrolleas, y la página migra de papel a azul digital.
`HTML/CSS/JS` · `0 librerías` · `scroll-driven`

</td>
</tr>
</table>

---

### 🚀 Proyectos de ingeniería

**⚡ DELCA — Plataforma para distribuidora eléctrica** &nbsp;·&nbsp; [![live](https://img.shields.io/badge/●_en_vivo-2ea44f?style=flat-square)](https://delca.onrender.com)
> Backend **Node.js/Fastify + PostgreSQL/PostGIS + Redis**. Facturación electrónica transaccional (NCF con **control de concurrencia**), telemetría de medidores y mapeo geoespacial de apagones. **~96 pruebas (Vitest)**, CI, 10 ADRs y OpenAPI. Con cliente móvil Kotlin/Android.
> `Node.js` · `TypeScript` · `Fastify` · `PostgreSQL` · `PostGIS` · `Redis` · `Docker`

**🏦 Banca Simón — Sistema de gestión de préstamos** &nbsp;·&nbsp; ![shipped](https://img.shields.io/badge/●_entregado_a_negocio_real-e8a317?style=flat-square)
> **Next.js 15 + TypeScript + Drizzle ORM** para un prestamista real en RD. **512 pruebas**, montos en centavos (sin floats), **auditoría append-only con cadena de hashes** (a prueba de manipulación), RBAC y pagarés/recibos en PDF. De extremo a extremo, con feedback del usuario final.
> `Next.js` · `TypeScript` · `Drizzle` · `Argon2` · `Vitest` · `Playwright`

**🏥 UAO — Facturación y contabilidad para clínica** &nbsp;·&nbsp; [![live](https://img.shields.io/badge/●_en_vivo-2ea44f?style=flat-square)](https://uao-facturacion.vercel.app)
> **Next.js 15 + PostgreSQL (Neon) + Better-Auth**. Emite NCF fiscales de la DGII, cuentas por cobrar, caja diaria y cierres mensuales con doble firma. **70 pruebas**, 16 módulos y RBAC de 4 roles.
> `Next.js` · `PostgreSQL` · `Better-Auth` · `RBAC`

<sub>🛠️ Además, herramientas propias: <b>hilo</b> — CLI en Node.js que reconstruye el contexto de un proyecto integrando la <b>API de Claude (Anthropic)</b> · 48 tests &nbsp;|&nbsp; <b>Chess Live</b> — análisis de ajedrez en vivo con <b>visión por computadora</b> (OpenCV/PySide6) + Stockfish · 40 tests.</sub>

---

### 🆕 Cerrando gaps esta semana — 5 repos nuevos (dev/IA + seguridad)

**🤖 DGII Responde — asistente fiscal RAG con citas verificables** &nbsp;·&nbsp; [![live](https://img.shields.io/badge/●_en_vivo-2ea44f?style=flat-square)](https://dgii-responde.vercel.app) [![repo](https://img.shields.io/badge/código-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/DeJesusEstevez/dgii-responde)
> Responde e-CF, NCF y formatos 606/607/608 **citando la norma real de la DGII** —o dice "no está en mis fuentes". **RAG** con embeddings locales ($0) + API de Claude + **eval harness** (72.7% hit-rate, medido). **27 pruebas**. _(El chat en vivo requiere una API key de Claude.)_
> `Next.js` · `TypeScript` · `Claude API` · `RAG` · `Transformers.js`

**🔌 HookLab — inspector de webhooks en tiempo real** &nbsp;·&nbsp; [![repo](https://img.shields.io/badge/código-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/DeJesusEstevez/hooklab)
> **GraphQL subscriptions** en vivo + verificación **HMAC** (Stripe/GitHub) timing-safe con anti-replay + endurecimiento GraphQL (límite de profundidad/complejidad). **43 pruebas**.
> `Fastify` · `Mercurius` · `graphql-ws` · `PostgreSQL` · `HMAC`

**🛡️ Guardian CI — DevSecOps con reglas Semgrep propias** &nbsp;·&nbsp; [![repo](https://img.shields.io/badge/código-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/DeJesusEstevez/guardian-ci)
> API deliberadamente vulnerable + **5 reglas SAST escritas a mano** (mapeadas a CWE/OWASP) + GitHub Actions → **SARIF en la pestaña Security**. `semgrep --test` 5/5. ⚠️ Código intencionalmente vulnerable (laboratorio educativo).
> `Semgrep` · `SARIF` · `GitHub Actions` · `gitleaks` · `OSV-Scanner`

**☁️ DocPipe — pipeline serverless event-driven en AWS** &nbsp;·&nbsp; [![repo](https://img.shields.io/badge/código-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/DeJesusEstevez/docpipe)
> S3 → Lambda → DynamoDB → SNS con **infraestructura como código (AWS SAM)**; extrae RNC/NCF/total/fecha de facturas RD. **33 pruebas**, CI en verde. _(Deploy requiere cuenta AWS.)_
> `AWS SAM` · `Lambda` · `S3` · `DynamoDB` · `SNS` · `TypeScript`

**📡 Radar AppSec RD — escáner pasivo de postura web** &nbsp;·&nbsp; [![live](https://img.shields.io/badge/●_en_vivo-2ea44f?style=flat-square)](https://radar-appsec-rd.vercel.app) [![repo](https://img.shields.io/badge/código-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/DeJesusEstevez/radar-appsec-rd)
> Califica **A–F** los headers, cookies y TLS de cualquier URL, con **defensa anti-SSRF** (OWASP A10) e informe agregado de sitios .do. Solo inspección pasiva. **30 pruebas**.
> `Next.js` · `TypeScript` · `SSRF defense` · `Node tls`

---

### 📦 Productos en vivo (República Dominicana)

<table width="100%">
<tr><th align="left">Producto</th><th align="left">Qué resuelve</th><th align="center">Abrir</th></tr>
<tr><td><b>Contáfacil</b></td><td>Valida tus formatos 606/607/608 antes de subirlos a la DGII</td><td align="center"><a href="https://validadordgii.netlify.app">▸ en vivo</a></td></tr>
<tr><td><b>¿Cuánto Me Toca?</b></td><td>Calcula tu liquidación laboral (Ley 16-92)</td><td align="center"><a href="https://prestacionesrd.netlify.app">▸ en vivo</a></td></tr>
<tr><td><b>FiaoYa</b></td><td>La libreta de fiados del colmado, que cuadra sola</td><td align="center"><a href="https://fiaoya.netlify.app">▸ en vivo</a></td></tr>
<tr><td><b>Aprueba RD</b></td><td>Practica el examen teórico de licencia (Ley 63-17)</td><td align="center"><a href="https://apruebard.netlify.app">▸ en vivo</a></td></tr>
<tr><td><b>CumpleFactura</b></td><td>Prepárate para la facturación electrónica e-CF (Ley 32-23)</td><td align="center"><a href="https://cumplefactura.netlify.app">▸ en vivo</a></td></tr>
</table>

---

### 🧩 Cómo trabajo

- 🧪 **Pruebo lo que construyo** — 700+ pruebas automatizadas (Vitest, Playwright, pytest) y TDD; no doy nada por terminado sin evidencia de que funciona.
- 🚢 **De la idea al deploy** — arquitectura por capas, CI/CD, contenedores y despliegue real (no solo prototipos).
- 🔒 **Seguridad aplicada desde el diseño** — Argon2, HMAC, JWT endurecido, validación estricta, RBAC y auditoría a prueba de manipulación.
- 📝 **Documento decisiones** — ADRs y OpenAPI para que el "por qué" quede claro.
- 🤖 **IA aplicada** — integración con la API de Claude (Anthropic) y uso diario de herramientas de desarrollo con IA.

---

### 🧰 Tecnologías

**Lenguajes**
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

**Frontend & Móvil**
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
</p>

**Backend & Datos**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
</p>

**DevOps & Herramientas**
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white"/>
</p>

---

### 🌱 Aprendiendo ahora
`Cloud en producción a escala (AWS/GCP)` · `Kubernetes` · `Inglés técnico`
<sub>✅ Recién cerrados con proyectos reales: <b>GraphQL en tiempo real</b> (HookLab) · <b>RAG con eval harness</b> (DGII Responde) · <b>SAST/DevSecOps</b> (Guardian CI) · <b>serverless en AWS</b> (DocPipe) · <b>AppSec defensiva</b> (Radar AppSec RD).</sub>

### 📊 GitHub en números
<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=DeJesusEstevez&show_icons=true&hide_border=true&include_all_commits=true" alt="Estadísticas de GitHub de José"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DeJesusEstevez&layout=compact&hide_border=true&langs_count=8" alt="Lenguajes más usados"/>
</p>

---

<div align="center">
  <a href="https://dejesusestevez.netlify.app"><b>🌐 Portafolio</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/jose-enrique-de-jesus-estevez/"><b>💼 LinkedIn</b></a> &nbsp;·&nbsp;
  <a href="mailto:joseenriquedejesusestevez@gmail.com"><b>✉️ Email</b></a>
  <br/><br/>
  <sub>🎓 Ingeniería de Software · Instituto Tecnológico de Santo Domingo (INTEC) · Certificación HCIA-AI V3.5 (Huawei)</sub>
</div>
