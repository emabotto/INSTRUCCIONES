# 🌱 Generador de Códigos QR - FFO SA

Este script genera códigos QR para la empresa FFO SA con diferentes estilos y formatos.

## 📋 Requisitos

- Python 3.6 o superior
- Librerías: `qrcode` y `Pillow`

## 🚀 Instalación

### Opción 1: Instalación automática
```bash
python generar_qr.py
```
El script instalará automáticamente las dependencias necesarias.

### Opción 2: Instalación manual
```bash
pip install -r requirements.txt
```

## 🎯 Uso

```bash
python generar_qr.py
```

## 📁 Archivos Generados

El script crea una carpeta `qr_codes` con los siguientes archivos:

### 🌐 Página Web
- `ffo_web.png` - QR simple para la página web
- `ffo_web_estilizado.png` - QR con colores de FFO (verde)
- `ffo_web_con_logo.png` - QR con logo de FFO en el centro

### 📞 Contacto
- `ffo_email.png` - QR para enviar email
- `ffo_telefono.png` - QR para llamar por teléfono
- `ffo_ubicacion.png` - QR para ubicación en mapas
- `ffo_contacto_completo.png` - QR con información completa (vCard)

## 🎨 Características

- **QR Simple**: Códigos básicos en blanco y negro
- **QR Estilizado**: Códigos con colores corporativos de FFO
- **QR con Logo**: Códigos con logo de FFO en el centro
- **Múltiples formatos**: Web, email, teléfono, ubicación, vCard

## 💡 Usos Recomendados

- **Tarjetas de presentación**: QR con información de contacto
- **Material promocional**: QR para la página web
- **Sitio web**: QR para compartir fácilmente
- **Redes sociales**: QR para promocionar la empresa

## 🔧 Personalización

Puedes modificar el archivo `generar_qr.py` para:
- Cambiar los colores corporativos
- Agregar más información de contacto
- Modificar el diseño del logo
- Ajustar el tamaño de los códigos QR

## 📱 Compatibilidad

Los códigos QR generados son compatibles con:
- Cámaras de teléfonos móviles
- Aplicaciones de escaneo de QR
- Navegadores web
- Aplicaciones de contactos (vCard)
