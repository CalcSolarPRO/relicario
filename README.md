<!-- saved from url=(0116)file:///C:/Users/erazo/OneDrive/Desktop/relicario%20html/Cotiza%20tu%20joya%20%C2%B7%20Relicario%20Joyer%C3%ADa.html -->
<html lang="es"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cotiza tu joya · Relicario Joyería</title>
<link href="./index_files/css2" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --gold: #b8976a;
    --gold-light: #d4b48a;
    --dark: #1a1714;
    --dark-2: #2a2420;
    --cream: #f5f0e8;
    --cream-2: #ede7db;
    --text: #1a1714;
    --text-muted: #7a6e60;
    --border: rgba(184,151,106,0.25);
    --radius: 10px;
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Inter', sans-serif;
    background: var(--cream);
    color: var(--text);
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .header {
    width: 100%;
    background: var(--dark);
    padding: 28px 24px 24px;
    text-align: center;
    position: relative;
  }

  .header::after {
    content: '';
    display: block;
    width: 40px;
    height: 1px;
    background: var(--gold);
    margin: 16px auto 0;
  }

  .logo-symbol {
    font-size: 28px;
    color: var(--gold);
    margin-bottom: 10px;
    letter-spacing: 2px;
  }

  .brand {
    font-family: 'Cormorant Garamond', serif;
    font-size: 26px;
    font-weight: 600;
    color: var(--cream);
    letter-spacing: 6px;
  }

  .brand-sub {
    font-size: 10px;
    letter-spacing: 3px;
    color: var(--gold);
    margin-top: 4px;
    font-weight: 500;
  }

  .tagline {
    font-size: 13px;
    color: #9a8e80;
    margin-top: 10px;
    line-height: 1.6;
  }

  .container {
    width: 100%;
    max-width: 480px;
    padding: 32px 20px 48px;
  }

  .form-header {
    text-align: center;
    margin-bottom: 28px;
  }

  .form-eyebrow {
    font-size: 10px;
    letter-spacing: 3px;
    color: var(--gold);
    font-weight: 500;
    margin-bottom: 8px;
  }

  .form-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 26px;
    font-weight: 500;
    color: var(--dark);
    line-height: 1.3;
  }

  .form-subtitle {
    font-size: 13px;
    color: var(--text-muted);
    margin-top: 6px;
    line-height: 1.6;
  }

  .form-card {
    background: white;
    border: 0.5px solid var(--border);
    border-radius: 14px;
    padding: 28px 24px;
  }

  .field-group {
    margin-bottom: 20px;
  }

  .field-group:last-of-type {
    margin-bottom: 0;
  }

  label {
    display: block;
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 1.5px;
    color: var(--text-muted);
    margin-bottom: 8px;
    text-transform: uppercase;
  }

  label span.required {
    color: var(--gold);
    margin-left: 2px;
  }

  input[type="text"],
  input[type="tel"] {
    width: 100%;
    padding: 13px 16px;
    border: 0.5px solid var(--border);
    border-radius: var(--radius);
    background: var(--cream);
    font-size: 15px;
    font-family: 'Inter', sans-serif;
    color: var(--dark);
    outline: none;
    transition: border-color 0.2s;
    -webkit-appearance: none;
  }

  input[type="text"]:focus,
  input[type="tel"]:focus {
    border-color: var(--gold);
    background: white;
  }

  .options-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 8px;
  }

  .options-grid.three-col {
    grid-template-columns: 1fr 1fr 1fr;
  }

  .option-btn {
    padding: 11px 8px;
    border: 0.5px solid var(--border);
    border-radius: var(--radius);
    background: var(--cream);
    font-size: 13px;
    font-family: 'Inter', sans-serif;
    color: var(--text-muted);
    cursor: pointer;
    text-align: center;
    transition: all 0.15s;
    -webkit-tap-highlight-color: transparent;
    line-height: 1.3;
  }

  .option-btn:active {
    transform: scale(0.97);
  }

  .option-btn.selected {
    background: var(--dark);
    border-color: var(--dark);
    color: var(--gold);
    font-weight: 500;
  }

  .divider {
    height: 0.5px;
    background: var(--border);
    margin: 24px 0;
  }

  .submit-btn {
    width: 100%;
    padding: 16px;
    background: var(--dark);
    color: var(--cream);
    border: none;
    border-radius: var(--radius);
    font-size: 15px;
    font-family: 'Inter', sans-serif;
    font-weight: 500;
    cursor: pointer;
    margin-top: 24px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    transition: background 0.2s;
    -webkit-tap-highlight-color: transparent;
    letter-spacing: 0.5px;
  }

  .submit-btn:active { background: #2a2420; transform: scale(0.99); }

  .submit-btn .wa-icon {
    width: 20px;
    height: 20px;
    fill: #25D366;
  }

  .privacy-note {
    text-align: center;
    font-size: 11px;
    color: var(--text-muted);
    margin-top: 14px;
    line-height: 1.6;
  }

  .success-screen {
    display: none;
    text-align: center;
    padding: 40px 24px;
  }

  .success-screen.visible { display: block; }
  .form-card.hidden { display: none; }

  .success-icon {
    width: 56px;
    height: 56px;
    border-radius: 50%;
    background: var(--dark);
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 20px;
  }

  .success-icon svg { fill: var(--gold); width: 28px; height: 28px; }

  .success-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 26px;
    font-weight: 500;
    color: var(--dark);
    margin-bottom: 10px;
  }

  .success-text {
    font-size: 14px;
    color: var(--text-muted);
    line-height: 1.7;
    margin-bottom: 28px;
  }

  .wa-btn {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background: #25D366;
    color: white;
    padding: 15px 28px;
    border-radius: var(--radius);
    font-size: 15px;
    font-weight: 500;
    font-family: 'Inter', sans-serif;
    text-decoration: none;
    transition: background 0.2s;
  }

  .wa-btn svg { fill: white; width: 20px; height: 20px; }

  .footer {
    width: 100%;
    background: var(--dark);
    padding: 20px 24px;
    text-align: center;
    margin-top: auto;
  }

  .footer p {
    font-size: 11px;
    color: #5a5248;
    line-height: 1.8;
  }

  .footer span { color: var(--gold); }

  @media (max-width: 360px) {
    .options-grid.three-col { grid-template-columns: 1fr 1fr; }
    .brand { font-size: 22px; letter-spacing: 4px; }
  }

  @media (prefers-reduced-motion: reduce) {
    * { transition: none !important; }
  }
