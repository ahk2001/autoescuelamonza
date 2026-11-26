# Autoescuela Monza Castellón

Sitio web oficial de **Autoescuela Monza Castellón** (TORRES Y RUIZ AUTOESCUELA S.L.), diseñado con enfoque editorial, alto rendimiento y formulario popup de triaje inteligente para atención por WhatsApp.

## Estructura del proyecto

```text
.
├── assets/                  # Logotipo, fotografías de flota y alumnos aprobados
├── docs/                    # Dossiê estratégico del proyecto
├── index.html               # Página principal autocontenida (HTML5 + CSS + Vanilla JS)
├── vercel.json              # Cabeceras de seguridad HTTP y caché de assets
├── .gitignore               # Exclusiones de sistema y archivos temporales
└── README.md
```

## Características principales

- **Triaje inteligente en popup (5 pasos):** Filtra permiso/curso, situación actual, preferencia horaria y centro (`Calle Artana, 2` o `Plaza de la Paz`) antes de abrir WhatsApp (`+34 628 26 90 05`).
- **Diseño responsive:** Carruseles horizontales en móvil sin cortes laterales, animaciones suaves al hacer scroll y menú minimalista a pantalla completa.
- **Seguridad:** Cabeceras HTTP (`X-Content-Type-Options`, `X-Frame-Options`, `Referrer-Policy`, `Permissions-Policy`) configuradas en `vercel.json`.
