# Recomeço — edição profissional Android

A identidade foi preparada com:
- Nome: Recomeço
- ID Android: com.recomeco.app
- orientação vertical
- tema roxo do Recomeço
- manifesto PWA
- ícone vetorial de referência
- splash/tela inicial já representada pelo onboarding do aplicativo
- estrutura Capacitor para Android

## Gerar o APK
Num computador com Node.js + Android Studio + Android SDK:

npm install
npm run build:web
npm run android:add
npm run android:sync
npm run android:open

No Android Studio:
Build > Generate App Bundles or APKs > Generate APKs

Para a Play Store, gerar AAB assinado.

## Nota
O código está pronto para a etapa de compilação, mas este ambiente de chat não tem Android SDK/Gradle para entregar um APK assinado diretamente.
