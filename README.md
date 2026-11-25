# Kures Poker · Caja

App de cajero para noches de poker: entradas en cash o a cuenta, recompras, retiros, cierre de la noche, historial, estadísticas por jugador, ranking y jackpot.

## Descargar

**[Descargar la última versión (KuresPoker.apk)](https://github.com/edufdc39-ship-it/kures-poker/releases/latest/download/KuresPoker.apk)**

Al instalar, Android puede pedir permiso para "instalar apps desconocidas": es normal porque no viene de la Play Store.
Para actualizar, se instala el APK nuevo encima: los datos se mantienen.

## Datos

Todo se guarda solo en el celular. Desde **Historial → Respaldo de datos** se puede exportar una copia (para WhatsApp o Drive) e importarla en otro celular.

## Cómo se compila

Cada cambio que se sube a `main` compila el APK automáticamente (GitHub Actions) y lo publica en *Releases*.
- `www/index.html`: la app.
- `android/`: proyecto Android (Capacitor).
- `android/keystore/kures-release.jks`: clave de firma. Su contraseña está en el secreto `KEYSTORE_PASSWORD` del repositorio. **No borrar**: sin esta clave las actualizaciones no se pueden instalar encima.