</style>
</head>
<body>

<div class="header">
  <div class="logo-symbol">✦</div>
  <div class="brand">RELICARIO</div>
  <div class="brand-sub">JOYERÍA · PUERTO LA CRUZ</div>
  <p class="tagline">Fabricantes de Recuerdos en Joyas</p>
</div>

<div class="container">

  <div class="form-header">
    <p class="form-eyebrow">COTIZA TU PIEZA</p>
    <h1 class="form-title">Cuéntanos tu idea</h1>
    <p class="form-subtitle">Respondemos en menos de 24 horas con opciones y precios para tu diseño.</p>
  </div>

  <div class="form-card" id="formCard">

    <div class="field-group">
      <label>Nombre <span class="required">*</span></label>
      <input type="text" id="nombre" placeholder="Tu nombre completo" autocomplete="name">
    </div>

    <div class="field-group">
      <label>Teléfono <span class="required">*</span></label>
      <input type="tel" id="telefono" placeholder="+58 412 000 0000" autocomplete="tel">
    </div>

    <div class="divider"></div>

    <div class="field-group">
      <label>¿Qué tipo de joya buscas? <span class="required">*</span></label>
      <div class="options-grid" id="tipo">
        <button class="option-btn" data-value="Anillo" onclick="select(this,&#39;tipo&#39;)">Anillo</button>
        <button class="option-btn" data-value="Collar" onclick="select(this,&#39;tipo&#39;)">Collar</button>
        <button class="option-btn" data-value="Pulsera" onclick="select(this,&#39;tipo&#39;)">Pulsera</button>
        <button class="option-btn" data-value="Aretes" onclick="select(this,&#39;tipo&#39;)">Aretes</button>
        <button class="option-btn" data-value="Otro" onclick="select(this,&#39;tipo&#39;)" style="grid-column: span 2;">Otro</button>
      </div>
    </div>

    <div class="divider"></div>

    <div class="field-group">
      <label>¿Para qué ocasión es?</label>
      <div class="options-grid" id="ocasion">
        <button class="option-btn" data-value="Compromiso" onclick="select(this,&#39;ocasion&#39;)">Compromiso</button>
        <button class="option-btn" data-value="Regalo" onclick="select(this,&#39;ocasion&#39;)">Regalo</button>
        <button class="option-btn" data-value="Aniversario" onclick="select(this,&#39;ocasion&#39;)">Aniversario</button>
        <button class="option-btn" data-value="Uso personal" onclick="select(this,&#39;ocasion&#39;)">Uso personal</button>
        <button class="option-btn" data-value="Otra ocasión" onclick="select(this,&#39;ocasion&#39;)" style="grid-column: span 2;">Otra ocasión</button>
      </div>
    </div>

    <div class="divider"></div>

    <div class="field-group">
      <label>¿Tienes un diseño en mente?</label>
      <div class="options-grid three-col" id="diseno">
        <button class="option-btn" data-value="Sí, tengo idea clara" onclick="select(this,&#39;diseno&#39;)">Sí, tengo idea</button>
        <button class="option-btn" data-value="Más o menos" onclick="select(this,&#39;diseno&#39;)">Más o menos</button>
        <button class="option-btn" data-value="Necesito asesoría" onclick="select(this,&#39;diseno&#39;)">Necesito ayuda</button>
      </div>
    </div>

    <div class="divider"></div>

    <div class="field-group">
      <label>Presupuesto aproximado</label>
      <div class="options-grid" id="presupuesto">
        <button class="option-btn" data-value="Menos de $50" onclick="select(this,&#39;presupuesto&#39;)">Menos de $50</button>
        <button class="option-btn" data-value="$50 a $150" onclick="select(this,&#39;presupuesto&#39;)">$50 – $150</button>
        <button class="option-btn" data-value="$150 a $300" onclick="select(this,&#39;presupuesto&#39;)">$150 – $300</button>
        <button class="option-btn" data-value="Más de $300" onclick="select(this,&#39;presupuesto&#39;)">Más de $300</button>
      </div>
    </div>

    <button class="submit-btn" onclick="enviar()">
      <svg class="wa-icon" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"></path>
      </svg>
      Enviar y continuar en WhatsApp
    </button>

    <p class="privacy-note">
      Tu información es privada y solo se usa para contactarte.<br>
      Nunca compartimos tus datos.
    </p>
  </div>

  <div class="success-screen" id="successScreen">
    <div class="success-icon">
      <svg viewBox="0 0 24 24"><path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"></path></svg>
    </div>
    <h2 class="success-title">¡Recibido, gracias!</h2>
    <p class="success-text">
      Tus datos quedaron guardados.<br>
      Ahora continúa en WhatsApp para que un asesor de Relicario te ayude con tu diseño.
    </p>
    <a class="wa-btn" id="waLink" href="file:///C:/Users/erazo/Downloads/relicario-formulario_3.html#">
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"></path>
      </svg>
      Abrir WhatsApp ahora
    </a>
  </div>

