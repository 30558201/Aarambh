LAKSHYA FINAL WEBSITE
======================

Files:
- index.html          Complete SPA frontend
- lakshya_logo.png    Supplied Lakshya logo
- track_01.mp3        Extracted audio track
- track_02.mp3        Extracted audio track
- track_03.mp3        Extracted audio track

Backend URL is already configured in index.html.

Run:
1. Keep all files in the same folder.
2. Open index.html in a browser or load the folder into the Android WebView app.
3. The frontend calls the supplied Google Apps Script backend.
4. Admin uses the Admin login button.
5. Study/video URLs are returned by the backend and opened in the built-in player.
6. The Android native layer should handle actual Google Account chooser and Android permissions.

Important:
- The web form's "Continue with Google account" is a bridge/hook. A real Android Google Account chooser requires the native Android layer / approved Google Sign-In configuration.
- API keys are not embedded in this HTML.
