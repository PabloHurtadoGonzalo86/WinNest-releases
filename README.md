<p align="center">
  <img src="icon.svg" width="88" alt="WinNest logo" />
</p>

<h1 align="center">WinNest</h1>

<p align="center">
  <b>Virtual machines for Windows, built for AI agents.</b><br />
  <a href="https://winnest.apptolast.com">winnest.apptolast.com</a> ·
  <a href="#español">Español</a>
</p>

This repository hosts the **WinNest installers** and its **public issue tracker**. WinNest's
source code is not public.

- **Download the latest version:**
  [WinNest-setup-x64.exe](https://github.com/PabloHurtadoGonzalo86/WinNest-releases/releases/latest/download/WinNest-setup-x64.exe)
  (Windows 10 or 11, 64-bit)
- **Release notes and checksums:** [Releases](https://github.com/PabloHurtadoGonzalo86/WinNest-releases/releases)
- **Report a bug or ask for a feature:** [Issues](https://github.com/PabloHurtadoGonzalo86/WinNest-releases/issues/new/choose)
- **Licenses, purchases and refunds:** [pricing](https://winnest.apptolast.com/pricing/) or
  [pablohurtadohg@gmail.com](mailto:pablohurtadohg@gmail.com)
- **Security vulnerabilities:** please report them privately by email, not in an issue.

WinNest is free to download and, for now, has no trial limits. A license is a one-time purchase
for one PC per seat, with a year of updates:
[license agreement](https://winnest.apptolast.com/terms/).

### Verify a download

Every release includes `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\WinNest-setup-x64.exe -Algorithm SHA256
```

The installer is not code-signed yet, so Microsoft Defender SmartScreen may say that it protected
your PC: choose **More info** and then **Run anyway**.

---

## Español

Este repositorio aloja los **instaladores de WinNest** y su **gestor de incidencias público**. El
código fuente de WinNest no es público.

- **Descarga la última versión:**
  [WinNest-setup-x64.exe](https://github.com/PabloHurtadoGonzalo86/WinNest-releases/releases/latest/download/WinNest-setup-x64.exe)
  (Windows 10 u 11 de 64 bits)
- **Notas de versión y sumas de verificación:** [Releases](https://github.com/PabloHurtadoGonzalo86/WinNest-releases/releases)
- **Informa de un error o pide una función:** [Issues](https://github.com/PabloHurtadoGonzalo86/WinNest-releases/issues/new/choose)
- **Licencias, compras y reembolsos:** [precios](https://winnest.apptolast.com/es/pricing/) o
  [pablohurtadohg@gmail.com](mailto:pablohurtadohg@gmail.com)
- **Vulnerabilidades de seguridad:** avísanos en privado por email, no en una incidencia.

El instalador aún no está firmado digitalmente, así que SmartScreen puede decir que ha protegido
tu PC: pulsa **Más información** y después **Ejecutar de todas formas**. Comprueba el archivo con
`SHA256SUMS.txt` (`Get-FileHash .\WinNest-setup-x64.exe -Algorithm SHA256` en PowerShell).

---

Copyright © 2026 Pablo Hurtado González. All rights reserved. Windows is a trademark of the
Microsoft group of companies.
