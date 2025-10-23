# Emabooks - Sistema de Gestão de Livros

Aplicativo Android desenvolvido em Kotlin para gerenciamento de livros da biblioteca da Universidade de Fortaleza (UNIFOR).

## Descrição

O Emabooks é um sistema mobile de gestão de acervo bibliográfico que permite:
- Cadastro de livros
- Consulta e busca de títulos
- Gerenciamento de categorias
- Controle de quantidade disponível
- Interface moderna e intuitiva

## Tecnologias Utilizadas

- **Linguagem**: Kotlin
- **Framework UI**: Jetpack Compose
- **Arquitetura**: MVVM (Model-View-ViewModel)
- **Build System**: Gradle (Kotlin DSL)
- **Minimum SDK**: 24 (Android 7.0)
- **Target SDK**: 34 (Android 14)

## Estrutura do Projeto

```
emabooks-devmobile-unifor2025/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/br/edu/unifor/emabooks/
│   │       │   ├── MainActivity.kt
│   │       │   └── ui/theme/
│   │       │       ├── Color.kt
│   │       │       ├── Theme.kt
│   │       │       └── Type.kt
│   │       ├── res/
│   │       │   ├── values/
│   │       │   │   ├── strings.xml
│   │       │   │   ├── colors.xml
│   │       │   │   └── themes.xml
│   │       │   └── xml/
│   │       └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## Pré-requisitos

- Android Studio Hedgehog | 2023.1.1 ou superior
- JDK 8 ou superior
- Android SDK 34
- Gradle 8.2

## Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/lucasbraide-unifor/emabooks-devmobile-unifor2025.git
```

2. Abra o projeto no Android Studio

3. Aguarde a sincronização do Gradle

4. Execute o aplicativo em um emulador ou dispositivo físico:
   - Clique em "Run" ou pressione Shift+F10

## Funcionalidades Planejadas

- [ ] Tela inicial com lista de livros
- [ ] Tela de detalhes do livro
- [ ] Formulário de cadastro de livros
- [ ] Busca e filtros
- [ ] Integração com banco de dados local (Room)
- [ ] Autenticação de usuários
- [ ] Empréstimo e devolução de livros
- [ ] Relatórios e estatísticas

## Padrão de Cores

O aplicativo utiliza as cores institucionais da UNIFOR:
- **Primary**: #0056A4 (Azul UNIFOR)
- **Secondary**: #4A90E2 (Azul UNIFOR Claro)
- **Dark**: #003D73 (Azul UNIFOR Escuro)

## Contribuindo

Este é um projeto acadêmico desenvolvido para a disciplina de Desenvolvimento Mobile da UNIFOR.

## Licença

Projeto acadêmico - Universidade de Fortaleza © 2025

## Autor

Desenvolvido como trabalho da disciplina de Desenvolvimento Mobile - UNIFOR 2025
