
es donde se aloja el frontend de legalcontratos.com
# LegalContratos

Sistema de mail-merge para contratos legales argentinos.

**Frontend:** GitHub Pages → `app.legalcontratos.com`  
**Backend:** Google Apps Script  
**DB:** Google Sheets  
**Templates:** Google Docs  

## Stack
- HTML/CSS/JS vanilla (SPA)
- Google Apps Script (backend)
- Google Sheets (base de datos)
- Google Docs (motor de templates)
- Cloudflare DNS
- Auth 2FA por email

## Deploy
1. Push `index.html` + `CNAME` a este repo
2. Activar GitHub Pages (branch `main`, root `/`)
3. Configurar CNAME en Cloudflare → `vresti.github.io`

© 2026 LegalContratos · info@tasks-on.com