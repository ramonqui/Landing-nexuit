# Contexto para Landing Page de Nexuit

## Proposito

Este documento sirve como brief maestro para alinear la landing page comercial de Nexuit con el SaaS real.
Debe usarse en el repositorio de marketing/landing para definir mensajes, estructura, tono visual, CTAs y limites de promesa.

No reemplaza la documentacion tecnica del producto.
Su funcion es traducir el sistema operativo de Nexuit a una narrativa clara para clientes potenciales.

## Gobierno del documento

Este brief es parte del contexto vivo de Nexuit.
Debe actualizarse con la misma disciplina que `AGENTS/**` cuando cambie una decision que afecte posicionamiento, promesa comercial, modulos vendibles, rutas publicas, trial, onboarding, planes, capabilities o superficies de experiencia.

Owner documental:

- `Product Owner Agent` define posicionamiento y limites de promesa.
- `Documentation Context Agent` mantiene el brief sincronizado con `AGENTS/**` y `docs/contexto-maestro-para-chatgpt.md`.
- `UI Design Agent` revisa tono visual cuando la landing cambia componentes, estilo o direccion grafica.

Triggers obligatorios de actualizacion:

- se agrega o retira una capability comercial importante
- cambia el onboarding o el registro publico
- cambia el trial o la politica de planes
- cambia la estrategia `WEB_DESKTOP`, `WEB_MOBILE_FIRST` o `FLUTTER_NATIVE`
- se habilita productivamente tienda propia, marketplace, facturacion fiscal u otra promesa comercial fuerte
- cambia el CTA principal, dominio publico o rutas `/register` y `/login`
- se detecta que la landing promete algo que el SaaS aun no cumple

Evidencia minima al actualizar:

- `git diff --check`
- decision registrada en `AGENTS/16-decision-log.md` si cambia regla o posicionamiento
- snapshot actualizado en `AGENTS/17-module-status.md` si cambia estado comercial o modulo visible

## Que es Nexuit

Nexuit es una suite SaaS multi-tenant para operar negocios con inventario fisico y venta multicanal.
Ayuda a controlar productos, stock, sucursales, almacenes, ventas fisicas, POS, ventas online, despachos, compras y fabricacion desde un mismo sistema modular.

La direccion final del producto incluye que el usuario pueda crear su propia tienda en linea usando el mismo catalogo, variantes, SKUs, precios, stock y reglas operativas del sistema.
La landing debe presentar esta direccion como parte natural de Nexuit: el inventario es el nucleo que alimenta tanto la venta fisica como la venta online.

La promesa central:

> Controla tu operacion desde inventario hasta venta fisica u online, sin perder visibilidad entre sucursales, almacenes y equipos.

Nexuit debe sentirse como una herramienta profesional para operar el negocio todos los dias, no como una landing decorativa ni como un sistema burocratico.

## Que no es Nexuit

- No es un ERP generico.
- No es solo un CRUD administrativo.
- No es un software contable.
- No es una herramienta fiscal local.
- No es un videojuego ni una app visualmente ruidosa.
- No es una plantilla bonita sin operacion real.

## Cliente ideal

La landing debe hablarle principalmente a negocios que ya sienten friccion operativa:

- tiendas con inventario fisico
- negocios con una o varias sucursales
- fabricas pequenas o medianas
- marcas que venden por tienda fisica, mostrador, POS, tienda online o canales digitales
- equipos que necesitan controlar bodegas, almacenes, ubicaciones y movimientos
- operaciones que crecen y empiezan a perder orden en hojas de calculo, libretas o sistemas aislados

El usuario debe sentir:

- "esto entiende mi operacion"
- "puedo empezar rapido"
- "no necesito llenar formularios eternos"
- "mi inventario, ventas fisicas, ventas online y salidas van a hablar entre si"

## Posicionamiento

Nexuit es una suite operativa modular.

No venderlo como "ERP completo" en primer plano.
La palabra ERP puede aparecer solo si es necesario para comparacion, pero no debe ser la identidad principal.

Formula recomendada:

> Nexuit es la suite SaaS para ordenar inventario, ventas fisicas, ventas online y operacion en negocios que crecen.

Alternativas de headline:

- "Opera inventario, ventas fisicas, ventas online y despachos sin perder control."
- "Una suite para ordenar tu negocio desde el stock hasta cada venta."
- "Inventario, ventas y operacion multicanal en una sola suite SaaS."
- "Control real para negocios con productos, sucursales, almacenes y canales digitales."

