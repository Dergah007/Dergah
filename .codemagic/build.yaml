workflows:
  version: 2
  build:
    name: Build APK
    jobs:
      - build:
          name: Build Flutter APK
          timeout: 30
          max_build_duration: 120
          environment:
            flutter: stable
            android: true
          scripts:
            - flutter pub get
            - flutter build apk --release
