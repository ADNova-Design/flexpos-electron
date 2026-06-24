# FlexPOS v3.0 - Punto de Venta Local y Seguro

FlexPOS v3.0 es la solución definitiva de punto de venta (POS) de escritorio diseñada para operar de manera completamente autónoma y local, garantizando la continuidad de su negocio sin depender de una conexión a internet ni de suscripciones mensuales obligatorias. Desarrollado con tecnología moderna sobre Electron, ofrece una experiencia ágil, robusta y sumamente segura para la gestión diaria de comercios de cualquier escala.

> [!IMPORTANT]
> **Nota de Distribución:** Este repositorio no almacena el código fuente de la aplicación FlexPOS. Está destinado exclusivamente para hospedar los instaladores de distribución oficial, las notas de lanzamiento y los metadatos necesarios para el motor de actualizaciones automáticas de la aplicación de escritorio.

---

## 🏆 Ventajas Clave del Cliente

*   **100% Fuera de Línea (Offline):** El sistema funciona en su totalidad de manera local. Su negocio nunca se detendrá debido a fallas en el proveedor de internet.
*   **Seguridad y Privacidad de Datos:** Toda la información comercial, catálogos y registros de ventas se almacenan de manera local en su propio hardware. Usted es el único dueño y custodio de sus datos comerciales.
*   **Integridad de Datos Avanzada:** Implementación de transacciones a nivel de base de datos para asegurar que cada venta, movimiento de inventario y corte de caja se registren de forma consistente y sin pérdidas.
*   **Respaldos Locales Automáticos:** Mecanismo integrado de copias de seguridad automáticas programadas que se almacenan de manera segura en unidades locales o externas definidas por el administrador.
*   **Seguridad por Licencia de Hardware (HWID):** Protección avanzada mediante el enlazado de la licencia al identificador único de hardware de la máquina instalada, evitando duplicaciones no autorizadas y accesos indebidos.
*   **Cero Mensualidades (Licencia de Pago Único):** Olvídese de rentas mensuales que merman el flujo de efectivo de su negocio. FlexPOS se adquiere mediante un único pago por licencia de equipo.

---

## ⚙️ Módulos Funcionales Centrales

1.  **Punto de Venta (POS) con Pago Dividido:**
    *   Soporte para cobros combinados en efectivo, tarjeta y transferencias en una misma transacción.
    *   Búsqueda ultra rápida de productos por código de barras, clave o descripción.
    *   Gestión de clientes frecuentes y descuentos directos sobre la venta.
2.  **Inventario y Márgenes de Utilidad:**
    *   Control preciso de existencias con alertas automáticas de stock mínimo.
    *   Configuración dinámica de márgenes de utilidad deseados por producto o categoría.
    *   Historial de entradas y salidas de mercancía detallado.
3.  **Auditoría y Bitácora de Movimientos (Audit Trails):**
    *   Registro estricto y no modificable de todas las acciones críticas en el sistema (cancelaciones, descuentos, aperturas de cajón, cambios de precio).
    *   Facilidad de rastreo para administradores ante cualquier discrepancia.
4.  **Control de Turnos Activos (Cortes de Caja):**
    *   Registro de saldo inicial, entradas y salidas de efectivo justificadas durante el turno.
    *   Arqueos rápidos y reportes de cierre de turno detallados por tipo de pago y cajero.
5.  **Configuración Personalizada e Impresión de Tickets:**
    *   Personalización completa de la información del ticket de compra (logotipo, datos fiscales, leyendas de garantía, redes sociales).
    *   Compatibilidad nativa con impresoras térmicas de 58mm y 80mm vía comandos ESC/POS directos.

---

## 🔄 Sistema de Actualizaciones Automáticas

La aplicación de escritorio de FlexPOS incluye un motor de escaneo de actualizaciones configurado para auditar este repositorio público.
*   **Mecanismo:** La aplicación realiza una petición segura y ligera de lectura a este repositorio para verificar la existencia de un archivo de metadatos de versión (`latest.yml` / `package.json` de distribución).
*   **Descarga Segura:** Si detecta una nueva versión estable disponible, ofrece al usuario la descarga automática y la aplicación del parche de actualización sin interrumpir la operación local de la base de datos.

---

## ⏳ Prueba Gratuita de 15 Días

Le invitamos a evaluar el poder y la estabilidad de FlexPOS v3.0 sin compromisos:
*   Descargue el instalador y comience una prueba con acceso a **todas las funcionalidades** durante 15 días consecutivos.
*   Al finalizar el periodo de prueba, podrá activar la licencia definitiva mediante un código único de hardware (HWID) sin perder la información registrada durante su evaluación.

---

*Desarrollado y distribuido por **ADNova-Design**.*
