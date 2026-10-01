# Yatta

**Cobrá y facturá.** Facturación electrónica para el mostrador (ARCA / ex AFIP).

Este repositorio publica **solo binarios firmados** para Windows y el material comercial del producto.  
El código fuente no se distribuye aquí.

---

## Video presentacional

Conocé Yatta en menos de un minuto:

**[Ver / descargar yatta-promo.mp4](https://github.com/GabrieLZ19/Facturador-releases/releases/download/v0.1.4/yatta-promo.mp4)**

> Spot de producto: usabilidad, asistente de inicio, mostrador y emisión con CAE.

---

## Descargar

Última versión estable:

**[Releases → Latest](https://github.com/GabrieLZ19/Facturador-releases/releases/latest)**

| Archivo | Para qué |
| --- | --- |
| `Yatta_*_x64-setup.exe` | Instalador recomendado (NSIS) |
| `*.sig` | Firma de verificación (auto-update) |
| `latest.json` | Manifiesto que consulta la app al buscar actualizaciones |
| `yatta-promo.mp4` | Video presentacional del producto |

> Preferí el instalador **setup.exe**. No hace falta descargar el `.sig` a mano si instalás desde la app o desde ese `.exe`.

---

## Requisitos

- Windows 10 / 11 (64 bits)
- [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) (en la mayoría de PCs ya viene instalado)
- Certificado ARCA (ex AFIP) del comercio para emitir en producción

---

## Instalación

1. Descargá el `.exe` de la [última release](https://github.com/GabrieLZ19/Facturador-releases/releases/latest).
2. Ejecutá el instalador y seguí el asistente.
3. Al abrir Yatta, completá el onboarding (local, datos fiscales, certificados).
4. Activá tu licencia desde **Configuración → Licencia** (archivo `.lic` que te enviamos).

Los datos quedan en tu PC (`%APPDATA%\sistema-facturacion`). No se suben a la nube.

---

## Actualizaciones

Yatta busca actualizaciones al iniciar y periódicamente. Cuando hay una versión nueva:

- Verás un aviso en la app, o
- Podés ir a **Configuración → Actualizaciones → Buscar actualizaciones**

Las actualizaciones se descargan desde este mismo repositorio y se verifican con firma criptográfica. Sin internet, la app sigue funcionando con normalidad.

---

## Qué incluye el producto

- Emisión de **Factura C** y **Nota de crédito C** (ARCA / WSFEv1)
- Mostrador, clientes, productos favoritos, historial y caja
- Ticket térmico 58/80 mm, PDF y QR (RG 4892)
- Multilocal (perfiles aislados), backup y diagnóstico
- Licencia por máquina (Hardware ID)

---

## Seguridad

- Los instaladores se firman con la clave de updates de Yatta.
- No publiques ni compartas tu `private.key` de ARCA ni archivos `.lic` de otros comercios.
- Este repo **no** contiene código fuente, certificados ni claves privadas.

---

## Soporte

Si tenés un problema al instalar o actualizar:

1. En la app: **Configuración → Soporte → Exportar soporte**
2. Enviá ese paquete a quien te vendió / da soporte de Yatta

Indicá siempre la **versión** (Configuración → Soporte) y si el error es al instalar, al activar licencia o al emitir.

---

## Licencia de uso

Yatta se distribuye bajo licencia comercial por máquina.  
La descarga del instalador no implica derechos de uso sin una licencia válida.

---

<p align="center">
  <a href="https://github.com/GabrieLZ19/Facturador-releases/releases/download/v0.1.4/yatta-promo.mp4"><strong>Ver video</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/GabrieLZ19/Facturador-releases/releases/latest"><strong>Descargar Yatta</strong></a>
</p>
