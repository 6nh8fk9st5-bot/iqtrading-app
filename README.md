# IQTRADING Flutter App

تطبيق Flutter جاهز يفتح موقع IQTRADING داخل WebView مع Splash Screen وشعار التطبيق.

## التشغيل

```bash
flutter create .
flutter pub get
flutter run
```

## بناء Android APK

```bash
flutter build apk --release
```

الملف بيطلع عادة هون:
`build/app/outputs/flutter-apk/app-release.apk`

## iOS

لازم Mac + Xcode + Apple Developer Account.

```bash
flutter build ios --release
```

بعدها تفتح مجلد ios على Xcode وترفع التطبيق من Archive.

## ملاحظات مهمة للـ App Store

لأن التطبيق متعلق بالتداول، حضّر روابط:
- Privacy Policy
- Terms & Conditions
- Risk Disclaimer

وخلّي الموقع شغال على HTTPS دائماً.
