---
layout: single
title: "Currículum virtual"
permalink: /curriculum-virtual/
classes: resume-page
author_profile: false
---

<style>
.resume-page {
  --accent: #1769aa;
  --accent-soft: #e8f1fb;
  --surface: #f7f9fc;
  --text-strong: #0f172a;
  --text-muted: #4b5563;
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
}

.resume-page section {
  background: #fff;
  border-radius: 14px;
  padding: 1.5rem 1.75rem;
  box-shadow: 0 18px 40px rgba(15, 23, 42, 0.08);
}

.resume-page .cv-hero {
  background: linear-gradient(135deg, #0f172a, #1e3a8a 65%, #2563eb);
  color: #fff;
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 1.5rem;
  align-items: center;
}

.resume-page .cv-hero h1 {
  margin: 0.25rem 0;
  font-size: clamp(1.9rem, 3vw, 2.5rem);
}

.resume-page .cv-hero p {
  color: rgba(255, 255, 255, 0.92);
}

.resume-page .eyebrow {
  text-transform: uppercase;
  letter-spacing: 0.08em;
  font-weight: 700;
  color: #bfdbfe;
  font-size: 0.85rem;
  margin: 0;
}

.resume-page .cv-hero__meta {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 0.75rem;
  margin: 1rem 0;
}

.resume-page .cv-pill {
  background: rgba(255, 255, 255, 0.1);
  color: #fff;
  padding: 0.75rem;
  border-radius: 10px;
  border: 1px solid rgba(255, 255, 255, 0.2);
  display: flex;
  flex-direction: column;
  gap: 0.15rem;
}

.resume-page .cv-hero__actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.resume-page .cv-button {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.7rem 1.1rem;
  border-radius: 12px;
  font-weight: 700;
  border: 1px solid transparent;
  transition: transform 150ms ease, box-shadow 150ms ease, background 150ms ease;
}

.resume-page .cv-button.primary {
  background: #fff;
  color: #0f172a;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.25);
}

.resume-page .cv-button.secondary {
  border-color: rgba(255, 255, 255, 0.5);
  color: #fff;
}

.resume-page .cv-button:hover {
  transform: translateY(-1px);
  box-shadow: 0 16px 32px rgba(15, 23, 42, 0.25);
}

.resume-page .cv-hero__media {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid rgba(255, 255, 255, 0.15);
  border-radius: 14px;
  padding: 1rem;
  text-align: center;
}

.resume-page .cv-hero__media img {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 14px;
  box-shadow: 0 16px 40px rgba(15, 23, 42, 0.25);
  border: 2px solid rgba(255, 255, 255, 0.35);
}

.resume-page h2 {
  margin-top: 0;
  color: var(--text-strong);
}

.resume-page .cv-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1rem;
}

.resume-page .cv-card {
  border: 1px solid #e5e7eb;
  border-radius: 12px;
  padding: 1rem;
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  background: var(--surface);
}

.resume-page .cv-card h3 {
  margin: 0;
  color: var(--text-strong);
}

.resume-page .cv-chip {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  background: var(--accent-soft);
  color: #0f172a;
  border-radius: 999px;
  padding: 0.35rem 0.7rem;
  font-weight: 600;
  font-size: 0.9rem;
}

.resume-page .cv-list {
  list-style: none;
  padding: 0;
  margin: 0.5rem 0 0;
  display: grid;
  gap: 0.35rem;
}

.resume-page .cv-list li {
  color: var(--text-muted);
}

.resume-page .cv-subgrid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 0.75rem;
}

.resume-page .cv-subcard {
  border: 1px solid #e5e7eb;
  padding: 0.85rem 1rem;
  border-radius: 12px;
  background: #fff;
}

.resume-page .cv-badges {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 0.75rem 0 0;
}

.resume-page .cv-badge {
  padding: 0.4rem 0.7rem;
  border-radius: 10px;
  background: var(--accent-soft);
  color: #0f172a;
  font-weight: 600;
  font-size: 0.9rem;
}

