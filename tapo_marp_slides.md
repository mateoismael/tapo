---
marp: true
title: "Tapo Smart Bulb — Mini deck (4 diapositivas)"
description: "Portada con integrantes y 3 diapositivas principales para exponer guía de configuración."
paginate: true
theme: default
_class: lead
style: |
  :root {
    --accent: #007BFF;
    --accent-2: #00E5FF;
    --text: #111318;
    --bg: #F5F7FA;
    --card: #FFFFFF;
  }
  section {
    padding: 60px;
    background: var(--bg);
    color: var(--text);
  }
  h1 { font-size: 56px; margin: 0 0 12px; }
  h2 { font-size: 48px; margin: 0 0 12px; }
  p, li { font-size: 32px; line-height: 1.25; }
  code { font-size: 28px; }
  .small { font-size: 24px; }
  .accent { color: var(--accent); }
  .kicker { text-transform: uppercase; letter-spacing: .08em; color: var(--accent); font-size: 20px; }
  .callout {
    border-left: 6px solid var(--accent);
    background: #E9F3FF;
    padding: 12px 16px;
    border-radius: 12px;
    font-size: 26px;
    margin-top: 12px;
  }
  .grid-3 {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
    margin-top: 8px;
  }
  .card {
    background: var(--card);
    border: 1px solid #E5E7EB;
    border-radius: 16px;
    padding: 20px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.06);
  }
  .card h3 {
    margin: 0 0 8px;
    font-size: 32px;
    color: var(--accent);
  }
  ul { margin: 12px 0 0 0; padding-left: 26px; }
  li { margin: 6px 0; }
  footer { font-size: 20px; color: #475569; }
---

<!--
Para exportar con Marp CLI:
marp --pdf tapo_marp_slides.md
o para PowerPoint:
marp --pptx tapo_marp_slides.md
-->

<!-- ====================================================== -->
<!-- DIAPOSITIVA 0 — PORTADA CON INTEGRANTES                -->
<!-- ====================================================== -->

# Tapo Smart Bulb

**Guía de configuración (FAQ 2848)**

**Integrantes:** Enzo Gomez · Ismael Rodríguez

---

<!-- ====================================================== -->
<!-- DIAPOSITIVA 1 — CONTEXTO Y PROPÓSITO                   -->
<!-- ====================================================== -->

## Contexto y propósito

- **Producto/guía:** Tapo Smart Bulb — FAQ 2848 (setup)
- **Objetivo:** configuración inicial vía app Tapo
- **Audiencia:** usuarios domésticos no técnicos
- **Alcance:** app → añadir dispositivo → emparejar → Wi‑Fi → firmware

<div class="callout">
Recomendación transversal: publicar versión **ES‑PE** (texto y capturas).
</div>

---

<!-- ====================================================== -->
<!-- DIAPOSITIVA 2 — DECISIONES EDITORIALES CLAVE           -->
<!-- ====================================================== -->

## Decisiones editoriales clave

<div class="grid-3">
  <div class="card">
    <h3>Lenguaje + visual</h3>
    <ul>
      <li>Imperativos simples + capturas de app</li>
      <li>QR de descarga (menos fricción)</li>
    </ul>
  </div>
  <div class="card">
    <h3>Éxito 1° intento</h3>
    <ul>
      <li>Pasos numerados claros</li>
      <li>Actualización de firmware al final</li>
    </ul>
  </div>
  <div class="card">
    <h3>Entornos variados</h3>
    <ul>
      <li>Emparejamiento por Bluetooth</li>
      <li>Modo AP: <code>Tapo_Bulb_XXXX</code></li>
    </ul>
  </div>
</div>

---

<!-- ====================================================== -->
<!-- DIAPOSITIVA 3 — RECOMENDACIONES PRIORIZADAS            -->
<!-- ====================================================== -->

## Recomendaciones priorizadas

<div class="grid-3">
  <div class="card">
    <h3>Localización ES‑PE</h3>
    Traducir **texto y capturas**; hoy está en inglés en <code>/pe/</code> → mejor comprensión.
  </div>
  <div class="card">
    <h3>Alcance por modelo</h3>
    Listar **L531E/L535E…** y diferencias (Bluetooth vs AP, **2.4 GHz**) → evita pasos erróneos.
  </div>
  <div class="card">
    <h3>Checklist + diagnóstico</h3>
    **2.4 GHz** ON, clave lista, BT/ubicación ON, cerca del router, datos móviles OFF + **mini tabla** síntoma→acción.
  </div>
</div>
