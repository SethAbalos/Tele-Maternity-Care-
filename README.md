# Tele-Maternity-Care-
Tele-Maternity Care website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Tele-Maternity Care: A telehealth solution to improve maternal care in remote barangays of Butuan City." />
  <meta name="keywords" content="maternity, telehealth, Butuan, maternal health, Philippines, healthcare" />
  <meta name="author" content="Tele-Maternity Care Team" />
  <title>Tele-Maternity Care</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9fc;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #e3dafc;
      padding: 2rem;
      text-align: center;
      color: #4a148c;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #d1c4e9;
      padding: 0.5rem;
    }
    nav a {
      color: #4a148c;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: 600;
    }
    section {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem 2rem;
      background: white;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
      position: relative;
    }
    h2 {
      color: #6a1b9a;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    h2 img {
      height: 32px;
      width: 32px;
    }
    ul {
      margin-left: 1.5rem;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #ede7f6;
      color: #6a1b9a;
    }
    a.source-link {
      display: block;
      color: #1e88e5;
    }
    /* Hero banner */
    .hero-image {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      border-radius: 0 0 20px 20px;
      margin-bottom: 1.5rem;
    }
    /* Responsive tweaks */
    @media (max-width: 600px) {
      section {
        padding: 1rem;
      }
      nav {
        flex-direction: column;
        gap: 0.5rem;
      }
      nav a {
        margin: 0;
      }
      h2 {
        font-size: 1.4rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Tele-Maternity Care</h1>
    <p>Addressing Delayed Maternal Healthcare Through Real-Time Remote Access</p>
  </header>

  <img 
    src="https://images.unsplash.com/photo-1588776814546-cf91f3f61fa7?auto=format&fit=crop&w=1200&q=80" 
    alt="Pregnant woman receiving care" 
    class="hero-image" 
  />

  <nav>
    <a href="#problem">Problem</a>
    <a href="#solution">Solution</a>
    <a href="#impact">Impact</a>
    <a href="#funding">Funding</a>
  </nav>

  <section id="problem">
    <h2>
      <img src="https://cdn-icons-png.flaticon.com/512/565/565547.png" alt="Problem icon" />
      1. Problem Statement
    </h2>
    <p>In Butuan City’s remote barangays, pregnant women often face delays in accessing skilled maternity care due to:</p>
    <ul>
      <li>Absence of permanent nurses in rural health centers.</li>
      <li>Limited skills of barangay health workers (BHWs) in handling deliveries and emergencies.</li>
      <li>Long travel times to hospitals, especially during complications.</li>
    </ul>
    <p>This leads to higher maternal and neonatal mortality rates from preventable causes like hemorrhage, eclampsia, and neonatal asphyxia.</p>

    <h3>Prevalence Data in Butuan City (If Available)</h3>
    <ul>
      <li>PSA 2022: Caraga Region recorded 85 maternal deaths per 100,000 live births, higher than the national average (78).</li>
      <li>DOH Reports: Delays contribute to 30% of maternal deaths in rural areas.</li>
      <li>UNICEF Philippines: Neonatal mortality is 12 deaths per 1,000 live births (2021).</li>
    </ul>
    <p>Sources:</p>
    <a class="source-link" href="https://psa.gov.ph" target="_blank" rel="noopener noreferrer">Philippine Statistics Authority (PSA)</a>
    <a class="source-link" href="https://caraga.doh.gov.ph" target="_blank" rel="noopener noreferrer">Department of Health (DOH) Caraga</a>
    <a class="source-link" href="https://www.unicef.org/philippines/" target="_blank" rel="noopener noreferrer">UNICEF Philippines - Maternal & Child Health</a>
  </section>

  <section id="solution">
    <h2>
      <img src="https://cdn-icons-png.flaticon.com/512/2748/2748558.png" alt="Solution icon" />
      2. Proposed Solution: "Tele-Mat Care" – Remote Maternity Support System
    </h2>
    <p>A real-time telemedicine platform connecting isolated barangays to obstetricians and midwives in Butuan City hospitals.</p>

    <h3>Key Features</h3>
    <ul>
      <li><strong>24/7 Teleconsultations</strong> – BHWs use a tablet/phone to connect with doctors during emergencies.</li>
      <li><strong>AI-Powered Triage Tool</strong> – Assesses risk factors and alerts specialists.</li>
      <li><strong>Mobile Training for BHWs</strong> – App-based tutorials on emergency delivery, neonatal CPR, and danger signs.</li>
      <li><strong>Emergency Transport Coordination</strong> – Links with ambulances or maternity waiting homes near hospitals.</li>
    </ul>

    <h3>Implementation Plan</h3>
    <ul>
      <li>Pilot Barangays: Partner with 3–5 high-risk areas (e.g., mountainous or far-flung zones).</li>
      <li>Device Distribution: Provide BHWs with tablets + portable Doppler/USG devices.</li>
      <li>Hospital Linkage: Butuan Medical Center or CARAGA Regional Hospital as the hub.</li>
      <li>Monitoring: Track reductions in delayed care and mortality over 12 months.</li>
    </ul>
  </section>

  <section id="impact">
    <h2>
      <img src="https://cdn-icons-png.flaticon.com/512/1077/1077035.png" alt="Impact icon" />
      3. Expected Impact
    </h2>
    <ul>
      <li>↓ Maternal & neonatal deaths by 30% in pilot areas.</li>
      <li>↑ Skilled birth attendance via remote guidance.</li>
      <li>↓ Referral delays through real-time coordination.</li>
    </ul>
  </section>

  <section id="funding">
    <h2>
      <img src="https://cdn-icons-png.flaticon.com/512/1995/1995574.png" alt="Funding icon" />
      4. Funding & Partnerships
    </h2>
    <ul>
      <li><strong>Local Government</strong> (Butuan City Health Office) – Policy support and BHW training.</li>
      <li><strong>DOH & PhilHealth</strong> – Potential coverage under telemedicine benefits.</li>
      <li><strong>NGOs</strong> (e.g., UNICEF, WHO) – Grants for rural maternal health tech.</li>
    </ul>
  </section>

  <footer>
    <p>© 2025 Tele-Maternity Care | Empowering Safe Motherhood in Remote Communities</p>
  </footer>
</body>
</html>
