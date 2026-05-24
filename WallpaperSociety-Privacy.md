# Datenschutzerklärung für Wallpaper Society

**Stand:** 24. Mai 2026

## 1. Verantwortlicher

Verantwortlich für die Datenverarbeitung im Sinne der Datenschutz-Grundverordnung (DSGVO) ist der Anbieter der App.

**Kontakt:** qlappz@gmail.com

## 2. Allgemeines zur Datenverarbeitung

Wallpaper Society ist eine iOS-App, mit der Sie hochauflösende Wallpaper durchsuchen, favorisieren und auf Ihr Gerät herunterladen können. Die App bezieht ihre Inhalte über eine Server-Schnittstelle (API) und nutzt zur Finanzierung Werbeanzeigen sowie optional eine "Supporter"-Funktion über In-App-Kauf.

Im Folgenden wird beschrieben, welche Daten in welchem Umfang verarbeitet werden.

## 3. Berechtigungen und verarbeitete Daten

### 3.1 Fotomediathek

Die App benötigt Zugriff auf die Fotomediathek, um heruntergeladene Wallpaper in Ihrem Album "Wallpaper Society" zu speichern. Es findet kein Lesen Ihrer eigenen Fotos statt — der Zugriff dient ausschließlich dem Schreiben gespeicherter Wallpaper.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung – Bereitstellung der Hauptfunktion).

### 3.2 Lokale Speicherung

Die folgenden Daten werden ausschließlich lokal auf Ihrem Gerät gespeichert:

- **Favoriten:** IDs der von Ihnen mit einem Herz markierten Wallpaper (in den UserDefaults)
- **Bildcache:** Heruntergeladene Vorschauen und Cover-Bilder (im URL-Cache und im Verzeichnis `Library/Caches/`)
- **App-Einstellungen:** z. B. der Status des Supporter-Kaufs

Diese Daten verlassen Ihr Gerät nicht und werden nicht an den Anbieter oder Dritte übertragen.

### 3.3 App Tracking Transparency (IDFA)

Beim ersten Werbe-Request fragt Apple Sie über das Apple-Dialogfeld, ob Sie das Tracking zulassen möchten (`NSUserTrackingUsageDescription`). Wenn Sie zustimmen, kann der Werbe-Identifier (IDFA) für personalisierte Werbung genutzt werden. Wenn Sie ablehnen, wird ausschließlich nicht-personalisierte Werbung ausgeliefert.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO (Einwilligung).

## 4. Server-Kommunikation

Die App kommuniziert mit einem über Cloudflare betriebenen Backend, um Kategorien, Wallpaper und Tag-Listen abzurufen sowie anonymisierte Statistiken zu Downloads und Reaktionen (Likes) zu erfassen.

Dabei werden technisch unvermeidliche Daten verarbeitet, darunter Ihre IP-Adresse (zur Auslieferung der HTTPS-Antwort) sowie der HTTP-User-Agent. Diese Daten werden nicht zur Identifikation einzelner Nutzer ausgewertet.

**Dienstleister:** Cloudflare, Inc., 101 Townsend St, San Francisco, CA 94107, USA. Datenschutzerklärung: https://www.cloudflare.com/privacypolicy/

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung) und Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse am sicheren Betrieb).

## 5. Werbung (Google AdMob)

Zur Finanzierung der Serverkosten zeigt die App Werbeanzeigen über das **Google Mobile Ads SDK (AdMob)** an. Konkret kommt ein "Rewarded Video"-Format zum Einsatz, das vor dem Download eines Wallpapers abgespielt wird.

Google AdMob kann dabei folgende Daten verarbeiten:

- IP-Adresse
- Werbe-Identifier (IDFA), sofern Sie über App Tracking Transparency zugestimmt haben
- Allgemeine Geräteinformationen (Modell, iOS-Version, Sprache)
- Technische Daten zur Werbe-Auslieferung

