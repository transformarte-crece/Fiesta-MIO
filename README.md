<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Boarding Pass · Fiesta Navideña MIO</title>
<style>
:root{--bg:#e9ebf5;--fg:#25234a;--card:#ffffff;--pu:#4e4c91;--or:#E67A2F;--mut:#6b6a8f;--ln:#d5d7e8}
@media (prefers-color-scheme:dark){:root{color-scheme:dark;--bg:#15142b;--fg:#f1f0fb;--card:#211f40;--mut:#a9a8cf;--ln:#3a3866}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--fg);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;display:flex;align-items:center;justify-content:center;padding:calc(20px + env(safe-area-inset-top,0px)) 14px calc(20px + env(safe-area-inset-bottom,0px))}
.ticket{width:100%;max-width:420px;background:var(--card);border-radius:20px;overflow:hidden;box-shadow:0 10px 30px rgba(40,30,90,.18)}
.head{background:linear-gradient(90deg,#4e4c91,#de6b29);color:#fff;padding:16px 18px;display:flex;align-items:center;gap:12px}
.logo{background:#fff;border-radius:12px;padding:5px 10px;height:46px;width:auto;display:block}
.head h1{margin:0;font-size:1.15rem;letter-spacing:.14em;font-weight:800;flex:1;text-align:right}
.head .plane{font-size:1.5rem;transform:rotate(-8deg)}
.body{padding:18px 20px 8px}
.ev{font-size:.72rem;letter-spacing:.12em;color:var(--mut);text-transform:uppercase}
.evn{font-size:1.45rem;font-weight:800;margin:0 0 14px;color:var(--pu)}
@media (prefers-color-scheme:dark){.evn{color:#fff}}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:12px 14px;margin-bottom:12px}
.grid .full{grid-column:1/-1}
.k{font-size:.68rem;letter-spacing:.08em;color:var(--mut);text-transform:uppercase}
.v{font-weight:800;font-size:1.02rem}
.tear{position:relative;border-top:2px dashed var(--ln);margin:6px 0 0}
.tear::before,.tear::after{content:"";position:absolute;top:-13px;width:24px;height:24px;border-radius:50%;background:var(--bg)}
.tear::before{left:-12px}.tear::after{right:-12px}
.stub{padding:18px 20px 22px;text-align:center}
.stub h2{margin:0 0 4px;font-size:1.05rem;letter-spacing:.06em;color:var(--or);text-transform:uppercase}
.stub p{margin:0 0 14px;color:var(--mut);font-size:.95rem}
label.btn{display:inline-block;background:linear-gradient(90deg,#d9622a,#E67A2F);color:#fff;border-radius:999px;padding:15px 30px;font-size:1.05rem;font-weight:800;cursor:pointer;box-shadow:0 4px 12px rgba(230,122,47,.4)}
input[type=file]{display:none}
#track{position:relative;height:6px;border-radius:99px;background:var(--ln);margin:30px 6px 4px;display:none}
#fill{height:100%;width:0;border-radius:99px;background:linear-gradient(90deg,var(--pu),var(--or));transition:width .25s}
#jet{position:absolute;top:-17px;left:0;font-size:1.3rem;transform:translateX(-50%);transition:left .25s}
#st{margin-top:12px;min-height:1.4em;font-weight:600}
.foot{font-style:italic;color:var(--or);font-weight:700;margin-top:14px}
</style>
</head>
<body>
<div class="ticket">
  <div class="head">
    <img class="logo" alt="MIO" src="data:image/png;base64,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">
    <h1>BOARDING PASS</h1>
    <span class="plane">✈</span>
  </div>
  <div class="body">
    <div class="ev">Destino celebración</div>
    <p class="evn">Fiesta Navideña MIO</p>
    <div class="grid">
      <div><div class="k">De / From</div><div class="v">Mis fotos</div></div>
      <div><div class="k">A / To</div><div class="v">Álbum MIO</div></div>
      <div><div class="k">Fecha / Date</div><div class="v">10 de diciembre</div></div>
      <div><div class="k">Terminal</div><div class="v">TresSDQ</div></div>
    </div>
  </div>
  <div class="tear"></div>
  <div class="stub">
    <h2>Check-in de fotos</h2>
    <p>Elige las fotos que tomaste y embárcalas al álbum de la fiesta.</p>
    <label class="btn" for="f">✈ Subir fotos</label>
    <input id="f" type="file" accept="image/*" multiple>
    <div id="track"><div id="fill"></div><span id="jet">✈</span></div>
    <div id="st"></div>
    <div class="foot">¡Comparte tus mejores momentos!</div>
  </div>
</div>
<script>
// Configuración de Cloudinary: subida directa desde el navegador.
const CLOUD_NAME = "o5nzameq";
const UPLOAD_PRESET = "fiesta_mio_2026";
const MAX_DIMENSION = 2000;
const JPEG_QUALITY = 0.88;
const MAX_FILE_SIZE = 15 * 1024 * 1024; // 15 MB por fotografía antes de comprimir
const $ = id => document.getElementById(id);

function toJpegBlob(file) {
  return new Promise((resolve, reject) => {
    const objectUrl = URL.createObjectURL(file);
    const img = new Image();
    img.onload = () => {
      try {
        const scale = Math.min(1, MAX_DIMENSION / Math.max(img.width, img.height));
        const canvas = document.createElement("canvas");
        canvas.width = Math.max(1, Math.round(img.width * scale));
        canvas.height = Math.max(1, Math.round(img.height * scale));
        const context = canvas.getContext("2d");
        if (!context) throw new Error("No se pudo procesar la fotografía en este navegador.");
        context.fillStyle = "#ffffff";
        context.fillRect(0, 0, canvas.width, canvas.height);
        context.drawImage(img, 0, 0, canvas.width, canvas.height);
        canvas.toBlob(blob => {
          URL.revokeObjectURL(objectUrl);
          if (blob) resolve(blob);
          else reject(new Error("No se pudo convertir la fotografía."));
        }, "image/jpeg", JPEG_QUALITY);
      } catch (error) {
        URL.revokeObjectURL(objectUrl);
        reject(error);
      }
    };
    img.onerror = () => {
      URL.revokeObjectURL(objectUrl);
      reject(new Error("No se pudo abrir esta imagen."));
    };
    img.src = objectUrl;
  });
}

function setPct(percent) {
  $("fill").style.width = percent + "%";
  $("jet").style.left = percent + "%";
}

async function uploadToCloudinary(file, index) {
  if (!file.type.startsWith("image/")) {
    throw new Error("El archivo no es una imagen.");
  }
  if (file.size > MAX_FILE_SIZE) {
    throw new Error("La fotografía supera el límite de 15 MB.");
  }

  const blob = await toJpegBlob(file);
  const safeBaseName = (file.name || "foto").replace(/\.[^.]+$/, "").replace(/[^a-zA-Z0-9_-]/g, "_").slice(0, 50);
  const fileName = safeBaseName + "_" + Date.now() + "_" + index + ".jpg";
  const formData = new FormData();
  formData.append("file", blob, fileName);
  formData.append("upload_preset", UPLOAD_PRESET);

  const endpoint = "https://api.cloudinary.com/v1_1/" + CLOUD_NAME + "/image/upload";
  const response = await fetch(endpoint, { method: "POST", body: formData });
  let result;
  try { result = await response.json(); }
  catch { throw new Error("Cloudinary respondió con un formato inesperado (HTTP " + response.status + ")."); }

  if (!response.ok) {
    const message = result?.error?.message || ("Error HTTP " + response.status);
    throw new Error(message);
  }
  return result;
}

$("f").onchange = async event => {
  const files = Array.from(event.target.files || []);
  event.target.value = "";
  if (!files.length) return;

  $("track").style.display = "block";
  setPct(0);
  $("st").textContent = "Preparando " + files.length + " fotografía(s)…";
  let uploaded = 0;
  const errors = [];

  for (let i = 0; i < files.length; i++) {
    $("st").textContent = "Subiendo fotografía " + (i + 1) + " de " + files.length + "…";
    try {
      await uploadToCloudinary(files[i], i + 1);
      uploaded++;
    } catch (error) {
      errors.push(files[i].name + ": " + (error?.message || "Error desconocido"));
    }
    setPct(Math.round(((i + 1) / files.length) * 100));
  }

  if (uploaded === files.length) {
    $("st").textContent = "¡Aterrizaje exitoso! " + uploaded + " foto(s) guardadas en el álbum 🎉";
  } else if (uploaded > 0) {
    $("st").textContent = "Se subieron " + uploaded + " de " + files.length + " fotografías. Primer error: " + (errors[0] || "revisa la consola del navegador.");
  } else {
    $("st").textContent = "No se pudo subir ninguna fotografía. " + (errors[0] || "Revisa tu conexión y la configuración del preset.");
  }
  if (errors.length) console.error("Errores de subida a Cloudinary:", errors);
};
</script>
</body>
</html>
