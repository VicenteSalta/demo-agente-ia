# 🤖 Demo Agente IA: Cotizador Automático

Este proyecto implementa un agente de inteligencia artificial capaz de generar cotizaciones personalizadas, exportarlas en PDF y enviarlas por correo electrónico.

## 🚀 Funcionalidades
- Recopila nombre, correo y producto de interés.
- Genera un resumen del producto usando GPT-4 Turbo (LangChain).
- Crea un archivo PDF con la cotización.
- Envía el archivo por correo utilizando SendGrid.

## 📦 Requisitos
- Python 3.8+
- API Key de OpenAI
- Cuenta de SendGrid con correo remitente verificado

## 🔧 Instalación
```bash
git clone https://github.com/tu_usuario/demo-agente-ia.git
cd demo-agente-ia
pip install -r requirements.txt
cp .env.example .env  # luego edita .env con tus credenciales
```

## 🧪 Ejecutar localmente
```bash
streamlit run streamlit_app.py
```

## ☁️ Despliegue en Streamlit Cloud
1. Subí este repositorio a tu cuenta de GitHub.
2. Ingresá a https://streamlit.io/cloud
3. Conectá tu cuenta GitHub y seleccioná el repositorio.
4. En la sección `Secrets`, añadí:
    - EMAIL_REMITENTE
    - SENDGRID_USER
    - SENDGRID_API_KEY
5. ¡Listo! Tu app tendrá una URL pública.

## 📄 Licencia
MIT
