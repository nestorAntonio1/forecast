<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Forecast Financiero – Análisis de Proyección 10 Meses</title>
<style>
  :root {
    --primary: #0f2b5b;
    --accent: #1a6fc4;
    --success: #1a8a4a;
    --danger: #c0392b;
    --warning: #e67e22;
    --light: #f4f7fb;
    --border: #d0dcea;
    --text: #1c2a3a;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: 'Segoe UI', Arial, sans-serif; background: #eef2f7; color: var(--text); }

  header {
    background: linear-gradient(135deg, var(--primary) 0%, #1a4a8a 100%);
    color: #fff; padding: 36px 48px; border-bottom: 4px solid var(--accent);
  }
  header h1 { font-size: 2rem; letter-spacing: 1px; }
  header p { opacity: .75; margin-top: 6px; font-size: .95rem; }

  .container { max-width: 1200px; margin: 0 auto; padding: 32px 24px; }

  /* KPI Cards */
  .kpi-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 18px; margin-bottom: 36px; }
  .kpi { background: #fff; border-radius: 12px; padding: 22px 20px; border-left: 5px solid var(--accent); box-shadow: 0 2px 8px rgba(0,0,0,.07); }
  .kpi.red { border-color: var(--danger); }
  .kpi.green { border-color: var(--success); }
  .kpi.orange { border-color: var(--warning); }
  .kpi label { font-size: .75rem; text-transform: uppercase; letter-spacing: .5px; color: #6b7c93; }
  .kpi .value { font-size: 1.55rem; font-weight: 700; margin-top: 4px; }
  .kpi .value.red { color: var(--danger); }
  .kpi .value.green { color: var(--success); }
  .kpi .value.orange { color: var(--warning); }

  /* Section */
  .section { background: #fff; border-radius: 12px; padding: 28px; margin-bottom: 28px; box-shadow: 0 2px 8px rgba(0,0,0,.07); }
  .section h2 { font-size: 1.15rem; color: var(--primary); border-bottom: 2px solid var(--border); padding-bottom: 10px; margin-bottom: 20px; }

  /* Table */
  table { width: 100%; border-collapse: collapse; font-size: .875rem; }
  thead th { background: var(--primary); color: #fff; padding: 10px 12px; text-align: right; font-weight: 600; white-space: nowrap; }
  thead th:first-child { text-align: left; }
  tbody tr:nth-child(even) { background: var(--light); }
  tbody td { padding: 9px 12px; text-align: right; border-bottom: 1px solid var(--border); }
  tbody td:first-child { text-align: left; font-weight: 600; }
  tbody tr:hover { background: #dce8f8; }
  .neg { color: var(--danger); font-weight: 600; }
  .pos { color: var(--success); font-weight: 600; }
  tfoot td { background: var(--primary); color: #fff; padding: 10px 12px; font-weight: 700; text-align: right; }
  tfoot td:first-child { text-align: left; }

  /* Bar chart */
  .chart-wrap { margin-top: 10px; }
  .bar-row { display: flex; align-items: center; margin-bottom: 8px; gap: 10px; }
  .bar-label { width: 60px; font-size: .8rem; text-align: right; color: #4a5c72; flex-shrink: 0; }
  .bar-track { flex: 1; background: #eef2f7; border-radius: 4px; height: 26px; overflow: hidden; position: relative; }
  .bar-fill { height: 100%; border-radius: 4px; display: flex; align-items: center; padding-left: 8px; font-size: .75rem; color: #fff; font-weight: 600; transition: width .8s ease; }
  .bar-fill.green { background: linear-gradient(90deg, #1a8a4a, #25c26e); }
  .bar-fill.red { background: linear-gradient(90deg, #c0392b, #e74c3c); }
  .bar-val { font-size: .78rem; color: #4a5c72; width: 120px; text-align: left; flex-shrink: 0; }

  /* PRI */
  .pri-box { background: linear-gradient(135deg, #0f2b5b 0%, #1a6fc4 100%); color: #fff; border-radius: 14px; padding: 32px; text-align: center; }
  .pri-box .big { font-size: 3rem; font-weight: 800; margin: 10px 0; }
  .pri-box p { opacity: .8; font-size: .9rem; max-width: 500px; margin: 0 auto; }

  /* Supuestos */
  .assumptions { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
  .assump-card { background: var(--light); border-radius: 10px; padding: 18px; border: 1px solid var(--border); }
  .assump-card h3 { font-size: .9rem; color: var(--accent); margin-bottom: 12px; }
  .assump-card ul { list-style: none; }
  .assump-card ul li { padding: 5px 0; font-size: .85rem; border-bottom: 1px solid #dde4ed; }
  .assump-card ul li:last-child { border: none; }
  .tag { display: inline-block; font-size: .7rem; padding: 2px 7px; border-radius: 10px; margin-left: 6px; font-weight: 600; }
  .tag.fijo { background: #dce8f8; color: var(--accent); }
  .tag.variable { background: #fce8cc; color: var(--warning); }
  .badge-up { color: var(--success); font-weight: 700; }

  @media(max-width:700px){
    .assumptions { grid-template-columns: 1fr; }
    header { padding: 24px 18px; }
    .container { padding: 18px 10px; }
  }
</style>
</head>
<body>

<header>
  <h1>📊 Forecast Financiero — Proyección 10 Meses</h1>
  <p>Análisis de Ventas, Flujo de Efectivo y Período de Recuperación de la Inversión · Febrero 2026</p>
</header>

<div class="container">

  <!-- KPI Cards -->
  <div class="kpi-grid">
    <div class="kpi red">
      <label>Inversión Inicial</label>
      <div class="value red">−$850,000</div>
    </div>
    <div class="kpi">
      <label>Ventas Mes 1</label>
      <div class="value">$300,000</div>
    </div>
    <div class="kpi green">
      <label>Ventas Mes 10</label>
      <div class="value green">$2,180,459</div>
    </div>
    <div class="kpi green">
      <label>Primer mes positivo</label>
      <div class="value green">Mes 5</div>
    </div>
    <div class="kpi orange">
      <label>PRI (Período Recuperación)</label>
      <div class="value orange">8.24 meses</div>
    </div>
    <div class="kpi green">
      <label>Flujo Acumulado Mes 10</label>
      <div class="value green">$2,423,568</div>
    </div>
  </div>

  <!-- Supuestos -->
  <div class="section">
    <h2>📋 Supuestos del Modelo</h2>
    <div class="assumptions">
      <div class="assump-card">
        <h3>📈 Crecimiento de Ventas (Parte A)</h3>
        <ul>
          <li>Mes 1: $300,000 <span class="badge-up">(base)</span></li>
          <li>Mes 1→5: crecimiento <span class="badge-up">+10% ~ +25%</span></li>
          <li>Mes 5→8: crecimiento <span class="badge-up">+25% por mes</span></li>
          <li>Mes 8→10: crecimiento <span class="badge-up">+35% por mes</span></li>
        </ul>
      </div>
      <div class="assump-card">
        <h3>💸 Costos Fijos <span class="tag fijo">Fijo</span></h3>
        <ul>
          <li>Mes 1–5: $521,920 <small>(+12% del base)</small></li>
          <li>Mes 6–8: $536,230 <small>(+15% adicional)</small></li>
          <li>Mes 9–10: $557,300 <small>(+22% adicional)</small></li>
          <li>Incluye: Renta, Sueldos, Servicios, Sistemas, Seguro</li>
        </ul>
      </div>
      <div class="assump-card">
        <h3>🔄 Costos Variables <span class="tag variable">Variable</span></h3>
        <ul>
          <li>Mes 1–6: $184,800 <small>(+5%)</small></li>
          <li>Mes 7–10: $190,080 <small>(+8%)</small></li>
          <li>Incluye: Gas, Materia prima, Verduras, Publicidad, Comisiones, Empaques</li>
        </ul>
      </div>
      <div class="assump-card">
        <h3>🏗️ Estructura de Costos Base</h3>
        <ul>
          <li>Total Costos Fijos: $301,000 <span class="tag fijo">Fijo</span></li>
          <li>Total Costos Variables: $176,000 <span class="tag variable">Variable</span></li>
          <li>Total Mensual Base: $477,000</li>
          <li>Inversión inicial: $850,000</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Tabla Principal -->
  <div class="section">
    <h2>📊 Proyección de Ventas y Flujos de Efectivo</h2>
    <table>
      <thead>
        <tr>
          <th>Período</th>
          <th>Ventas</th>
          <th>Crecimiento</th>
          <th>Costo Fijo</th>
          <th>Costo Variable</th>
          <th>Costos Totales</th>
          <th>Flujo Neto</th>
          <th>Flujo Acumulado</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Inversión Inicial (Mes 0)</td>
          <td>—</td>
          <td>—</td>
          <td>—</td>
          <td>—</td>
          <td>—</td>
          <td class="neg">($850,000)</td>
          <td class="neg">($850,000)</td>
        </tr>
        <tr>
          <td>Mes 1</td>
          <td>$300,000</td>
          <td>Base</td>
          <td>$337,120</td>
          <td>$184,800</td>
          <td>$521,920</td>
          <td class="neg">($221,920)</td>
          <td class="neg">($1,071,920)</td>
        </tr>
        <tr>
          <td>Mes 2</td>
          <td>$330,000</td>
          <td class="badge-up">+10%</td>
          <td>$337,120</td>
          <td>$184,800</td>
          <td>$521,920</td>
          <td class="neg">($191,920)</td>
          <td class="neg">($1,263,840)</td>
        </tr>
        <tr>
          <td>Mes 3</td>
          <td>$363,000</td>
          <td class="badge-up">+10%</td>
          <td>$337,120</td>
          <td>$184,800</td>
          <td>$521,920</td>
          <td class="neg">($158,920)</td>
          <td class="neg">($1,422,760)</td>
        </tr>
        <tr>
          <td>Mes 4</td>
          <td>$453,750</td>
          <td class="badge-up">+25%</td>
          <td>$337,120</td>
          <td>$184,800</td>
          <td>$521,920</td>
          <td class="neg">($68,170)</td>
          <td class="neg">($1,490,930)</td>
        </tr>
        <tr>
          <td>Mes 5</td>
          <td>$567,188</td>
          <td class="badge-up">+25%</td>
          <td>$337,120</td>
          <td>$184,800</td>
          <td>$521,920</td>
          <td class="pos">$45,268</td>
          <td class="neg">($1,445,663)</td>
        </tr>
        <tr>
          <td>Mes 6</td>
          <td>$708,984</td>
          <td class="badge-up">+25%</td>
          <td>$346,150</td>
          <td>$184,800</td>
          <td>$530,950</td>
          <td class="pos">$178,034</td>
          <td class="neg">($1,267,628)</td>
        </tr>
        <tr>
          <td>Mes 7</td>
          <td>$886,230</td>
          <td class="badge-up">+25%</td>
          <td>$346,150</td>
          <td>$190,080</td>
          <td>$536,230</td>
          <td class="pos">$350,000</td>
          <td class="neg">($917,628)</td>
        </tr>
        <tr>
          <td>Mes 8</td>
          <td>$1,196,411</td>
          <td class="badge-up">+35%</td>
          <td>$346,150</td>
          <td>$190,080</td>
          <td>$536,230</td>
          <td class="pos">$660,181</td>
          <td class="neg">($257,447)</td>
        </tr>
        <tr>
          <td>Mes 9</td>
          <td>$1,615,155</td>
          <td class="badge-up">+35%</td>
          <td>$367,220</td>
          <td>$190,080</td>
          <td>$557,300</td>
          <td class="pos">$1,057,855</td>
          <td class="pos">$800,409</td>
        </tr>
        <tr>
          <td>Mes 10</td>
          <td>$2,180,459</td>
          <td class="badge-up">+35%</td>
          <td>$367,220</td>
          <td>$190,080</td>
          <td>$557,300</td>
          <td class="pos">$1,623,159</td>
          <td class="pos">$2,423,568</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td>TOTAL ACUMULADO</td>
          <td>$8,600,177</td>
          <td></td>
          <td>$3,311,210</td>
          <td>$1,873,440</td>
          <td>$5,184,650</td>
          <td>$3,273,568</td>
          <td>$2,423,568</td>
        </tr>
      </tfoot>
    </table>
  </div>

  <!-- Gráfica de Flujo Neto -->
  <div class="section">
    <h2>📉📈 Flujo Neto por Mes</h2>
    <div class="chart-wrap">
      <!-- Max positive ~1,623,159 -->
      <div class="bar-row">
        <div class="bar-label">Mes 0</div>
        <div class="bar-track">
          <div class="bar-fill red" style="width:52.4%">−$850,000</div>
        </div>
        <div class="bar-val neg">($850,000)</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 1</div>
        <div class="bar-track">
          <div class="bar-fill red" style="width:13.7%">−$221,920</div>
        </div>
        <div class="bar-val neg">($221,920)</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 2</div>
        <div class="bar-track">
          <div class="bar-fill red" style="width:11.8%">−$191,920</div>
        </div>
        <div class="bar-val neg">($191,920)</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 3</div>
        <div class="bar-track">
          <div class="bar-fill red" style="width:9.8%">−$158,920</div>
        </div>
        <div class="bar-val neg">($158,920)</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 4</div>
        <div class="bar-track">
          <div class="bar-fill red" style="width:4.2%">−$68,170</div>
        </div>
        <div class="bar-val neg">($68,170)</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 5</div>
        <div class="bar-track">
          <div class="bar-fill green" style="width:2.8%">$45K</div>
        </div>
        <div class="bar-val pos">$45,268</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 6</div>
        <div class="bar-track">
          <div class="bar-fill green" style="width:11%">$178K</div>
        </div>
        <div class="bar-val pos">$178,034</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 7</div>
        <div class="bar-track">
          <div class="bar-fill green" style="width:21.6%">$350K</div>
        </div>
        <div class="bar-val pos">$350,000</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 8</div>
        <div class="bar-track">
          <div class="bar-fill green" style="width:40.7%">$660K</div>
        </div>
        <div class="bar-val pos">$660,181</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 9</div>
        <div class="bar-track">
          <div class="bar-fill green" style="width:65.2%">$1,057,855</div>
        </div>
        <div class="bar-val pos">$1,057,855</div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Mes 10</div>
        <div class="bar-track">
          <div class="bar-fill green" style="width:100%">$1,623,159</div>
        </div>
        <div class="bar-val pos">$1,623,159</div>
      </div>
    </div>
  </div>

  <!-- PRI Box -->
  <div class="section">
    <h2>⏱️ Período de Recuperación de la Inversión (PRI)</h2>
    <div class="pri-box">
      <p style="opacity:.6;font-size:.85rem;">PERÍODO DE RECUPERACIÓN DE LA INVERSIÓN</p>
      <div class="big">8.24 Meses</div>
      <p>La inversión inicial de <strong>$850,000</strong> comienza a recuperarse en el <strong>Mes 5</strong> (primer flujo neto positivo) y se recupera completamente entre el <strong>Mes 8 y Mes 9</strong>. El cálculo exacto es <em>8 + (257,447 / 1,057,855) ≈ 8.24 meses</em>.</p>
    </div>

    <div style="margin-top:20px; display:grid; grid-template-columns:1fr 1fr 1fr; gap:16px;">
      <div style="background:#fff8ec;border:1px solid #f5c272;border-radius:10px;padding:18px;text-align:center;">
        <div style="font-size:.8rem;color:#9b6a00;text-transform:uppercase;letter-spacing:.5px;">Mes 5</div>
        <div style="font-size:1.3rem;font-weight:700;color:#c97d00;">Punto de Equilibrio</div>
        <div style="font-size:.8rem;color:#9b6a00;">Primer flujo neto positivo: +$45,268</div>
      </div>
      <div style="background:#fef0f0;border:1px solid #f5b3b3;border-radius:10px;padding:18px;text-align:center;">
        <div style="font-size:.8rem;color:#900;text-transform:uppercase;letter-spacing:.5px;">Mes 8</div>
        <div style="font-size:1.3rem;font-weight:700;color:#c0392b;">Casi recuperado</div>
        <div style="font-size:.8rem;color:#900;">Flujo acumulado: −$257,447</div>
      </div>
      <div style="background:#edfbf1;border:1px solid #7ed6a3;border-radius:10px;padding:18px;text-align:center;">
        <div style="font-size:.8rem;color:#1a5c30;text-transform:uppercase;letter-spacing:.5px;">Mes 8.24</div>
        <div style="font-size:1.3rem;font-weight:700;color:#1a8a4a;">Recuperación Total</div>
        <div style="font-size:.8rem;color:#1a5c30;">Inversión 100% recuperada</div>
      </div>
    </div>
  </div>

  <!-- Análisis de Estructura de Costos -->
  <div class="section">
    <h2>🏗️ Desglose de Costos Base (Mensual)</h2>
    <table>
      <thead>
        <tr>
          <th>Concepto</th>
          <th>Monto</th>
          <th>Tipo</th>
          <th>% del Total</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Sueldos cocina</td><td>$85,000</td><td><span class="tag fijo">Fijo</span></td><td>17.8%</td></tr>
        <tr><td>Sueldos administrativos</td><td>$60,000</td><td><span class="tag fijo">Fijo</span></td><td>12.6%</td></tr>
        <tr><td>Materia prima mariscos</td><td>$95,000</td><td><span class="tag variable">Variable</span></td><td>19.9%</td></tr>
        <tr><td>Renta local</td><td>$45,000</td><td><span class="tag fijo">Fijo</span></td><td>9.4%</td></tr>
        <tr><td>Sueldos meseros</td><td>$55,000</td><td><span class="tag fijo">Fijo</span></td><td>11.5%</td></tr>
        <tr><td>Verduras e insumos</td><td>$35,000</td><td><span class="tag variable">Variable</span></td><td>7.3%</td></tr>
        <tr><td>Comisiones plataformas</td><td>$12,000</td><td><span class="tag variable">Variable</span></td><td>2.5%</td></tr>
        <tr><td>Empaques</td><td>$10,000</td><td><span class="tag variable">Variable</span></td><td>2.1%</td></tr>
        <tr><td>Electricidad</td><td>$18,000</td><td><span class="tag fijo">Fijo</span></td><td>3.8%</td></tr>
        <tr><td>Mantenimiento</td><td>$12,000</td><td><span class="tag fijo">Fijo</span></td><td>2.5%</td></tr>
        <tr><td>Publicidad</td><td>$15,000</td><td><span class="tag variable">Variable</span></td><td>3.1%</td></tr>
        <tr><td>Seguro</td><td>$6,000</td><td><span class="tag fijo">Fijo</span></td><td>1.3%</td></tr>
        <tr><td>Agua</td><td>$6,000</td><td><span class="tag fijo">Fijo</span></td><td>1.3%</td></tr>
        <tr><td>Gas</td><td>$9,000</td><td><span class="tag variable">Variable</span></td><td>1.9%</td></tr>
        <tr><td>Contador</td><td>$8,000</td><td><span class="tag fijo">Fijo</span></td><td>1.7%</td></tr>
        <tr><td>Internet</td><td>$2,500</td><td><span class="tag fijo">Fijo</span></td><td>0.5%</td></tr>
        <tr><td>Sistema POS</td><td>$3,500</td><td><span class="tag fijo">Fijo</span></td><td>0.7%</td></tr>
      </tbody>
      <tfoot>
        <tr><td>TOTAL FIJO</td><td>$301,000</td><td></td><td>63.1%</td></tr>
        <tr><td>TOTAL VARIABLE</td><td>$176,000</td><td></td><td>36.9%</td></tr>
      </tfoot>
    </table>
  </div>

  <!-- Conclusiones -->
  <div class="section">
    <h2>📌 Conclusiones y Recomendaciones</h2>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;">
      <div>
        <h3 style="color:var(--success);margin-bottom:10px;">✅ Aspectos Positivos</h3>
        <ul style="list-style:none;">
          <li style="padding:7px 0;border-bottom:1px solid var(--border);font-size:.88rem;">📈 Crecimiento agresivo de ventas: de $300K a $2.18M en 10 meses (+627%)</li>
          <li style="padding:7px 0;border-bottom:1px solid var(--border);font-size:.88rem;">💚 Primer flujo positivo en Mes 5, lo cual es razonable para un negocio nuevo</li>
          <li style="padding:7px 0;border-bottom:1px solid var(--border);font-size:.88rem;">🏆 PRI de 8.24 meses es favorable para el sector gastronómico</li>
          <li style="padding:7px 0;font-size:.88rem;">📊 Estructura de costos bien balanceada (63% fijo / 37% variable)</li>
        </ul>
      </div>
      <div>
        <h3 style="color:var(--warning);margin-bottom:10px;">⚠️ Puntos de Atención</h3>
        <ul style="list-style:none;">
          <li style="padding:7px 0;border-bottom:1px solid var(--border);font-size:.88rem;">🔴 Los primeros 4 meses generan flujos negativos acumulados de hasta $1.49M</li>
          <li style="padding:7px 0;border-bottom:1px solid var(--border);font-size:.88rem;">⚡ Las tasas de crecimiento de 35% mensual (Mes 8-10) son muy optimistas; validar con datos de mercado</li>
          <li style="padding:7px 0;border-bottom:1px solid var(--border);font-size:.88rem;">🍤 Materia prima mariscos (20% del costo total) es muy sensible a inflación y estacionalidad</li>
          <li style="padding:7px 0;font-size:.88rem;">💰 Se recomienda contar con un fondo de reserva mínimo de $1.5M para los primeros 8 meses</li>
        </ul>
      </div>
    </div>
  </div>

  <div style="text-align:center;padding:20px;color:#8a9ab5;font-size:.8rem;">
    Forecast generado por Claude – Análisis Financiero | Datos basados en archivo: act_3_admin_finan.xlsx | Febrero 2026
  </div>

</div>
</body>
</html>
