<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>NovaPay TPRM Dashboard — PayLink Cloud Services</title>
<style>
:root{
  --bg:#0b1220; --panel:#131c30; --panel2:#0f1728; --border:#223050;
  --text:#e7edf7; --muted:#93a3c2; --accent:#4da3ff;
  --crit:#ef4757; --high:#f59e42; --med:#f2d43d; --low:#3ecf8e;
  --eff:#3ecf8e; --part:#f2b73d; --gap:#ef4757;
  --card-shadow: 0 1px 0 rgba(255,255,255,.03) inset;
  font-size:16px;
}
:root:not([data-theme="light"]) { }
@media (prefers-color-scheme: light){
  :root:not([data-theme="dark"]){
    --bg:#f4f6fb; --panel:#ffffff; --panel2:#eef1f8;
    --border:#dbe2ef; --text:#1a2233; --muted:#5b6b8c;
  }
}
:root[data-theme="light"]{
  --bg:#f4f6fb; --panel:#ffffff; --panel2:#eef1f8;
  --border:#dbe2ef; --text:#1a2233; --muted:#5b6b8c;
}
*{box-sizing:border-box;}
html,body{height:100%;}
body{
  margin:0; background:var(--bg); color:var(--text);
  font-family:'Segoe UI',ui-sans-serif,system-ui,-apple-system,Arial,sans-serif;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
.wrap{max-width:1180px;margin:0 auto;padding:20px 18px 48px;}
header{display:flex;flex-wrap:wrap;gap:14px;align-items:center;justify-content:space-between;
  padding:18px 20px;background:linear-gradient(135deg,var(--panel),var(--panel2));
  border:1px solid var(--border);border-radius:14px;margin-bottom:18px;}
header h1{margin:0;font-size:1.3rem;letter-spacing:.2px;}
header p{margin:2px 0 0;color:var(--muted);font-size:.85rem;}
.pill{padding:6px 14px;border-radius:999px;font-weight:700;font-size:.78rem;letter-spacing:.4px;text-transform:uppercase;}
.pill.crit{background:rgba(239,71,87,.16);color:var(--crit);border:1px solid var(--crit);}
.kpis{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:12px;margin-bottom:20px;}
.kpi{background:var(--panel);border:1px solid var(--border);border-radius:12px;padding:14px 16px;box-shadow:var(--card-shadow);}
.kpi .num{font-size:1.7rem;font-weight:800;}
.kpi .lbl{color:var(--muted);font-size:.78rem;margin-top:2px;}
.crit-txt{color:var(--crit);} .high-txt{color:var(--high);} .ok-txt{color:var(--low);}
section{background:var(--panel);border:1px solid var(--border);border-radius:14px;padding:18px 20px;margin-bottom:18px;}
section h2{margin:0 0 4px;font-size:1.02rem;}
section .sub{color:var(--muted);font-size:.82rem;margin:0 0 14px;}
.grid2{display:grid;grid-template-columns:1.15fr .85fr;gap:18px;}
@media(max-width:820px){.grid2{grid-template-columns:1fr;}}
table{width:100%;border-collapse:collapse;font-size:.85rem;}
th,td{text-align:left;padding:8px 10px;border-bottom:1px solid var(--border);vertical-align:top;}
th{color:var(--muted);font-weight:600;font-size:.75rem;text-transform:uppercase;letter-spacing:.3px;}
tbody tr:hover{background:rgba(77,163,255,.05);}
.badge{display:inline-block;padding:3px 9px;border-radius:6px;font-weight:700;font-size:.72rem;white-space:nowrap;}
.b-crit{background:rgba(239,71,87,.16);color:var(--crit);}
.b-high{background:rgba(245,158,66,.16);color:var(--high);}
.b-med{background:rgba(242,212,61,.18);color:#b8940a;}
.b-eff{background:rgba(62,207,142,.16);color:var(--eff);}
.b-part{background:rgba(242,183,61,.16);color:var(--part);}
.b-gap{background:rgba(239,71,87,.16);color:var(--gap);}
.b-open{background:rgba(147,163,194,.18);color:var(--muted);}
.tablewrap{overflow-x:auto;}
table.kri{min-width:900px;table-layout:fixed;}
table.kri th:nth-child(1){width:16%;}
table.kri th:nth-child(2){width:14%;}
table.kri th:nth-child(3){width:14%;}
table.kri th:nth-child(4){width:14%;}
table.kri th:nth-child(5){width:21%;}
table.kri th:nth-child(6){width:21%;}
table.kri td{overflow-wrap:break-word;}
.matrixbox{display:flex;justify-content:center;}
svg text{fill:var(--text);font-family:inherit;}
.legend{display:flex;gap:14px;flex-wrap:wrap;margin-top:10px;font-size:.75rem;color:var(--muted);}
.legend span{display:inline-flex;align-items:center;gap:6px;}
.dot{width:10px;height:10px;border-radius:50%;display:inline-block;}
.donutrow{display:flex;align-items:center;gap:22px;flex-wrap:wrap;}
.donut{width:150px;height:150px;border-radius:50%;
  background:conic-gradient(var(--eff) 0 94.4%, var(--gap) 94.4% 100%);
  display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.donut-inner{width:104px;height:104px;border-radius:50%;background:var(--panel);
  display:flex;flex-direction:column;align-items:center;justify-content:center;}
.donut-inner b{font-size:1.4rem;}
.donut-inner span{font-size:.7rem;color:var(--muted);}
.flow{display:flex;flex-wrap:wrap;gap:8px;align-items:center;font-size:.78rem;}
.flow .node{background:var(--panel2);border:1px solid var(--border);padding:8px 12px;border-radius:8px;}
.flow .arrow{color:var(--muted);}
.bar-row{display:flex;align-items:center;gap:10px;margin:7px 0;font-size:.8rem;}
.bar-row .lbl{width:180px;flex-shrink:0;color:var(--muted);}
.bar-track{flex:1;background:var(--panel2);border-radius:6px;height:16px;overflow:hidden;position:relative;}
.bar-fill{height:100%;border-radius:6px;}
.bar-val{width:80px;text-align:right;flex-shrink:0;font-weight:700;}
footer{text-align:center;color:var(--muted);font-size:.75rem;padding:18px 0 6px;}
.exec-summary{border-left:4px solid var(--accent);}
.exec-body p{margin:0 0 12px;font-size:.9rem;line-height:1.65;}
.exec-body p:last-child{margin-bottom:0;}
.exec-body strong{color:var(--text);}
.exec-actions{margin-top:16px;padding-top:14px;border-top:1px solid var(--border);}
.exec-actions h3{margin:0 0 10px;font-size:.78rem;text-transform:uppercase;letter-spacing:.4px;color:var(--muted);font-weight:600;}
.exec-actions ol{margin:0;padding-left:20px;font-size:.88rem;line-height:1.6;}
.exec-actions li{margin-bottom:8px;}
.exec-actions li:last-child{margin-bottom:0;}
</style>
</head>
<body>
<div class="wrap">

<header>
  <div>
    <h1>NovaPay Third-Party / Vendor Risk Dashboard</h1>
    <p>Vendor: PayLink Cloud Services Ltd. · Cloud payment API &amp; transaction-processing infrastructure · Assessment: Initial TPRM</p>
  </div>
  <span class="pill crit">Overall Inherent Risk: Critical</span>
</header>

<section class="exec-summary">
  <h2>Executive Summary</h2>
  <p class="sub">Prepared for the Vendor Risk Committee · Initial TPRM assessment · PayLink Cloud Services Ltd.</p>
  <div class="exec-body">
    <p><strong>PayLink Cloud Services is a critical vendor.</strong> It provides the cloud payment API and transaction-processing infrastructure NovaPay relies on to accept and settle card payments. A failure or compromise at PayLink would directly disrupt payment processing and could expose cardholder data. The vendor is assessed as inherently <strong>Critical</strong>.</p>
    <p><strong>The evidence package is broadly complete, but completeness is not assurance.</strong> PayLink submitted 17 of 19 requested evidence items. Only one of six sampled controls was fully effective. Three findings remain open, including privileged access weaknesses and unverified disaster recovery capability. The ISO 27001 certificate on file has not had its scope or validity confirmed, and PCI DSS attestation for the cardholder data environment has not been received. Current residual risk remains <strong>High</strong>, with one open finding linked to a Critical-rated risk.</p>
    <p><strong>No risk acceptance has been recorded.</strong> All findings are routed to mitigation. The outstanding DR test report (VTF-03) is the single item that, once received and validated, would allow reassessment of the two highest-scoring risks in the register.</p>
  </div>
  <div class="exec-actions">
    <h3>Top 3 Actions This Quarter</h3>
    <ol>
      <li><strong>Obtain and validate the DR test report</strong>, closes VTF-03, linked to VTR-03 (Critical) and VTR-10 (High).</li>
      <li><strong>Request current PCI DSS AOC/ROC with scope statement</strong>, to confirm coverage of the NovaPay cardholder data environment (VTR-11).</li>
      <li><strong>Remediate two overdue critical vulnerabilities and complete the privileged-access review</strong>, closes VTF-01 and VTF-02.</li>
    </ol>
  </div>
</section>

<div class="kpis">
  <div class="kpi"><div class="num crit-txt">3</div><div class="lbl">Critical-rated risks</div></div>
  <div class="kpi"><div class="num high-txt">8</div><div class="lbl">High-rated risks</div></div>
  <div class="kpi"><div class="num">17 / 19</div><div class="lbl">Evidence items received</div></div>
  <div class="kpi"><div class="num crit-txt">3</div><div class="lbl">Open findings, all High severity</div></div>
  <div class="kpi"><div class="num">1 / 6</div><div class="lbl">Controls fully effective</div></div>
  <div class="kpi"><div class="num high-txt">High</div><div class="lbl">Current residual risk (unchanged)</div></div>
</div>

<div class="grid2">
  <section>
    <h2>Risk Register — 11 vendor risk scenarios</h2>
    <p class="sub">Likelihood × Impact, 5×5 model. 20–25 Critical · 12–19 High · 6–11 Medium · 1–5 Low</p>
    <div class="tablewrap">
    <table>
      <tr><th>ID</th><th>Risk scenario</th><th>L</th><th>I</th><th>Score</th><th>Rating</th></tr>
      <tr><td>VTR-01</td><td>Unauthorized access to NovaPay data through vendor compromise</td><td>4</td><td>5</td><td>20</td><td><span class="badge b-crit">Critical</span></td></tr>
      <tr><td>VTR-02</td><td>Vendor API compromise disrupts payment processing</td><td>4</td><td>5</td><td>20</td><td><span class="badge b-crit">Critical</span></td></tr>
      <tr><td>VTR-03</td><td>Vendor outage disrupts payment services</td><td>4</td><td>5</td><td>20</td><td><span class="badge b-crit">Critical</span></td></tr>
      <tr><td>VTR-04</td><td>Inadequate vulnerability management exposes integrated systems</td><td>4</td><td>4</td><td>16</td><td><span class="badge b-high">High</span></td></tr>
      <tr><td>VTR-05</td><td>Excessive vendor privileges enable unauthorized activity</td><td>3</td><td>5</td><td>15</td><td><span class="badge b-high">High</span></td></tr>
      <tr><td>VTR-06</td><td>Delayed vendor incident notification increases impact</td><td>3</td><td>5</td><td>15</td><td><span class="badge b-high">High</span></td></tr>
      <tr><td>VTR-07</td><td>Inadequate logging prevents effective investigation</td><td>3</td><td>4</td><td>12</td><td><span class="badge b-high">High</span></td></tr>
      <tr><td>VTR-08</td><td>Subcontractor introduces additional security exposure</td><td>3</td><td>4</td><td>12</td><td><span class="badge b-high">High</span></td></tr>
      <tr><td>VTR-09</td><td>Improper / excessive data retention exposes information</td><td>3</td><td>4</td><td>12</td><td><span class="badge b-high">High</span></td></tr>
      <tr><td>VTR-10</td><td>Vendor lacks effective recovery capability post-disruption</td><td>3</td><td>5</td><td>15</td><td><span class="badge b-high">High</span></td></tr>
      <tr><td>VTR-11</td><td>PCI DSS compliance cannot be validated, attestation scope, currency, or coverage insufficient</td><td>3</td><td>5</td><td>15</td><td><span class="badge b-high">High</span></td></tr>
    </table>
    </div>
  </section>

  <section>
    <h2>Risk Heatmap</h2>
    <p class="sub">Plotted by Likelihood (x) / Impact (y)</p>
    <div class="matrixbox">
    <svg viewBox="0 0 300 300" width="100%" height="290" style="max-width:320px">
      <!-- background rating cells -->
      <g>
        <!-- rows top(impact5) to bottom(impact1), cols left(L1) to right(L5) -->
        <!-- colors precomputed by L*I -->
      </g>
      <script/>
      <g id="cells"></g>
      <g stroke="var(--border)" stroke-width="1">
      </g>
      <!-- grid drawn via rects -->
      <g>
        <!-- generate 25 cells -->
        <!-- L1..5 across x=30..270 step 48, I5..1 down y=10..250 step 48 -->
      </g>
      <g font-size="9" fill="var(--muted)">
        <text x="10" y="18">5</text><text x="10" y="66">4</text><text x="10" y="114">3</text><text x="10" y="162">2</text><text x="10" y="210">1</text>
        <text x="150" y="270" text-anchor="middle" font-size="10">Likelihood →</text>
        <text x="150" y="12" text-anchor="middle" font-size="10">Impact ↑</text>
      </g>
      <!-- cell rects: x = 30 + (L-1)*48 ; y = (5-I)*48 + 10 ; size 44 -->
      <rect x="222" y="10" width="44" height="44" fill="rgba(239,71,87,.35)"/>
      <rect x="174" y="10" width="44" height="44" fill="rgba(239,71,87,.35)"/>
      <rect x="126" y="10" width="44" height="44" fill="rgba(245,158,66,.30)"/>
      <rect x="78" y="10" width="44" height="44" fill="rgba(242,212,61,.28)"/>
      <rect x="30" y="10" width="44" height="44" fill="rgba(62,207,142,.28)"/>

      <rect x="222" y="58" width="44" height="44" fill="rgba(239,71,87,.35)"/>
      <rect x="174" y="58" width="44" height="44" fill="rgba(245,158,66,.30)"/>
      <rect x="126" y="58" width="44" height="44" fill="rgba(245,158,66,.30)"/>
      <rect x="78" y="58" width="44" height="44" fill="rgba(242,212,61,.28)"/>
      <rect x="30" y="58" width="44" height="44" fill="rgba(62,207,142,.28)"/>

      <rect x="222" y="106" width="44" height="44" fill="rgba(245,158,66,.30)"/>
      <rect x="174" y="106" width="44" height="44" fill="rgba(245,158,66,.30)"/>
      <rect x="126" y="106" width="44" height="44" fill="rgba(242,212,61,.28)"/>
      <rect x="78" y="106" width="44" height="44" fill="rgba(242,212,61,.28)"/>
      <rect x="30" y="106" width="44" height="44" fill="rgba(62,207,142,.28)"/>

      <rect x="222" y="154" width="44" height="44" fill="rgba(242,212,61,.28)"/>
      <rect x="174" y="154" width="44" height="44" fill="rgba(242,212,61,.28)"/>
      <rect x="126" y="154" width="44" height="44" fill="rgba(62,207,142,.28)"/>
      <rect x="78" y="154" width="44" height="44" fill="rgba(62,207,142,.28)"/>
      <rect x="30" y="154" width="44" height="44" fill="rgba(62,207,142,.28)"/>

      <rect x="222" y="202" width="44" height="44" fill="rgba(62,207,142,.28)"/>
      <rect x="174" y="202" width="44" height="44" fill="rgba(62,207,142,.28)"/>
      <rect x="126" y="202" width="44" height="44" fill="rgba(62,207,142,.28)"/>
      <rect x="78" y="202" width="44" height="44" fill="rgba(62,207,142,.28)"/>
      <rect x="30" y="202" width="44" height="44" fill="rgba(62,207,142,.28)"/>

      <!-- points: cx = 30+(L-1)*48+22 ; cy=(5-I)*48+10+22 -->
      <!-- VTR-01 L4 I5 -->
      <circle cx="200" cy="32" r="6" fill="#fff" stroke="var(--crit)" stroke-width="2"/><text x="200" y="35" text-anchor="middle" font-size="7" fill="#111">1,2</text>
      <!-- VTR-03 L4 I5 same point offset label -->
      <circle cx="212" cy="32" r="6" fill="#fff" stroke="var(--crit)" stroke-width="2"/><text x="212" y="35" text-anchor="middle" font-size="7" fill="#111">3</text>
      <!-- VTR-04 L4 I4 -->
      <circle cx="200" cy="80" r="6" fill="#fff" stroke="var(--high)" stroke-width="2"/><text x="200" y="83" text-anchor="middle" font-size="7" fill="#111">4</text>
      <!-- VTR-05, 06, 10, 11 all L3 I5: spaced evenly inside the correct cell (was overflowing into L4) -->
      <circle cx="134" cy="32" r="5" fill="#fff" stroke="var(--high)" stroke-width="2"/><text x="134" y="35" text-anchor="middle" font-size="6" fill="#111">5</text>
      <circle cx="146" cy="32" r="5" fill="#fff" stroke="var(--high)" stroke-width="2"/><text x="146" y="35" text-anchor="middle" font-size="6" fill="#111">6</text>
      <circle cx="158" cy="32" r="5" fill="#fff" stroke="var(--high)" stroke-width="2"/><text x="158" y="35" text-anchor="middle" font-size="6" fill="#111">10</text>
      <circle cx="169" cy="32" r="5" fill="#fff" stroke="var(--high)" stroke-width="2"/><text x="169" y="35" text-anchor="middle" font-size="6" fill="#111">11</text>
      <!-- VTR-07,08,09 L3 I4 -->
      <circle cx="152" cy="80" r="6" fill="#fff" stroke="var(--high)" stroke-width="2"/><text x="152" y="83" text-anchor="middle" font-size="7" fill="#111">7,8,9</text>
    </svg>
    </div>
    <div class="legend">
      <span><i class="dot" style="background:var(--crit)"></i>Critical</span>
      <span><i class="dot" style="background:var(--high)"></i>High</span>
      <span><i class="dot" style="background:#b8940a"></i>Medium</span>
      <span><i class="dot" style="background:var(--low)"></i>Low</span>
    </div>
  </section>
</div>

<section>
  <h2>Due-Diligence Evidence Package</h2>
  <p class="sub">19 evidence requests tied to specific risk areas · PayLink submission status</p>
  <div class="donutrow">
    <div class="donut" style="background:conic-gradient(var(--eff) 0 89.5%, var(--gap) 89.5% 100%);"><div class="donut-inner"><b>89%</b><span>received</span></div></div>
    <div style="flex:1;min-width:260px">
      <div class="bar-row"><span class="lbl">Received / Satisfactory</span><div class="bar-track"><div class="bar-fill" style="width:89%;background:var(--eff)"></div></div><span class="bar-val">17 items</span></div>
      <div class="bar-row"><span class="lbl">Missing (DR test + PCI DSS)</span><div class="bar-track"><div class="bar-fill" style="width:11%;background:var(--gap)"></div></div><span class="bar-val">2 items</span></div>
      <p class="sub" style="margin-top:10px">Note: "received" ≠ validated. The DR test report and PCI DSS attestation remain outstanding. ISO 27001 and similar items are marked satisfactory subject to scope/validity verification — a document existing is not the same as a control operating effectively.</p>
    </div>
  </div>
  <details style="margin-top:6px">
    <summary style="cursor:pointer;color:var(--accent);font-size:.85rem">View full 19-item evidence register</summary>
    <div class="tablewrap" style="margin-top:10px">
    <table>
      <tr><th>ID</th><th>Risk area</th><th>Evidence requested</th><th>Status</th></tr>
      <tr><td>DD-01</td><td>Info-sec governance</td><td>ISMS / Information Security Policy</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-02</td><td>Independent assurance</td><td>ISO 27001 certificate / SOC 2</td><td><span class="badge b-part">Received – scope/validity TBC</span></td></tr>
      <tr><td>DD-03</td><td>Access control</td><td>Access Control Policy + privileged-access procedure</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-04</td><td>Authentication</td><td>MFA / authentication standard</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-05</td><td>Vulnerability management</td><td>Policy + latest assessment summary</td><td><span class="badge b-part">Received – 2 criticals overdue</span></td></tr>
      <tr><td>DD-06</td><td>Penetration testing</td><td>Recent pen-test executive summary</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-07</td><td>Incident response</td><td>IR Plan + notification procedure</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-08</td><td>Logging &amp; monitoring</td><td>Policy + sample control evidence</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-09</td><td>Business continuity</td><td>Business Continuity Plan</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-10</td><td>Disaster recovery</td><td>DR plan + recent test evidence</td><td><span class="badge b-gap">Plan received, test missing</span></td></tr>
      <tr><td>DD-11</td><td>Data protection</td><td>Data handling / classification policy</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-12</td><td>Data retention</td><td>Retention &amp; secure disposal policy</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-13</td><td>Encryption</td><td>Encryption standard / architecture summary</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-14</td><td>Subcontractors</td><td>Fourth-party register</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-15</td><td>Security responsibilities</td><td>Contract security clauses / DPA</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-16</td><td>Service availability</td><td>SLA and availability commitments</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-17</td><td>Recovery</td><td>RTO/RPO documentation</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-18</td><td>Security contacts</td><td>Incident escalation contacts</td><td><span class="badge b-eff">Received</span></td></tr>
      <tr><td>DD-19</td><td>PCI DSS compliance</td><td>Current AOC/ROC + scope statement covering cardholder data environment</td><td><span class="badge b-gap">Not received</span></td></tr>
    </table>
    </div>
  </details>
</section>

<section>
  <h2>Control Assessment</h2>
  <p class="sub">6 representative controls tested in detail. A policy existing (design) is distinguished from it operating effectively (operating evidence).</p>
  <div class="tablewrap">
  <table>
    <tr><th>Control</th><th>Evidence</th><th>Design</th><th>Operating</th><th>Sufficiency</th><th>Overall</th></tr>
    <tr><td>MFA required for privileged access</td><td>EV-04</td><td>Effective</td><td>Not fully verified</td><td>Partial</td><td><span class="badge b-part">Partially Effective</span></td></tr>
    <tr><td>Privileged access reviewed periodically</td><td>EV-05</td><td>Effective</td><td>Partially effective — dormant account found</td><td>Sufficient to flag exception</td><td><span class="badge b-part">Partially Effective</span></td></tr>
    <tr><td>Critical vulnerabilities remediated on time</td><td>EV-06/07</td><td>Effective</td><td>Partially effective — 2 criticals overdue</td><td>Sufficient to flag exception</td><td><span class="badge b-part">Partially Effective</span></td></tr>
    <tr><td>Security incidents formally managed</td><td>EV-09/10</td><td>Effective</td><td>Effective (exercise evidence)</td><td>Sufficient</td><td><span class="badge b-eff">Effective</span></td></tr>
    <tr><td>Disaster recovery capability tested</td><td>EV-13</td><td>Requirement exists</td><td>Not determined — no test evidence</td><td>Insufficient</td><td><span class="badge b-gap">Evidence Gap</span></td></tr>
    <tr><td>PCI DSS compliance maintained and validated</td><td>DD-19</td><td>Contractual requirement exists</td><td>Not determined — no attestation received</td><td>Insufficient</td><td><span class="badge b-gap">Evidence Gap</span></td></tr>
  </table>
  </div>
</section>

<div class="grid2">
  <section>
    <h2>Findings &amp; Remediation Tracker</h2>
    <p class="sub">3 findings, 4 rows: VTF-03 links to two risks, so it appears twice below and each is tracked and reassessed independently.</p>
    <div class="tablewrap">
    <table>
      <tr><th>Finding</th><th>Linked risk</th><th>Inherent</th><th>Current residual</th><th>Owner</th><th>Status</th></tr>
      <tr><td>VTF-01 Privileged access weakness</td><td>VTR-05</td><td><span class="badge b-high">15 High</span></td><td><span class="badge b-high">15 High</span></td><td>NovaPay Risk Owner</td><td><span class="badge b-open">Open</span></td></tr>
      <tr><td>VTF-02 Vulnerability remediation delays</td><td>VTR-04</td><td><span class="badge b-high">16 High</span></td><td><span class="badge b-high">16 High</span></td><td>NovaPay Risk Owner</td><td><span class="badge b-open">Open</span></td></tr>
      <tr><td>VTF-03 DR testing evidence gap</td><td>VTR-03</td><td><span class="badge b-crit">20 Critical</span></td><td><span class="badge b-crit">20 Critical</span></td><td>Service/Risk Owner</td><td><span class="badge b-open">Open</span></td></tr>
      <tr><td>VTF-03 DR testing evidence gap</td><td>VTR-10</td><td><span class="badge b-high">15 High</span></td><td><span class="badge b-high">15 High</span></td><td>NovaPay Risk Owner</td><td><span class="badge b-open">Open</span></td></tr>
    </table>
    </div>
    <p class="sub" style="margin-top:10px">Target residual risk is not assigned numerically until remediation evidence is received and validated. The affected risks will be reassessed using the approved scoring methodology.</p>
  </section>

  <section>
    <h2>Risk Decision &amp; Acceptance</h2>
    <p class="sub">All three findings are currently routed to mitigation. No risk acceptance has been recorded.</p>
    <div class="tablewrap">
    <table>
      <tr><th>Risk</th><th>Residual (target)</th><th>Decision</th><th>Owner</th></tr>
      <tr><td>Privileged access</td><td>Not yet assigned</td><td>Mitigation required; acceptance not recorded</td><td>Technology Risk Owner</td></tr>
      <tr><td>Vulnerability delays</td><td>Not yet assigned</td><td>Remediation required; acceptance not recorded</td><td>Security Owner</td></tr>
      <tr><td>DR testing gap</td><td>Not yet assigned</td><td>Mitigation required; EXC-001 proposed / pending approval</td><td>Business Risk Owner</td></tr>
    </table>
    </div>
  </section>
</div>

<section>
  <h2>Ongoing Vendor Monitoring — KRIs</h2>
  <p class="sub">Monitoring connects measurable signals to risk, findings, ownership, escalation and reassessment. Threshold breaches do not automatically change a risk score; they trigger review and evidence-based reassessment.</p>
  <div class="tablewrap">
  <table class="kri">
    <tr><th>KRI</th><th>Measurement / Threshold</th><th>Linked Risk / Finding</th><th>Owner</th><th>Action / Escalation</th><th>Reassessment Trigger</th></tr>
    <tr><td>Critical vulnerabilities overdue</td><td>Count &gt; 0</td><td>VTR-04 / VTF-02</td><td>PayLink Security</td><td>Immediate security escalation; remediation tracking</td><td>Reassess VTR-04 if overdue exposure persists or materially changes</td></tr>
    <tr><td>Material security incidents affecting NovaPay</td><td>Any material incident</td><td>VTR-01, VTR-02, VTR-06</td><td>Vendor Security / NovaPay Incident Management</td><td>Immediate notification, incident response and risk review</td><td>Event-driven reassessment of affected risks</td></tr>
    <tr><td>DR testing</td><td>Required test overdue</td><td>VTR-03, VTR-10 / VTF-03 / EXC-001</td><td>PayLink BCM/IT</td><td>High-risk escalation; review exception status and compensating controls</td><td>Reassess VTR-03 and VTR-10 when test evidence is validated</td></tr>
    <tr><td>Privileged-access review</td><td>Required review missed</td><td>VTR-05 / VTF-01</td><td>PayLink Security</td><td>Security escalation; access review and remediation</td><td>Reassess VTR-05 after remediation evidence and follow-up testing</td></tr>
    <tr><td>SLA availability</td><td>Below contractual threshold</td><td>VTR-03 / VTR-02</td><td>NovaPay Service Owner</td><td>Vendor performance review and escalation under contract</td><td>Reassess affected availability risks if failure is material or persistent</td></tr>
    <tr><td>Open High-severity findings</td><td>Beyond agreed remediation timeframe</td><td>VTF-01, VTF-02, VTF-03</td><td>NovaPay Risk Owner</td><td>Management escalation; evaluate exception or further treatment</td><td>Reassess linked risks after remediation validation or material deterioration</td></tr>
    <tr><td>Security certification</td><td>Expired or scope no longer supports reliance</td><td>VTR-01, VTR-04, VTR-07</td><td>Third-Party Risk / Compliance</td><td>Evidence request and reassessment</td><td>Event-driven reassessment of affected risk areas</td></tr>
    <tr><td>PCI DSS attestation</td><td>Expired, scope-reduced, or not received</td><td>VTR-11</td><td>Third-Party Risk / Compliance</td><td>Evidence request and escalation; assess contractual remedies and card-brand exposure</td><td>Reassess VTR-11 when current AOC/ROC with scope statement is validated</td></tr>
  </table>
  </div>
</section>

<section>
  <h2>GRC Evidence Chain</h2>
  <div class="flow">
    <span class="node">Vendor Profile</span><span class="arrow">→</span>
    <span class="node">Business Criticality</span><span class="arrow">→</span>
    <span class="node">Inherent Risk</span><span class="arrow">→</span>
    <span class="node">Due-Diligence Evidence</span><span class="arrow">→</span>
    <span class="node">Control Assessment</span><span class="arrow">→</span>
    <span class="node">Control Effectiveness</span><span class="arrow">→</span>
    <span class="node">Residual Risk</span><span class="arrow">→</span>
    <span class="node">Risk Treatment</span><span class="arrow">→</span>
    <span class="node">Acceptance / Escalation</span><span class="arrow">→</span>
    <span class="node">Ongoing Monitoring</span>
  </div>
</section>

<footer>NovaPay Enterprise Risk Assessment — Third-Party/Vendor Risk module · Portfolio project, simulated data · Assessment scope: TPRM initial review, PCI DSS attestation outstanding at time of publication · Source: github.com/TJON-Star/NovaPay-Enterprise-Risk-Assessment</footer>
</div>
</body>
</html>
