# NLW Pocket Mobile - Swift

## Visão Geral

Este projeto é um aplicativo iOS desenvolvido em Swift, seguindo a arquitetura **MVVM-C** (Model-View-ViewModel-Coordinator) para facilitar a escalabilidade, modularidade e separação de responsabilidades. Ele é projetado para fornecer uma experiência fluida de navegação e interação com componentes reutilizáveis.

### Link do Design
O design do aplicativo pode ser encontrado no Figma: [Figma Community Project](https://www.figma.com/community/file/1448070647757721748)

---

## Arquitetura do Projeto

### MVVM-C (Model-View-ViewModel-Coordinator)
A arquitetura **MVVM-C** é composta por:
1. **Model**: Gerencia os dados e a lógica de negócios do aplicativo.
2. **View**: Responsável pela interface do usuário, observando as alterações do ViewModel.
3. **ViewModel**: Atua como a ponte entre a View e o Model, processando dados para a apresentação.
4. **Coordinator**: Gerencia a navegação e a criação de ViewControllers para manter as responsabilidades bem definidas.

#### Detalhamento das Pastas
- **Constants**: Contém valores constantes e configurações globais usadas em toda a aplicação.
- **Features**: Abrange os principais componentes do app.
  - **Components**: UI reutilizável e componentes auxiliares.
  - **Coordinator**: Implementação dos coordenadores responsáveis pela navegação.
  - **Extensions**: Extensões para classes Swift, adicionando funcionalidades.
  - **Models**: Estruturas que representam os dados do aplicativo.
  - **Scenes**: Conjunto de Views e ViewModels que compõem diferentes telas.

---

## Funcionalidades

- Navegação entre diferentes telas utilizando a arquitetura MVVM-C.
- UI responsiva e modular baseada no design do Figma.
- Gerenciamento eficiente de dados utilizando modelos estruturados.

---

## Requisitos

Para executar o projeto, você precisará de:
- **Xcode 13.0 ou superior**
- **macOS Monterey ou superior**
- **Swift 5.5**

---

## Como Rodar o Projeto

1. Clone o repositório: ```git clone https://github.com/bsmvictor/NearbyApp-NLW ```
2. Abra o arquivo `NearbyApp NLW.xcodeproj` no Xcode.
3. Compile o projeto pressionando `Cmd + R`.

---

## Estrutura de Pastas
```
NearbyApp NLW
├── AppDelegate.swift       # Configuração inicial do aplicativo
├── SceneDelegate.swift     # Gerenciamento de janelas e cenas
├── Info.plist              # Configurações do projeto
├── Resources               # Recursos como assets e strings
└── Sources
    ├── Constants           # Valores globais e constantes
    ├── Features
    │   ├── Components      # UI reutilizável
    │   ├── Coordinator     # Lógica de navegação
    │   ├── Extensions      # Extensões de classes
    │   ├── Models          # Dados do app
    │   └── Scenes          # Views e ViewModels organizados por tela
```

---

## Contribuições

Contribuições são bem-vindas! Siga o fluxo padrão de pull requests:

1. Faça um fork do repositório.
2. Crie uma branch para sua feature ou correção.
3. Envie um pull request com uma descrição clara.
