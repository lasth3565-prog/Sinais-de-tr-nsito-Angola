# Escola de Condução — Android

Aplicação Android nativa em modo WebView para a página Escola de Condução (Angola), com versão web empacotada localmente e compatibilidade mínima Android 5.0 (API 21).

## O que está incluído
- Conteúdo HTML do site dentro do aplicativo, para abrir sem depender da hospedagem GitHub Pages.
- Correção do bloco JavaScript sem fecho que impedia a inicialização do site.
- JavaScript e armazenamento local do WebView, necessários para perfil, progresso, temas e favoritos.
- Escolha de fotografias/ficheiros pelo seletor Android.
- Abertura de links externos (por exemplo, WhatsApp) fora do WebView.
- Workflow GitHub Actions para gerar e disponibilizar um APK de depuração.

## Gerar o APK
Abra a pasta no Android Studio (JDK 17 e Android SDK 35) e execute **Build > Build APK(s)**. O APK fica em `app/build/outputs/apk/debug/app-debug.apk`.

Ou envie este projeto para um repositório GitHub e execute a ação **Build APK** na aba **Actions**; o APK aparece como artefacto transferível da execução.

O APK debug serve para instalação/teste direto. Para publicar na Play Store é necessário gerar um APK/AAB de release assinado com uma chave sua.
