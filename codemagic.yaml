workflows:
  android-release:
    name: Build APK
    instance_type: mac_mini_m1
    environment: {flutter: stable}
    scripts: [flutter pub get, flutter build apk --release]
    artifacts: [build/app/outputs/flutter-apk/app-release.apk]
    publishing: {email: {recipients: [khalaff.ffaisal@gmail.com]}}