Evitar headlines vagos:

- "La plataforma que transforma tu negocio"
- "El futuro de la gestion empresarial"
- "Todo en uno para empresas"

## Mensaje principal

El mensaje debe conectar tres ideas:

1. Nexuit organiza la base operativa: productos, sucursales, almacenes y ubicaciones.
2. Nexuit conecta esa base con ventas fisicas, POS, ventas online y despachos.
3. Nexuit permite crecer por modulos y planes, sin forzar complejidad desde el primer dia.

Copy base:

> Empieza con inventario ordenado. Conecta POS, ventas online y despachos. Activa mas capacidades conforme tu operacion crece.

## Diferenciales reales del producto

Usar como bloques de valor:

- Multi-sucursal: ver operacion general o filtrar por sucursal.
- Multi-almacen: controlar stock por almacenes y ubicaciones internas.
- Catalogo operativo: productos maestros, variantes, SKUs, codigos y stock por ubicacion.
- Ventas conectadas: venta fisica u online, reserva, despacho, picking, packing y envio.
- POS y venta directa: entrada rapida para operacion de mostrador.
- Tienda online propia: direccion estrategica para vender en linea desde el mismo catalogo e inventario operativo.
- Comercio multicanal: catalogo comercial, atributos y preparacion para tienda propia o marketplace.
- Compras y proveedores: recepcion y seguimiento de abastecimiento.
- Fabricacion: estructura para negocios que producen o ensamblan.
- Planes por capacidades: cada negocio activa lo que necesita segun su plan.
- Onboarding guiado: crear empresa y estructura minima sin friccion.
- Web desktop y web mobile-first: escritorio para supervisar; navegador movil para operar rapido.
- App Flutter nativa en evolucion: enfocada en bodega, scanner y operacion fisica.

## Pilares narrativos

### 1. Orden desde la base

Nexuit empieza por la infraestructura operativa:

- empresa
- sucursales
- almacenes
- ubicaciones internas
- productos
- variantes
- stock

Mensaje:

> Si tu inventario no esta claro, todo lo demas se vuelve friccion.

### 2. Operacion conectada

El sistema no debe verse como modulos aislados.
La landing debe mostrar que inventario, POS, ventas online, despachos y compras se conectan.

Mensaje:

> Cada venta, fisica u online, sabe de donde saldra el producto. Cada movimiento deja rastro. Cada sucursal conserva contexto.

### 3. Crecimiento modular

Nexuit no obliga a usar todo desde el dia uno.
Los planes y capabilities permiten activar capacidades por etapa.

Mensaje:

> Empieza simple y activa mas capacidades cuando tu negocio lo pida.

### 4. Velocidad sin desorden

La experiencia debe comunicar rapidez y confianza.

Mensaje:

> Menos captura repetitiva. Mas claridad para operar.

## Tono de voz

El tono debe ser:

- serio
- claro
- sobrio
- directo
- confiable
- moderno
- orientado a operacion real

Debe evitar:

- exageraciones vacias
- lenguaje corporativo pesado
- promesas absolutas
- chistes o tono gamer
- palabras como "revolucionario" si no hay una afirmacion concreta detras

Ejemplos de tono correcto:

- "Controla stock por sucursal, almacen y ubicacion."
- "Conecta ventas fisicas y online con el mismo inventario operativo."
- "Convierte ventas en salidas operativas sin perder contexto."
- "Crea tu empresa en minutos y completa la configuracion dentro del sistema."

Ejemplos a evitar:

- "La solucion definitiva para todas las empresas."
- "Automatiza todo tu negocio con un click."
- "El sistema mas poderoso del mercado."

## Tono visual

Referencia visual:

- Linear
- Stripe
- Vercel

Pero con identidad Nexuit:

- azul Nexuit como color primario
- blanco, gris frio y azul muy leve como base
- profundidad sutil
- cards limpias
- sombras suaves
- tipografia sobria
- animaciones discretas
- fondos con identidad operativa sutil, no decoracion excesiva

Debe sentirse:

- premium
- rapido
- confiable
- silencioso
- profesional

Evitar:

- UI saturada
- gradientes agresivos
- iconografia de videojuego
- mockups falsos imposibles
- dashboards genericos sin relacion con inventario real

