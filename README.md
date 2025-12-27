<h1 align='center'>SKULL NETWORK ITALIA APP ANDORID</a></h1>
<p align='center'><a href='https://discord.gg/Jrm2Z26ad3'>Discord Skull Network Italia</a>

# Skull Network Italia App Android

# Skull Network Italia - App Android

Applicazione ufficiale per la community Skull Network Italia.

## Caratteristiche
- Icona personalizzata della community
- Sistema di auto-update automatico
- Accesso rapido a sito, forum e news
- Notifiche per nuovi aggiornamenti

## Requisiti
- Visual Studio 2022+
- Xamarin.Android
- Android SDK 21+

## Installazione
1. Clona il repository
2. Apri la soluzione in Visual Studio
3. Configura le URL degli aggiornamenti in `MainActivity.cs`
4. Compila per Android

## Configurazione Auto-Update
Modificare le seguenti costanti in `MainActivity.cs`:
- `APK_DOWNLOAD_URL`: URL dove si trova l'APK aggiornato
- `VERSION_CHECK_URL`: URL del file di versione (solo testo)
- `APP_VERSION`: Versione corrente dell'app

## Struttura del Progetto
- `MainActivity.cs`: Attività principale
- `UpdateService.cs`: Servizio per controllo aggiornamenti
- `Resources/`: Immagini e layout

## Contribuire
1. Fork del progetto
2. Crea un branch per la tua feature
3. Commit delle modifiche
4. Push al branch
5. Crea una Pull Request