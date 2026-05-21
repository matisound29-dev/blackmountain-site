# Homepage
type: "widget_page"

# Hero Section
widget: "hero"
headless: true
active: true
weight: 10
title: "Black Mountain Bikes"
hero_media: "images/hero-bg.jpg" # 👈 Reemplaza con tu imagen de fondo
cta:
  label: "**Comenzar →**"
  url: "#product-finder"
cta_alt:
  label: ""
  url: ""
cta_note:
  label: "⬅️ Encontrá el repuesto ideal para tu nave. Respondé 3 preguntas y te mostramos los componentes compatibles."

# How It Works Section
widget: "featurette"
headless: true
active: true
weight: 20
title: "Cómo compramos"
subtitle: ""
features:
- icon: "whatsapp"
  icon_pack: "fab"
  name: "Todo por WhatsApp"
  description: "Los precios están en USD"
- icon: "truck"
  icon_pack: "fas"
  name: "Envíos a todo el país"
  description: "Preguntá sin compromiso"
- icon: "wrench"
  icon_pack: "fas"
  name: "Asesoramiento post-venta"
  description: "Te guiamos después de la compra"

# Features Section
widget: "featurette"
headless: true
active: true
weight: 30
title: "Por qué Black Mountain"
subtitle: ""
features:
- icon: "box"
  icon_pack: "fas"
  name: "Stock real en Argentina"
  description: ""
- icon: "mountain"
  icon_pack: "fas"
  name: "Repuestos de desarme premium"
  description: "DT Swiss, Maxxis, Renthal"
- icon: "comments"
  icon_pack: "fas"
  name: "Trato de taller"
  description: "Directo y honesto"

# Testimonials Section
widget: "testimonials"
headless: true
active: true
weight: 40
title: "Testimonios"
subtitle: ""
testimonials:
- author: "Cliente 1"
  role: ""
  text: "Me asesoraron perfecto, justo lo que necesitaba"
- author: "Cliente 2"
  role: ""
  text: "Llegó rápido y el producto impecable"

# Products Section
widget: "featurette"
headless: true
active: true
weight: 50
title: "Productos destacados"
subtitle: ""
features:
- icon: "bicycle"
  icon_pack: "fas"
  name: "Maza DT Swiss 350"
  description: "Enganche inmediato, para darle masa sin miedo"
- icon: "bicycle"
  icon_pack: "fas"
  name: "Cubierta Maxxis Shorty 2.4"
  description: "Auto-limpieza, tracción en barro líquido"
# 👇 Sigue esta estructura para agregar más productos

# Product Finder Placeholder
widget: "blank"
headless: true
active: true
weight: 60
title: "Buscador Inteligente de Productos"
subtitle: "Contestá las preguntas y encontrá el componente ideal"
design:
  columns: "1"
  css_style: "margin-top: 2rem;"
advanced:
  css_class: "product-finder"
