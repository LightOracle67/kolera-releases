# Kolera GDN — releases

Repositorio **solo de binarios** de Kolera GDN. No contiene el código fuente.

## Última versión: 1.0.106

### macOS

- `Kolera GDN-1.0.106-arm64.dmg` / `-arm64-mac.zip`
- Firma ad-hoc, sin notarización. Gatekeeper puede avisar: clic derecho → Abrir.

### Windows

- `Kolera GDN Setup 1.0.106-x64.exe` (Intel/AMD)
- `Kolera GDN Setup 1.0.106-arm64.exe` (ARM)
- `Kolera GDN-1.0.106-win-x64.zip` / `-win-arm64.zip` (portable)
- Sin certificado de CA. SmartScreen puede avisar: **Más información → Ejecutar de todas formas**.
- ARM64 no incluye `cloudflared`.

### Linux

- `Kolera GDN-1.0.106-linux-x64.zip`
- `Kolera GDN-1.0.106-linux-arm64.zip`
- Portable; `chmod +x "Kolera GDN"`.
- **Actualización manual:** la release gratuita no publica AppImage; descarga el ZIP nuevo y sustituye la carpeta.

## Integridad

Verifica `SHA256SUMS-1.0.106.txt` antes de instalar:

```bash
shasum -a 256 -c SHA256SUMS-1.0.106.txt
```

## Notas

- Sin nube, sin backup externo gestionado y sin conexión AEAT.
- Las actualizaciones se comprueban contra este repositorio público.
- No se publican claves privadas, cuentas de servicio ni código fuente.
- Soporte best-effort: `soporte@kolera.app`.
