# Documentación de Landing Page: Alejandro Gonzalez - Servicios de Refrigeración

Esta documentación contiene la estructura textual, visual y sugerencias de UI y SEO para la landing page. El archivo `index.html` generado de manera conjunta ya contiene la implementación práctica de estas directrices.

## Texto y Estructura

### 1. Hero (Sección Principal)
**Elementos Visuales:** Imagen de fondo oscura (tipo gradiente azulado) con aire acondicionado sutil para resaltar texto blanco.
- **Micro-título superior (Badge):** Técnico Especialista en Refrigeración
- **Título principal (H1):** Instalación y service de aire acondicionado profesional
- **Subtítulo:** Atención rápida y técnicos especializados en CABA y Gran Buenos Aires. Expertos en hogar, comercio y sistemas VRV/VRF.
- **CTA Principal:** "Solicitar presupuesto por WhatsApp" al 11 4174-0392 (Botón verde distintivo con ícono)

### 2. Servicios
**Elementos Visuales:** Grilla de 4 tarjetas (Cards) con íconos representativos (Aires, llaves, escoba de limpieza, edificio). Efecto "Hover" (se elevan al pasar el mouse por encima).
- **Instalación de Splits (hogar y oficina):** Instalaciones prolijas y seguras. Respetamos las indicaciones del fabricante para validar tu garantía.
- **Reparación de aire acondicionado:** Diagnóstico preciso y solución de fallas (pérdidas de gas, problemas eléctricos, placas).
- **Mantenimiento preventivo:** Limpieza profunda de unidades interior y exterior, control de carga de gas.
- **Sistemas VRV/VRF (empresas):** Enfoque y diseño destacado (borde y sombreado). Atención prioritaria para empresas y edificios. Instalación y mantenimiento preventivo/correctivo.

### 3. Sobre el técnico
**Elementos Visuales:** Layout de dos columnas. Izquierda: foto de manos del técnico trabajando en sistema VRV/VRF (manos a la obra y especialidad técnica). Derecha: textos descriptivos y viñetas.
- **Título:** Conocé al técnico a cargo
- **Texto:** "Soy Alejandro Gonzalez, técnico especializado en refrigeración... Mi objetivo es brindarte tranquilidad..." 
- **Viñetas de valor:** 
  - Experiencia técnica certificada
  - Enfoque en prolijidad y limpieza en el trabajo
  - Puntualidad y cumplimiento de horarios

### 4. Diferenciales
**Elementos Visuales:** 4 bloques con íconos destacados en Azul principal.
- **Atención rápida:** Respuesta y coordinación inmediata.
- **Presupuestos sin cargo:** Asesoramiento claro.
- **CABA y GBA:** Amplia zona de cobertura para comodidad del cliente.
- **Servicio a domicilio:** Vamos con las herramientas listas.

### 5. Cómo Funciona
**Elementos Visuales:** 3 pasos enumerados con números grandes y destacados dentro de círculos. 
- **Paso 1:** Contacto por WhatsApp (Diagnóstico base)
- **Paso 2:** Diagnóstico / Presupuesto (Directo sin sorpresas)
- **Paso 3:** Resolución rápida (Limpio y efectivo)

### 6. Casos Reales y Prueba Social
**Elementos Visuales:** Entorno oscuro para dar contraste y seriedad. Tarjetas con testimonios, estrellas amarillas y perfiles de los clientes.
- Ejemplos incluidos: "Instalación en departamento" y "Reparación comercial".

### 7. FAQ (Preguntas Frecuentes)
**Elementos Visuales:** Sistema de acordeón. Las preguntas se despliegan al hacer clic.
- ¿Cuánto tarda una instalación? (Resp: 2 a 4 hs en promedio, de manera prolija)
- ¿Hacen service a domicilio? (Resp: Sí, brindamos servicio completo al domicilio/comercio)
- ¿Trabajan fines de semana? (Resp: Coordinaciones posibles según disponibilidad u urgencias)
- ¿Cuál es su zona de cobertura? (Resp: Instalación y mantenimiento en CABA y Gran Buenos Aires)

### 8. Final CTA (Call to Action Final)
**Elementos Visuales:** Franja ancha, con un gradiente azul brillante que invita a no irse sin contactar.
- **Título:** Pedí tu presupuesto ahora
- **Subtítulo:** Dejá tu equipo en buenas manos. Contactame hoy mismo.
- **Botón grande:** "Enviar mensaje al técnico" > Dirige directo al WhatsApp.


---

## Sugerencias de UI (User Interface) aplicadas en el diseño
1. **Botón Flotante de WhatsApp:** Hemos colocado un botón fijo que palpita sutilmente (`pulse-wa` animation) en la esquina inferior derecha. Esto ataca directamente tu objetivo de "generar consultas inmediatas".
2. **Mobile First & Responsive:** La grilla de tarjetas y el diseño general fluirán a una sola columna en pantallas móviles. La fuente es de alta legibilidad (`Inter` Font), clave para usuarios en celular.
3. **Colores de Confianza:** 
   - Primario: Azul Hielo (`#0ea5e9`) asociado a lo técnico, la refrigeración y profesionalismo.
   - Secundario: Azul Noche / Gris Oscuro (`#0f172a`) que le aporta modernidad y alto perfil.
4. **Tarjetas Elevables (Hover Cards):** Crean un sitio moderno y dinámico que no parece un "sitio viejo abandonado", aumentando drásticamente la confianza del usuario (Trust factor).
5. **Clear Call to Actions:** Hay un botón de contacto persistente en el header, otro inmenso en el Hero inicial, el flotante omnipresente y uno masivo al final de la página.

---

## Estrategia SEO On-Page

La landing page se optimizó estructuralmente de la siguiente manera:
1. **Title Tag:** `<title>Alejandro Gonzalez | Instalación y Service de Aire Acondicionado Profesional</title>` 
2. **H1 Único:** Contiene "Instalación", "service de aire acondicionado", y en combinación con los subtítulos funciona perfecto para los términos de búsqueda deseados.
3. **Meta Keywords and Description:** Se introdujeron explícitamente palabras como: "instalación aire acondicionado CABA", "service aire acondicionado Gran Buenos Aires", "sistemas VRV VRF", "técnico refrigeración".
4. **Estructura semántica de Etiquetas:** Uso correcto de etiquetas HTML5 (`<header>`, `<section>`, `<nav>`, `<footer>`) e intertítulos (`H2`, `H3`) que Google prioriza para entender el contexto.
5. **Velocidad:** Al estar creada íntegramente en Vanilla CSS (Cero librerías externas pesadas), cargará de manera casi inicial en dispositivos móviles, lo que Google toma como factor clave en el posicionamiento (Core Web Vitals).