**Anbieter:** Google Ireland Limited, Gordon House, Barrow Street, Dublin 4, Irland.
Datenschutzerklärung von Google: https://policies.google.com/privacy

Vor dem ersten Werbe-Request wird im EU/EWR-Raum eine **Consent-Abfrage über Google User Messaging Platform (UMP)** angezeigt. Sie können dort wählen, ob personalisierte Werbung erlaubt sein soll. Die Auswahl kann später nicht direkt aus der App heraus zurückgesetzt werden — bitte wenden Sie sich dazu an uns (Kontakt siehe oben).

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO (Einwilligung) für personalisierte Werbung; Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an Finanzierung der App) für nicht-personalisierte Werbung.

## 6. In-App-Kauf "Supporter"

Wenn Sie die optionale "Supporter"-Version erwerben, wird die Werbung dauerhaft für Sie deaktiviert. Die Kaufabwicklung erfolgt vollständig über **Apple StoreKit**; der Anbieter dieser App erhält von Apple keine personenbezogenen Daten, sondern lediglich anonymisierte Verkaufsstatistiken.

Datenschutzerklärung von Apple: https://www.apple.com/legal/privacy/

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung).

## 7. Cookies und Tracking

Die App selbst setzt keine Cookies. Die in den Werbeanzeigen von Google eingebundenen Inhalte können technisch erforderliche Identifier (z. B. zur Frequenzbegrenzung) verwenden. Details finden Sie in Googles Datenschutzerklärung (siehe oben).

## 8. Speicherdauer

- **Lokale Daten** (Favoriten, Caches) verbleiben auf Ihrem Gerät, bis Sie sie über die App oder das System löschen oder die App deinstallieren.
- **Anonymisierte Server-Logs** werden nach maximal 30 Tagen automatisch gelöscht.
- **Werbe- und Tracking-Daten** unterliegen den Speicherfristen von Google bzw. den ausgewählten Werbenetzwerken.

## 9. Weitergabe an Dritte

Eine Weitergabe Ihrer Daten erfolgt ausschließlich an die in dieser Erklärung genannten Dienstleister (Cloudflare, Google AdMob, Apple) und nur im beschriebenen Umfang.

## 10. Ihre Rechte

Sie haben nach DSGVO folgende Rechte:

- Recht auf Auskunft (Art. 15 DSGVO)
- Recht auf Berichtigung (Art. 16 DSGVO)
- Recht auf Löschung (Art. 17 DSGVO)
- Recht auf Einschränkung der Verarbeitung (Art. 18 DSGVO)
- Recht auf Datenübertragbarkeit (Art. 20 DSGVO)
- Widerspruchsrecht (Art. 21 DSGVO)
- Beschwerderecht bei einer Aufsichtsbehörde (Art. 77 DSGVO)

Für Anfragen wenden Sie sich an: qlappz@gmail.com

## 11. Änderungen dieser Datenschutzerklärung

Diese Datenschutzerklärung kann bei Änderungen der App-Funktionalität oder rechtlichen Vorgaben angepasst werden. Die jeweils aktuelle Fassung ist unter der in App Store Connect hinterlegten URL abrufbar.

---

# Privacy Policy for Wallpaper Society

**Last updated:** May 24, 2026

## 1. Data Controller

The data controller in the sense of the General Data Protection Regulation (GDPR) is the provider of the app.

**Contact:** qlappz@gmail.com

## 2. General Information

Wallpaper Society is an iOS app that lets you browse, favorite, and download high-resolution wallpapers. The app retrieves its content from a server API and is financed through advertising and an optional "Supporter" in-app purchase.

## 3. Permissions and Processed Data

### 3.1 Photo Library

The app requires access to your photo library in order to save downloaded wallpapers to your "Wallpaper Society" album. It does not read your own photos — access is exclusively used to write saved wallpapers.

**Legal basis:** Art. 6(1)(b) GDPR (performance of a contract).

