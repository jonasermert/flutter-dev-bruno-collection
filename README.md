# Flutter Development API Toolkit for Bruno

Diese Collection ist für Flutter-App-Entwicklung gedacht und enthält typische Requests für lokale Backends, Android Emulator (`10.0.2.2`), iOS Simulator, Firebase Emulator Suite, Firestore REST, Storage, Auth, GraphQL und Webhook-Tests.

## Import

1. ZIP entpacken.
2. Bruno öffnen.
3. **Open Collection** wählen.
4. Den entpackten Ordner `flutter-dev-bruno-collection` auswählen.
5. Environment `Local` oder `Dev` auswählen und Variablen anpassen.

## Wichtige Variablen

- `api_base_url`: Backend-URL, z. B. `http://localhost:3000`
- `android_emulator_base_url`: für Android Emulator meist `http://10.0.2.2:3000`
- `firebase_project_id`: Firebase Projekt-ID oder Emulator-Projekt wie `demo-flutter-app`
- `access_token`: JWT/Firebase ID Token
- `device_id`, `platform`, `app_version`: typische Mobile-Client-Header

## Hinweis

Die Endpunkte sind bewusst generisch gehalten. Du kannst sie in Bruno direkt umbenennen und an dein echtes Flutter-Projekt anpassen.
