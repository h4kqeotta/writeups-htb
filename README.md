# Writeups — Hack The Box 🟥

Documentación de máquinas resueltas en [Hack The Box](https://hackthebox.com).
Cada writeup detalla el proceso completo: reconocimiento, enumeración, explotación y escalada de privilegios.

> ⚠️ Solo se publican writeups de máquinas **retiradas (retired)**.
> No se comparte información de máquinas activas.

---

## 📋 Índice de máquinas

| Máquina | OS | Dificultad | Técnicas principales | Writeup |
|---------|-----|-----------|----------------------|---------|
| *(próximamente)* | — | — | — | — |

---

## 🔧 Metodología

Cada máquina sigue esta estructura:

1. **Reconocimiento** — Nmap, enumeración de puertos y servicios
2. **Enumeración** — Investigación profunda de cada servicio
3. **Explotación** — Acceso inicial al sistema
4. **Post-explotación** — Escalada de privilegios y flags

---

## 📁 Estructura del repositorio

```
writeups-htb/
├── README.md
└── [nombre-maquina]/
    ├── [nombre-maquina].md   ← writeup completo
    └── img/                  ← capturas de pantalla
```

---

## 🛠️ Herramientas usadas frecuentemente

- `nmap` — Escaneo de puertos
- `gobuster` / `ffuf` — Fuerza bruta de directorios
- `metasploit` — Framework de explotación
- `burp suite` — Intercepción de tráfico web
- `linpeas` / `winpeas` — Enumeración post-explotación

---
