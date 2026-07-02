# Project Context — AuditWeb Landing

## Repositorios importantes

### Landing pública real
Repo local:
~/auditweb-landing

Repo GitHub:
git@github.com:DaniAngel79/auditweb-landing.git

Rama:
main

Archivo público:
index.html

URL pública:
https://daniangel79.github.io/auditweb-landing/

GitHub Pages:
DaniAngel79/auditweb-landing
Branch: main
Folder: /root

IMPORTANTE:
Cualquier cambio visual o comercial de la landing pública debe hacerse en:
~/auditweb-landing/index.html

NO publicar cambios de landing únicamente desde:
~/Proyect_jobs_independiente/landing/index.html

Ese archivo puede usarse como copia fuente o referencia, pero NO es el sitio público activo.

---

### Toolkit / aplicación de auditoría
Repo local:
~/Proyect_jobs_independiente

Archivo de landing dentro del toolkit:
~/Proyect_jobs_independiente/landing/index.html

Repo donde se subió una copia por error:
DaniAngel79/-audit-web-toolkit

IMPORTANTE:
El repo -audit-web-toolkit contiene la herramienta y una copia de la landing, pero NO es la landing pública principal.

---

## Regla para futuras modificaciones

Antes de modificar o publicar la landing:

1. Confirmar en qué repo estamos:
   pwd
   git remote -v
   git branch --show-current

2. Si el objetivo es actualizar la web pública, usar:
   ~/auditweb-landing/index.html

3. No tocar motor técnico:
   - no tocar auditoria_web/
   - no tocar archivos .py
   - no tocar .env
   - no tocar claves
   - no tocar base de datos
   - no tocar scripts de escaneo

4. Para publicar landing pública:
   cd ~/auditweb-landing
   git status --short
   git add index.html
   git commit -m "Update security landing"
   git push origin main

5. Después verificar:
   https://daniangel79.github.io/auditweb-landing/

---

## Copy aprobado

La landing debe posicionarse como:
"Seguridad web para comercios y profesionales"

No usar:
- pentest
- seguridad garantizada
- 0 vulnerabilidades
- hacker-proof
- blindaje total
- monitoreo 24/7
- respuesta en 2 horas
- ISO/PCI como certificación
- validez legal
- SQLi / Open Redirect en demo si la herramienta no lo valida realmente

WhatsApp:
https://wa.me/5493547322127

Email:
mailto:infra.socrecon@proton.me?subject=Quiero%20revisar%20la%20seguridad%20de%20mi%20sitio

