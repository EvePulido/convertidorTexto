# 📄 Conversor de Documentos

Aplicación web local para convertir documentos entre los formatos más comunes. Todo el procesamiento ocurre en tu computadora — ningún archivo se sube a ningún servidor.

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple?logo=bootstrap&logoColor=white)
![License](https://img.shields.io/badge/licencia-MIT-green)

---

## ✨ Formatos soportados

| Formato | Extensión | Descripción |
|--------|-----------|-------------|
| Texto plano | `.txt` | Sin formato, solo texto |
| Word | `.docx` | Documento con formato de Microsoft Word |
| PDF | `.pdf` | Formato de documento portátil |
| Rich Text | `.rtf` | Texto con formato básico |
| Página web | `.html` | Lenguaje de marcado de hipertexto |
| OpenDocument | `.odt` | Formato de LibreOffice / OpenOffice |

Todos los formatos se pueden convertir entre sí en ambas direcciones.

---

## 🚀 Instalación y uso

### 1. Clona el repositorio

```bash
git clone https://github.com/tu-usuario/conversor-documentos.git
cd conversor-documentos
```

### 2. Instala las dependencias

```bash
pip install -r requirements.txt
```

### 3. Ejecuta la aplicación

```bash
python conversor_documentos.py
```

Se abrirá automáticamente en tu navegador en `http://127.0.0.1:8765`

---

## 📦 Dependencias

```
python-docx
reportlab
pdfplumber
odfpy
beautifulsoup4
lxml
pypdf
```

---

## 🖥️ Capturas

> La interfaz usa Bootstrap 5 con un diseño limpio y minimalista.
> Soporta arrastrar y soltar archivos directamente en la pantalla.

---

## 🔒 Privacidad

Este conversor funciona **100% de forma local**. Ningún archivo es enviado a servidores externos. Todo se procesa en tu propia máquina.

---

## 📝 Licencia

MIT — libre para usar, modificar y distribuir.