### 3.2 Local Storage

The following data is stored exclusively on your device:

- **Favorites:** IDs of wallpapers you have marked with a heart (in UserDefaults)
- **Image Cache:** Downloaded previews and covers (in URLCache and `Library/Caches/`)
- **App Settings:** e.g. Supporter purchase status

This data never leaves your device.

### 3.3 App Tracking Transparency (IDFA)

On the first ad request, Apple will ask via the Apple-provided dialog whether you allow tracking. If you allow it, your advertising identifier (IDFA) may be used for personalized ads. If you decline, only non-personalized ads will be shown.

**Legal basis:** Art. 6(1)(a) GDPR (consent).

## 4. Server Communication

The app communicates with a backend hosted via Cloudflare to retrieve categories, wallpapers, and tag lists, and to record anonymized statistics on downloads and reactions (likes).

Technically unavoidable data — such as your IP address (for HTTPS delivery) and the HTTP user agent — are processed. This data is not used to identify individual users.

**Service Provider:** Cloudflare, Inc., 101 Townsend St, San Francisco, CA 94107, USA. Privacy Policy: https://www.cloudflare.com/privacypolicy/

**Legal basis:** Art. 6(1)(b) and (f) GDPR.

## 5. Advertising (Google AdMob)

To cover server costs, the app shows advertisements via the **Google Mobile Ads SDK (AdMob)**. Specifically, a "Rewarded Video" format is shown before downloading a wallpaper.

Google AdMob may process the following data:

- IP address
- Advertising identifier (IDFA), if you have consented via App Tracking Transparency
- General device information (model, iOS version, language)
- Technical data for ad delivery

**Provider:** Google Ireland Limited, Gordon House, Barrow Street, Dublin 4, Ireland.
Google Privacy Policy: https://policies.google.com/privacy

Within the EU/EEA, a **consent prompt via the Google User Messaging Platform (UMP)** is shown before the first ad request. You can choose whether personalized advertising should be allowed. Currently the choice cannot be reset directly from within the app — please contact us if you wish to change it.

**Legal basis:** Art. 6(1)(a) GDPR for personalized ads; Art. 6(1)(f) GDPR for non-personalized ads.

## 6. In-App Purchase "Supporter"

If you purchase the optional "Supporter" version, ads will be permanently disabled for you. The transaction is processed entirely via **Apple StoreKit**; the provider of this app does not receive personal data from Apple — only anonymized sales statistics.

Apple Privacy Policy: https://www.apple.com/legal/privacy/

**Legal basis:** Art. 6(1)(b) GDPR.

## 7. Cookies and Tracking

The app itself does not set any cookies. Content embedded in Google ads may use technically required identifiers (e.g. for frequency capping). Details can be found in Google's privacy policy (see above).

## 8. Retention Period

- **Local data** (favorites, caches) remains on your device until you delete it via the app or the system, or uninstall the app.
- **Anonymized server logs** are automatically deleted after no more than 30 days.
- **Advertising and tracking data** is subject to the retention periods of Google and the selected ad networks.

## 9. Sharing with Third Parties

Your data is only shared with the service providers mentioned in this policy (Cloudflare, Google AdMob, Apple) and only to the extent described.

## 10. Your Rights

Under GDPR, you have the following rights:

- Right to access (Art. 15 GDPR)
- Right to rectification (Art. 16 GDPR)
- Right to erasure (Art. 17 GDPR)
- Right to restriction of processing (Art. 18 GDPR)
- Right to data portability (Art. 20 GDPR)
- Right to object (Art. 21 GDPR)
- Right to lodge a complaint with a supervisory authority (Art. 77 GDPR)

To exercise your rights, please contact: qlappz@gmail.com

## 11. Changes to this Privacy Policy

This privacy policy may be updated when app functionality or legal requirements change. The current version is always available at the URL provided in App Store Connect.
