# Taski To Do

Taski To Do é um aplicativo Flutter para gerenciamento de tarefas.

## Requisitos

Antes de iniciar, certifique-se de ter instalado:

- [Flutter 3.27.1](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)
- [Android Studio](https://developer.android.com/studio) ou [VS Code](https://code.visualstudio.com/)
- Emulador Android ou dispositivo físico conectado
- Xcode (para desenvolvimento iOS)

## Configuração do Projeto

1. **Clone o repositório**
   ```sh
   git clone https://github.com/seu-usuario/taski_to_do.git
   cd taski_to_do
   ```

2. **Instale as dependências**
   ```sh
   flutter pub get
   ```

3. **Configure o ambiente**
   - Para Android:
     ```sh
     flutter config --android-sdk /caminho/do/android-sdk
     ```
   - Para iOS:
     ```sh
     cd ios && pod install && cd ..
     ```

## Executando o Projeto

### Android
```sh
flutter run --release
```

### iOS
```sh
flutter run --release --no-codesign
```

### Debug Mode
```sh
flutter run
```

## Estrutura do Projeto

```
lib/
│── main.dart            # Ponto de entrada do app
│── ui/                  # Componentes da interface do usuário
│   ├── views/           # Telas do aplicativo
│   ├── widgets/         # Widgets reutilizáveis
│── viewmodels/          # Lógica de negócios e gerenciamento de estado (com Riverpod)
│── models/              # Modelos de dados
│── services/            # Serviços e APIs
│   ├── database/        # Configuração do SQLite e DAO
│── routes/              # Configurações de rotas com GoRouter
│── core/                # Configurações globais, temas e utilitários
└── tests/               # Diretório para testes automatizados
    ├── unit/            # Testes unitários
    ├── widget/          # Testes de widgets
    └── integration/     # Testes de integração
```

## Contato
Para dúvidas ou sugestões, entre em contato pelo email: [ennes.silva2014@gmail.com](mailto:ennes.silva2014@gmail.com).