## Estructura sugerida de landing

### 1. Hero

Objetivo: explicar rapido que hace Nexuit y llevar a registro.

Elementos:

- headline fuerte
- subheadline clara
- CTA principal: "Crear empresa"
- CTA secundario: "Iniciar sesion"
- visual principal: operacion conectada inventario -> POS / tienda online -> despacho

Copy sugerido:

Headline:

> Ordena inventario, ventas fisicas, tienda online y despachos en una sola suite SaaS.

Subheadline:

> Nexuit conecta productos, sucursales, almacenes, POS, ventas online y salidas para que tu negocio opere con claridad desde el primer dia.

CTA principal:

> Crear empresa

CTA secundario:

> Iniciar sesion

### 2. Problema

Objetivo: que el usuario se reconozca.

Ideas:

- stock disperso entre sucursales
- ventas fisicas y online que no se reflejan claramente en inventario o salidas
- productos con variantes dificiles de controlar
- operaciones en hojas de calculo
- almacenes sin ubicaciones claras

Copy:

> Cuando el inventario crece, tambien crecen las dudas: donde esta, cuanto queda, que se vendio en tienda, que se vendio online, que falta empacar y que ya salio.

### 3. Sistema operativo del negocio

Objetivo: explicar la arquitectura de valor sin sonar tecnico.

Bloques:

- Catalogo
- Inventario
- Ventas/POS
- Tienda online
- Despachos
- Compras
- Fabricacion

Copy:

> Cada modulo comparte el mismo contexto: productos, sucursales, almacenes, canales de venta y movimientos.

### 4. Inventario como punto de partida

Objetivo: reforzar que el inventario es la base del sistema.

Copy:

> Crea productos, variantes y SKUs. Ubica stock por sucursal, almacen y ubicacion interna. Desde ahi nacen POS, tienda online, salidas, compras y fabricacion.

### 5. Venta fisica y online sobre el mismo inventario

Objetivo: dejar claro que Nexuit no se limita a ventas de mostrador.

Copy:

> Vende en mostrador, prepara pedidos online y conserva una sola verdad de stock. La tienda en linea debe nacer del mismo catalogo operativo, no de una lista duplicada.

Nota de promesa:

La landing puede presentar la tienda online propia como direccion central del producto y modulo final de comercio.
Si la funcionalidad aun no esta completamente productiva en el SaaS, usar lenguaje de preparacion o evolucion, no de publicacion automatica cerrada.

### 6. Operacion mobile-first

Objetivo: mostrar que no es solo escritorio.

Copy:

> Supervisa desde escritorio. Opera rapido desde el navegador movil. Nexuit separa las experiencias para que cada pantalla tenga sentido en su contexto.

No prometer offline completo aun.
Si se menciona app nativa, usar:

> App nativa en evolucion para escaneo y operacion de bodega.

### 7. Planes y capacidades

Objetivo: explicar modularidad.

Copy:

> Nexuit se activa por capacidades. Tu negocio empieza con lo que necesita y puede crecer hacia compras, POS, tienda online, despachos o fabricacion cuando sea momento.

### 8. CTA final

Copy:

> Crea tu empresa y empieza con una estructura operativa clara.

CTA:

> Crear empresa

## CTAs y rutas

El repo del SaaS expone estas rutas publicas:

- Registro de empresa: `/register`
- Login de tenant: `/login`
- Login SaaS Owner: `/platform/login`

La landing debe enviar clientes a:

- CTA principal: `https://app.nexuit.com/register` o dominio equivalente del SaaS
- CTA secundario: `https://app.nexuit.com/login`

No exponer `/platform/login` en la landing comercial normal.
Ese acceso es para el equipo Nexuit/SaaS Owner y debe mantenerse separado.

## Promesas permitidas

La landing puede afirmar:

- Nexuit organiza inventario por sucursal, almacen y ubicacion.
- Nexuit permite gestionar productos, variantes y SKUs.
- Nexuit conecta ventas fisicas y online con inventario, despachos y empaque.
- Nexuit esta pensado para tienda online propia basada en el mismo catalogo e inventario del sistema.
- Nexuit prepara productos vendibles con clasificacion comercial, atributos y stock como base para comercio digital.
- Nexuit soporta operacion desktop y web mobile-first.
- Nexuit tiene planes/capabilities modulares.
- Nexuit ayuda a iniciar con onboarding guiado.

