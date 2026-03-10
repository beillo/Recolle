# ♻️ Recolle

**Plataforma cidadá para reportar problemas de residuos e limpeza urbana en A Coruña.**

> MVP en construción — Día 1 de 14

---

## O que é

Recolle permite a calquera cidadán marcar nun mapa os problemas de residuos que atopa na rúa: contedores cheos, vertidos ilegais, puntos negros, problemas de reciclaxe ou limpeza viaria.

O obxectivo é construír un mapa colectivo de evidencia que axude á cidadanía e ao Concello a priorizar a xestión de residuos en A Coruña, aliñado co **Plan de Xestión de Residuos Municipais 2025-2030**.

---

## Estado actual

- [x] Mapa interactivo centrado en A Coruña (Leaflet.js)
- [x] Clic no mapa → marcador + xeolocalización inversa (Nominatim)
- [x] Formulario: categoría, descrición, foto
- [x] Lista de reportes na barra lateral
- [x] Datos en memoria (sen backend aínda)

## Próximos pasos

- [ ] Firebase Firestore (persistencia real)
- [ ] Subida de fotos (Firebase Storage)
- [ ] Filtros por categoría no mapa
- [ ] Xerar carta formal para o Concello (Claude API)
- [ ] Deploy en Vercel

---

## Stack

| Capa | Tecnoloxía |
|------|-----------|
| Frontend | HTML + CSS + JS vanilla |
| Mapa | Leaflet.js + OpenStreetMap |
| Geocoding | Nominatim (open source) |
| Backend (fase 2) | Firebase Firestore |
| Deploy | Vercel |

---

## Executar localmente

```bash
# Non necesita servidor — abre directamente no navegador
open index.html

# Ou usa Live Server en VSCode (recomendado)
```

---

## Contexto

Proxecto de portafolio desenvolvido en A Coruña.
Referencia técnica: [Karen Bot by @levelsio](https://gist.github.com/levelsio/b4467fd2fb63bc5373fd3e8559d5ad62)
Referencia civic tech: [FixMyStreet](https://fixmystreet.com)
