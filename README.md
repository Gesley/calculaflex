# CalculaFlex

CalculaFlex é um aplicativo Android que ajuda os usuários a calcular o melhor custo-benefício entre diferentes tipos de combustível para seu veículo. Este projeto utiliza o Kotlin como linguagem principal e está integrado com serviços Firebase para autenticação e análise de uso.

## Funcionalidades

- Suporte para dispositivos Android com `minSdk` 21 e `targetSdk` 30.
- Autenticação de usuários via Firebase Authentication.
- Animações utilizando a biblioteca Lottie.
- Navegação implementada com o Jetpack Navigation.
- Interface com suporte ao ViewBinding para manipulação de views.

## Estrutura do Projeto

### `build.gradle` Configuração

Este projeto utiliza as seguintes configurações no `build.gradle`:

- **Plugins:**
  - `com.android.application`: Plugin principal para aplicativos Android.
  - `kotlin-android`: Suporte ao Kotlin para desenvolvimento Android.
  - `androidx.navigation.safeargs.kotlin`: Gera classes seguras para passar argumentos entre fragmentos.
  - `com.google.gms.google-services`: Integração dos serviços do Google, incluindo Firebase.

- **Android SDK:**
  - `compileSdk 30`
  - `minSdk 21`
  - `targetSdk 30`

- **Configurações de build:**
  - Versão do código e nome da versão definidos em `versionCode` e `versionName`.
  - Arquivo ProGuard utilizado para otimizações em builds de release.

- **Kotlin Options:**
  - Configurações de compatibilidade para o Kotlin, com o alvo JVM 1.8.

- **Dependências principais:**
  - `androidx` para componentes padrão do Android.
  - Firebase para autenticação (`firebase-auth`) e analytics.
  - Lottie para animações.
  - Jetpack Navigation para gerenciar navegação de fragmentos.
  
## Dependências

### Bibliotecas principais utilizadas:

- **Core e UI:**
  - `androidx.core:core-ktx`
  - `androidx.appcompat:appcompat`
  - `com.google.android.material:material`
  - `androidx.constraintlayout:constraintlayout`

- **Firebase:**
  - `firebase-auth`: Para autenticação de usuários.
  - `firebase-analytics`: Para monitoramento e análise de eventos de uso do app.

- **Animações:**
  - `Lottie`: Biblioteca para animações JSON vetoriais.

- **Navegação:**
  - `androidx.navigation:navigation-fragment-ktx`
  - `androidx.navigation:navigation-ui-ktx`

- **Testes:**
  - `junit:junit`: Para testes unitários.
  - `androidx.test.ext:junit`: Para testes instrumentados.
  - `androidx.test.espresso:espresso-core`: Para testes de UI.

## Requisitos de Instalação

- Android Studio 4.2 ou superior.
- Android SDK configurado.
- Firebase configurado para o projeto, com os serviços necessários habilitados (autenticação e analytics).
  
## Como Configurar o Projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/Gesley/calculaflex.git
    ```
2. Abra o projeto no Android Studio.
3. Sincronize as dependências do Gradle.
4. Configure o Firebase para seu projeto, seguindo as instruções de [integração do Firebase com Android](https://firebase.google.com/docs/android/setup).
5. Compile e execute o aplicativo em um emulador ou dispositivo físico.

## Contribuindo

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades. Por favor, faça um fork do repositório e abra um pull request com suas alterações.

## Licença

Este projeto está licenciado sob a licença MIT.