## Promesas que deben evitarse

No prometer aun:

- facturacion fiscal local automatica
- cumplimiento SAT/CFDI/VAT por pais
- integraciones marketplace completas si no estan cerradas productivamente
- tienda online completamente publicada si el modulo aun no esta activo productivamente
- offline mobile completo
- inteligencia artificial automatizando todo el negocio
- contabilidad completa
- reemplazo absoluto de cualquier ERP

Si se menciona tienda propia o marketplace:

Usar lenguaje de direccion si el modulo aun no esta productivamente completo:

> Pensado para que tu tienda online nazca del mismo catalogo e inventario operativo.

> Preparado para evolucionar hacia tienda propia y canales marketplace sin duplicar inventario.

No decir:

> Publica automaticamente en todos los marketplaces.

## Modulos a presentar

Prioridad alta:

- Catalogo
- Inventario
- Ventas
- POS
- Tienda online
- Despachos

Prioridad media:

- Compras
- Fabricacion
- Usuarios y roles
- Planes/capabilities

Prioridad baja o secundaria:

- SaaS Owner
- auditoria interna
- configuraciones avanzadas
- downgrade de planes
- detalles tecnicos de permisos

## Lenguaje recomendado por modulo

Catalogo:

> Productos, variantes, SKUs y clasificacion comercial listos para operar.

Inventario:

> Stock visible por sucursal, almacen y ubicacion interna.

Ventas:

> Ventas fisicas y online conectadas al inventario y listas para convertirse en salida.

POS:

> Punto de venta para operacion diaria sin perder contexto de stock.

Tienda online:

> Comercio digital pensado para usar el mismo catalogo, variantes y stock de tu operacion.

Despachos:

> Picking, packing y envio conectados a cada venta.

Compras:

> Abastecimiento y proveedores conectados al inventario.

Fabricacion:

> Produccion para negocios que ensamblan, transforman o fabrican.

## Imagen de producto

Los mockups deben parecer operacion real.

Mostrar:

- cards de catalogo con variantes
- resumen de stock por sucursal/almacen
- flujo multicanal: POS y tienda online usando el mismo inventario
- cola de ventas/despachos
- mobile-first con escaneo o accion operativa
- dashboard sobrio con prioridades

Evitar:

- tablas gigantes sin jerarquia
- graficas genericas sin relacion operativa
- fondos abstractos que parezcan fintech pura
- pantallas demasiado llenas
- datos falsos exagerados

## Regla de consistencia con el SaaS

La landing no debe inventar un producto distinto al SaaS.

Debe conservar:

- producto serio
- operacion real
- modularidad
- inventario como base
- enfoque multi-sucursal/multi-almacen
- ventas fisicas y online conectadas al mismo inventario
- tienda online como direccion estrategica del producto
- experiencia desktop + mobile-first
- onboarding rapido
- claridad sobre planes y capacidades

Si una seccion no ayuda a que el cliente entienda por que Nexuit ordena su operacion, eliminarla.

## Prompt breve para usar en otro repo

Usa este resumen cuando se trabaje con un asistente en el repositorio de landing:

```text
Estamos construyendo la landing comercial de Nexuit.
Nexuit es una suite SaaS multi-tenant para negocios con inventario fisico y venta multicanal: catalogo, variantes, sucursales, almacenes, ubicaciones, ventas fisicas, POS, ventas online, despachos, compras y fabricacion.
No es un ERP generico ni un software contable. El tono debe ser SaaS premium, serio y sobrio tipo Linear/Stripe/Vercel, con azul Nexuit, blanco, gris frio y profundidad sutil.
La promesa principal es: controlar la operacion desde inventario hasta venta fisica u online sin perder visibilidad entre sucursales, almacenes y equipos.
CTA principal: Crear empresa -> /register.
CTA secundario: Iniciar sesion -> /login.
No exponer /platform/login en la landing.
La tienda online propia es direccion estrategica del producto: debe comunicarse como comercio digital basado en el mismo catalogo e inventario operativo. No prometer publicacion automatica completa, facturacion fiscal, marketplace completo, offline nativo o automatizacion total si no esta validado.
La landing debe explicar: inventario como base, ventas fisicas y online conectadas, operacion conectada, crecimiento modular por capacidades y experiencia desktop + web mobile-first.
```