</div>

<div class="footer">
  <p><span>Relicario Joyería</span> · Puerto La Cruz, Anzoátegui</p>
  <p>Joyería personalizada · Diseño y fabricación propia</p>
</div>

<script>
  const WHATSAPP_NUMBER = '584121144825';
  const SHEET_URL = 'https://script.google.com/macros/s/AKfycbyhOWeJU1_me7_OFUzrKjI7N9UVJDv1Cni6MQgLMQTJkQzVAs9OKD5CjylWkmpb0GJk/exec';

  const selections = { tipo: '', ocasion: '', diseno: '', presupuesto: '' };

  function select(btn, group) {
    document.querySelectorAll('#' + group + ' .option-btn').forEach(b => b.classList.remove('selected'));
    btn.classList.add('selected');
    selections[group] = btn.dataset.value;
  }

  function getUTM() {
    const p = new URLSearchParams(window.location.search);
    return {
      source: p.get('utm_source') || 'directo',
      medium: p.get('utm_medium') || '',
      campaign: p.get('utm_campaign') || ''
    };
  }

  function buildWAMessage(data) {
    let msg = `Hola, soy ${data.nombre} y llegué desde la ficha de Google de Relicario.`;
    if (data.tipo) msg += `\n\nBusco: ${data.tipo}`;
    if (data.ocasion) msg += `\nOcasión: ${data.ocasion}`;
    if (data.diseno) msg += `\nDiseño: ${data.diseno}`;
    if (data.presupuesto) msg += `\nPresupuesto: ${data.presupuesto}`;
    msg += `\n\nTeléfono: ${data.telefono}`;
    return encodeURIComponent(msg);
  }

  async function enviar() {
    const nombre = document.getElementById('nombre').value.trim();
    const telefono = document.getElementById('telefono').value.trim();

    if (!nombre) { alert('Por favor escribe tu nombre.'); return; }
    if (!telefono) { alert('Por favor escribe tu teléfono.'); return; }
    if (!selections.tipo) { alert('Por favor selecciona el tipo de joya.'); return; }

    const utm = getUTM();
    const data = {
      nombre,
      telefono,
      tipo: selections.tipo,
      ocasion: selections.ocasion || 'No indicó',
      diseno: selections.diseno || 'No indicó',
      presupuesto: selections.presupuesto || 'No indicó',
      fuente: utm.source,
      medio: utm.medium,
      campana: utm.campaign,
      fecha: new Date().toLocaleString('es-VE', { timeZone: 'America/Caracas' })
    };

    try {
      await fetch(SHEET_URL, {
        method: 'POST',
        mode: 'no-cors',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(data)
      });
    } catch(e) {}

    const waMsg = buildWAMessage(data);
    const waURL = `https://wa.me/${WHATSAPP_NUMBER}?text=${waMsg}`;

    document.getElementById('waLink').href = waURL;
    document.getElementById('formCard').classList.add('hidden');
    document.getElementById('successScreen').classList.add('visible');

    setTimeout(() => { window.location.href = waURL; }, 1800);
  }
</script>



</body></html>