.resume-page .cv-highlight {
  background: linear-gradient(120deg, #f0f4ff, #e5f3ff);
  border: 1px solid #d8e8ff;
}

.resume-page .cv-footer {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  align-items: center;
  justify-content: space-between;
}

.resume-page .cv-footer p {
  margin: 0;
  color: var(--text-muted);
}

@media (max-width: 960px) {
  .resume-page .cv-hero {
    grid-template-columns: 1fr;
  }

  .resume-page .cv-hero__media {
    order: -1;
  }
}
</style>

<div class="resume-page">
  <section class="cv-hero">
    <div>
      <p class="eyebrow">Página personal</p>
      <h1>Gerardo Daniel López Montejo</h1>
      <p>
        Maestro en Planeación, profesor universitario y especialista en geotecnologías con 20 años de experiencia en
        docencia, investigación aplicada y diseño de experiencias digitales. Integro análisis espacial, desarrollo de
        software y formación académica para resolver desafíos de riesgo, territorio y educación.
      </p>
      <div class="cv-badges">
        <span class="cv-badge">Planeación estratégica</span>
        <span class="cv-badge">Sistemas de Información Geográfica</span>
        <span class="cv-badge">Experiencia de usuario y gamificación</span>
        <span class="cv-badge">Docencia y mentoría</span>
      </div>
      <div class="cv-hero__meta">
        <div class="cv-pill">
          <strong>20+ años</strong>
          <span>usando geotecnologías en academia y consultoría</span>
        </div>
        <div class="cv-pill">
          <strong>Profesor</strong>
          <span>Universidad Autónoma de Quintana Roo · Centro de Información Geográfica</span>
        </div>
        <div class="cv-pill">
          <strong>Comunidad</strong>
          <span>Kotlin Trainer Certified · GitHub Campus Advisor · GitKraken Ambassador</span>
        </div>
      </div>
      <div class="cv-hero__actions">
        <a class="cv-button primary" href="mailto:contacto@ejemplo.com">Contáctame</a>
        <a class="cv-button secondary" href="/cv/">Ver CV detallado</a>
      </div>
    </div>
    <div class="cv-hero__media">
      <img src="{{ '/images/bio-photo-2.jpg' | relative_url }}" alt="Retrato de Gerardo Daniel López Montejo" />
      <p style="margin: 0.75rem 0 0;">Cancún, Quintana Roo · Disponible para colaboraciones e invitaciones docentes</p>
    </div>
  </section>

  <section>
    <h2>Resumen ejecutivo</h2>
    <div class="cv-grid">
      <div class="cv-card">
        <h3>Lo que hago</h3>
        <p>Dirijo y acompaño proyectos de análisis espacial, visualización de riesgo y formación universitaria.</p>
        <ul class="cv-list">
          <li>Modelado y cartografía de riesgos naturales con SIG y percepción remota.</li>
          <li>Diseño de experiencias de aprendizaje y cursos de posgrado en geotecnologías.</li>
          <li>Evaluación de productos interactivos con enfoque de usabilidad y jugabilidad.</li>
        </ul>
      </div>
      <div class="cv-card">
        <h3>Cómo aporto valor</h3>
        <p>Combino rigor académico con herramientas modernas para entregar soluciones accionables y formativas.</p>
        <ul class="cv-list">
          <li>Traducción de datos complejos a narrativas visuales para tomadores de decisión.</li>
          <li>Metodologías activas para comunidades educativas y equipos interdisciplinarios.</li>
          <li>Acompañamiento técnico con prácticas abiertas y colaborativas.</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2>Experiencia destacada</h2>
    <div class="cv-grid">
      <div class="cv-card">
        <h3>Responsable · Centro de Información Geográfica</h3>
        <p class="cv-chip">Universidad Autónoma de Quintana Roo · 2007 - presente</p>
        <ul class="cv-list">
          <li>Gestión de infraestructura geoespacial y repositorios de datos para investigación y docencia.</li>
          <li>Implementación de talleres de SIG, percepción remota y análisis de riesgo para estudiantes y docentes.</li>
          <li>Coordinación de proyectos de cartografía colaborativa para gobiernos locales.</li>
        </ul>
      </div>
      <div class="cv-card">
        <h3>Profesor universitario</h3>
        <p class="cv-chip">Programas de máster y doctorado · 2005 - presente</p>
        <ul class="cv-list">
          <li>Diseño de planes de asignatura y materiales prácticos en geotecnologías y desarrollo de software.</li>
          <li>Mentoría de tesis con enfoque en resiliencia, territorio y visualización de datos.</li>
          <li>Promoción de buenas prácticas en control de versiones y metodologías ágiles.</li>
        </ul>
      </div>
      <div class="cv-card">
        <h3>Formador y conferencista</h3>
        <p class="cv-chip">Comunidad tecnológica · 2016 - presente</p>
        <ul class="cv-list">
          <li>Capacitaciones en Kotlin y tecnologías de JetBrains para equipos académicos y de desarrollo.</li>
          <li>Charlas sobre experiencia de usuario, gamificación y evaluación de productos interactivos.</li>
          <li>Creación de recursos abiertos para facilitar la adopción de geotecnologías.</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2>Proyectos seleccionados</h2>
    <div class="cv-grid">
      <div class="cv-card">
        <h3>Mapa de riesgos naturales</h3>
        <p class="cv-chip">SIG · QGIS · Detección remota</p>
        <p>Modelado y visualización de amenazas en comunidades costeras para planes de mitigación local.</p>
      </div>
      <div class="cv-card">
        <h3>Ruta docente en geotecnologías</h3>
        <p class="cv-chip">Currículo · Mentoría · Evaluación</p>
        <p>Diseño de módulos prácticos para máster y doctorado, priorizando proyectos reproducibles.</p>
      </div>
      <div class="cv-card">
        <h3>Laboratorio de experiencia de usuario</h3>
        <p class="cv-chip">UX · Gamificación · Evaluación</p>
        <p>Protocolos para probar usabilidad en aplicaciones educativas y geoespaciales con equipos multidisciplinares.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Educación y certificaciones</h2>
    <div class="cv-subgrid">
      <div class="cv-subcard">
        <strong>Doctorado en Planeación (en progreso)</strong>
        <p class="cv-chip">Universidad Autónoma de Quintana Roo · 2018 - actual</p>
        <p style="margin: 0;">Investigación en resiliencia, territorio y adopción de geotecnologías.</p>
      </div>
      <div class="cv-subcard">
        <strong>Maestría en Planeación</strong>
        <p class="cv-chip">Universidad Autónoma de Quintana Roo · 2014</p>
        <p style="margin: 0;">Diseño y evaluación de estrategias de desarrollo regional.</p>
      </div>
      <div class="cv-subcard">
        <strong>Ingeniería Ambiental</strong>
        <p class="cv-chip">Universidad Autónoma de Quintana Roo · 2005</p>
        <p style="margin: 0;">Gestión ambiental y sistemas de información geográfica.</p>
      </div>
      <div class="cv-subcard cv-highlight">
        <strong>Certificaciones</strong>
        <ul class="cv-list">
          <li>Kotlin Trainer Certified by JetBrains</li>
          <li>GitHub Campus Advisor</li>
          <li>GitKraken Ambassador</li>
        </ul>
      </div>
    </div>
  </section>

  <section>
    <h2>Competencias técnicas y metodológicas</h2>
    <div class="cv-grid">
      <div class="cv-card">
        <h3>Geotecnologías</h3>
        <div class="cv-badges">
          <span class="cv-badge">QGIS</span>
          <span class="cv-badge">ArcGIS</span>
          <span class="cv-badge">Percepción remota</span>
          <span class="cv-badge">Modelado espacial</span>
        </div>
      </div>
      <div class="cv-card">
        <h3>Desarrollo y datos</h3>
        <div class="cv-badges">
          <span class="cv-badge">Python</span>
          <span class="cv-badge">Kotlin</span>
          <span class="cv-badge">JavaScript</span>
          <span class="cv-badge">GitHub Actions</span>
        </div>
      </div>
      <div class="cv-card">
        <h3>Docencia y facilitación</h3>
        <div class="cv-badges">
          <span class="cv-badge">Diseño instruccional</span>
          <span class="cv-badge">Aprendizaje basado en proyectos</span>
          <span class="cv-badge">Evaluación formativa</span>
          <span class="cv-badge">Mentoría individual</span>
        </div>
      </div>
    </div>
  </section>

  <section class="cv-footer">
    <p>¿Quieres colaborar o invitarme a tu curso, seminario o proyecto? Estoy abierto a nuevas propuestas.</p>
    <div class="cv-hero__actions" style="margin: 0;">
      <a class="cv-button primary" href="mailto:contacto@ejemplo.com">Escríbeme</a>
      <a class="cv-button secondary" href="https://github.com/tibadeux" target="_blank" rel="noopener">Ver GitHub</a>
    </div>
  </section>
</div>
