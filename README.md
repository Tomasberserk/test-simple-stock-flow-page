# Simple Stock Flow — Page (Sitio Público Estático)

Sitio web estático de presentación del producto **Simple Stock Flow**, diseñado de acuerdo con la especificación de la prueba técnica SDD (SENA ADSO 3413974).

---

## 📌 Principio de Diseño

- **Totalmente estático**: HTML5 semántico, CSS responsivo moderno y diseño visual limpio.
- **Sin conexión a la API**: Conforme al Artículo del spec, este repositorio **no se conecta a la API** ni a la base de datos.
- **Presentación integral**:
  - Explicación de los 4 anillos concéntricos de la Arquitectura Onion.
  - Reglas de negocio e invariantes (concurrencia optimista, cálculo decimal exacto con `BigDecimal`, congelado de precios históricos).
  - Resumen del stack tecnológico (Laravel + React + TypeScript + MySQL 8.4 LTS).
  - Mapa del ecosistema de 6 repositorios hermanos.

---

## 🚀 Visualización Local

Al ser un sitio web estático puro, puede abrirse directamente en cualquier navegador:

```bash
# Con cualquier servidor HTTP local simple
npx serve .
# o con Python
python -m http.server 3000
```
