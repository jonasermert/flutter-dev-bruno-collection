Flutter Development API Toolkit for Bruno

This collection is designed for Flutter app development and includes common requests for local backends, Android Emulator (10.0.2.2), iOS Simulator, Firebase Emulator Suite, Firestore REST API, Firebase Storage, Authentication, GraphQL, and webhook testing.

Import

1. Extract the ZIP archive.
2. Open Bruno.
3. Select Open Collection.
4. Choose the extracted folder flutter-dev-bruno-collection.
5. Select the Local or Dev environment and adjust the variables as needed.

Important Variables

* api_base_url: Backend URL, e.g. http://localhost:3000
* android_emulator_base_url: Usually http://10.0.2.2:3000 for Android Emulator
* firebase_project_id: Firebase project ID or emulator project such as demo-flutter-app
* access_token: JWT or Firebase ID token
* device_id, platform, app_version: Typical mobile client headers

Notes

The endpoints are intentionally generic so you can easily rename and customize them directly in Bruno for your own Flutter projects.
