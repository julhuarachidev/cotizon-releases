# Cotizon — descargas

Cotizon muestra el **dólar en Bolivia en tiempo real**: el oficial del BCB y el paralelo
(Binance P2P), y calcula si conviene comprar dólares con tarjeta y venderlos en P2P.

Este repositorio solo publica los instaladores (APK) para Android. El código es privado.

## Descargar

➡️ **[Versiones](https://github.com/julhuarachidev/cotizon-releases/releases)**: abre la primera de la lista y descarga el archivo `Cotizon-x.y.z.apk`.

## Instalar

1. Abre el archivo `.apk` en tu teléfono (Android 8 o superior).
2. Si Android pide permiso para *instalar apps desconocidas*, acéptalo para tu navegador o WhatsApp.
3. Si aparece **Play Protect** ("app no reconocida"), toca **Instalar de todas formas**:
   es normal en apps que todavía no están en Play Store.

Para actualizar, instala la versión nueva encima de la anterior; no hace falta desinstalar.

## Verificar (opcional)

Todas las versiones están firmadas con el mismo certificado:

```
SHA-256: A9:26:96:0F:00:D1:CC:EA:8A:B4:3F:7B:D9:D6:7A:DC:89:9D:9C:F6:F9:CD:C5:EC:E5:71:90:93:48:D6:F5:19
```

`apksigner verify --print-certs Cotizon-x.y.z.apk` debe mostrar ese valor.

## Aviso

Las cotizaciones y cálculos son informativos, no son asesoría financiera.
