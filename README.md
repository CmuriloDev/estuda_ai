# Estuda Aí (estuda_ai)

App mobile (protótipo) desenvolvido em **Flutter (Dart)** para **gerenciar sessões de estudo**, acompanhar **histórico de tempo estudado** e exibir **estatísticas/relatórios**.

**Diferencial:** integração com a **API da Wikipedia** para exibir curiosidades/contexto relacionados ao tema da sessão em andamento (ex.: sessão de Geografia → informações relacionadas ao tema).

---

## 🖼️ Screenshots
> Adicione imagens em `docs/images/` e referencie aqui.

![Home](docs/images/home.png)
![New Session](docs/images/new_session.png)
![Stats](docs/images/stats.png)
![Wikipedia Curiosity](docs/images/wiki_curiosity.png)

---

## ✨ Funcionalidades
- Criar sessões de estudo
- Histórico de tempo estudado
- Estatísticas/relatórios
- Curiosidades por tema via Wikipedia API

---

## 🧰 Stack
- Flutter / Dart
- Consumo de API REST (Wikipedia) e tratamento de JSON
- Execução local (protótipo)

---

## ▶️ Como rodar localmente (Android)

### Pré-requisitos
- Flutter SDK
- Android Studio + Android SDK
- Emulador Android (AVD) **ou** dispositivo físico

### Rodando o projeto
```bash
git clone https://github.com/CmuriloDev/estuda_ai.git
cd estuda_ai
flutter pub get
flutter run
