# 🎮 Proggaming

> Plataforma educacional gamificada para aprendizado de programação web (HTML, CSS e JavaScript)

**[Experimente agora!](https://proggamingpage.web.app/intro/)**

[![Firebase](https://img.shields.io/badge/Firebase-Hosting-orange?logo=firebase)](https://firebase.google.com)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

## Sobre o Projeto

**Proggaming** é uma plataforma educacional desenvolvida como Trabalho de Conclusão de Curso (TCC) que utiliza gamificação para tornar o aprendizado de programação web mais interativo, envolvente e divertido. A plataforma oferece uma experiência completa com jogos educativos, sistema de progressão e um chatbot interativo.

### Principais Características

- **Jogos Educativos Interativos**: Aprenda HTML, CSS e JavaScript através de fases desafiadoras
- **Academy (Chatbot)**: Assistente virtual que responde dúvidas sobre programação
- **Sistema de Gamificação**: Níveis, XP e barra de progresso para motivar o aprendizado
- **Design Responsivo**: Interface adaptável para desktop e mobile
- **Tema Claro/Escuro**: Experiência visual personalizada
- **Autenticação Firebase**: Login seguro com e-mail/senha ou Google

## Funcionalidades

### Jogos por Linguagem

#### HTML 
Aprenda os fundamentos do HTML através de desafios práticos:
- Estrutura básica de documentos
- Tags semânticas
- Formulários e inputs
- Links e navegação
- Tabelas e listas

#### CSS (Em construção!)
Domine estilização web com exercícios progressivos:
- Propriedades básicas (`background-color`, `width`, `font-size`)
- Flexbox e Grid
- Animações e transições
- Design responsivo
- Posicionamento de elementos

#### JavaScript 
Desenvolva lógica de programação através de desafios:
- Variáveis e tipos de dados
- Estruturas condicionais
- Loops e iterações
- Funções
- Manipulação do DOM

### Academy - Chatbot Educacional

- Respostas instantâneas sobre conceitos de programação
- Atalhos rápidos para perguntas frequentes
- Interface conversacional intuitiva
- Suporte contextual durante os jogos

### Sistema de Progressão

- **Níveis**: Avance conforme completa desafios
- **XP (Experiência)**: Ganhe pontos por cada fase concluída
- **Barra de Progresso**: Visualize seu desenvolvimento em tempo real
- **Conquistas**: Desbloqueie medalhas e reconhecimentos

## Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna e responsiva
- **JavaScript (ES6+)**: Interatividade e lógica do jogo

### Backend & Hospedagem
- **Firebase Hosting**: Deploy e hospedagem
- **Firebase Firestore**: Banco de dados NoSQL
- **Firebase Authentication**: Sistema de autenticação

### Bibliotecas & Recursos
- **Boxicons**: Biblioteca de ícones
- **Google Fonts**: Tipografia (Press Start 2P para tema retrô)
- **Firebase SDK 10.7.1**: Integração com serviços Firebase

## Estrutura do Projeto

```
ProggamingWebSite/
│
├── NOVO TEMA-TCC/
│   ├── firebase.json              # Configuração do Firebase
│   │
│   └── public/                    # Arquivos públicos da aplicação
│       ├── index.html             # Página de login/cadastro
│       ├── style.css              # Estilos globais
│       ├── script.js              # Lógica de autenticação
│       │
│       ├── Academy/               # Chatbot educacional
│       ├── TelaPrincipal/         # Dashboard principal
│       ├── intro/                 # Tela de introdução
│       │
│       ├── gameHTML/              # Jogos de HTML
│       │   ├── Fase1/
│       │   ├── Fase2/
│       │   └── ... (até Fase10)
│       │
│       ├── gameCSS/               # Jogos de CSS
│       ├── gameJS/                # Jogos de JavaScript
│       │
│       ├── avatares/              # Imagens de avatares
│       ├── assets/                # Recursos gerais
│       ├── adminK230193/          # Painel administrativo
│       ├── Amigos/                # Sistema social
│       ├── excluir-conta/         # Gerenciamento de conta
│       │
│       ├── Termos_de_uso.pdf      # Termos de uso
│       ├── politica_privacidade.pdf
│       └── 404.html               # Página de erro
│
└── README.md                      # Documentação do projeto
```

## Como Executar

### Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- Conexão com internet (para Firebase)
- *(Opcional)* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) para desenvolvimento local

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/AlvesKZ/ProggamingWebSite.git
   ```

2. **Navegue até o diretório do projeto**
   ```bash
   cd ProggamingWebSite/NOVO\ TEMA-TCC/
   ```

3. **Abra o projeto**
   
   **Opção 1: Usando Live Server (Recomendado)**
   - Abra `public/index.html` com Live Server no VS Code
   
   **Opção 2: Diretamente no navegador**
   - Abra `public/index.html` no seu navegador
   
   **Opção 3: Servidor HTTP local**
   ```bash
   # Se tiver Python instalado
   cd public
   python -m http.server 8000
   # Acesse: http://localhost:8000
   ```

### Acessar Versão Online

O projeto está hospedado no Firebase Hosting:

**🔗 [Acesse o Proggaming agora!](https://proggamingpage.web.app/intro/)**

```
https://proggamingpage.web.app/intro/
```

## Como Usar

1. **Cadastro/Login**
   - Crie uma conta com e-mail e senha
   - Ou faça login com sua conta Google
   - Acesso como convidado disponível para visitantes

2. **Escolha uma Linguagem**
   - Selecione HTML, CSS ou JavaScript
   - Comece pela Fase 1 de cada linguagem

3. **Complete os Desafios**
   - Leia as instruções de cada fase
   - Escreva o código solicitado
   - Valide sua resposta
   - Ganhe XP e avance de nível

4. **Use o Academy**
   - Clique no ícone do chatbot
   - Faça perguntas sobre programação
   - Receba orientações e dicas

## Temas e Personalização

- **Tema Claro**: Interface clara e moderna
- **Tema Escuro**: Reduz fadiga visual em ambientes com pouca luz
- **Cursores Customizados**: Estilo pixel art retrô
- **Fonte Pixel**: Press Start 2P para experiência nostálgica

## Compatibilidade

| Plataforma | Suporte |
|------------|---------|
| Desktop (Chrome, Firefox, Edge, Safari) | ✅ Completo |
| Mobile (iOS Safari, Chrome Android) | ⚠️ Parcial |
| Tablets | ✅ Completo |
| PWA (Progressive Web App) | ✅ Instalável |

## Segurança e Privacidade

- Autenticação segura via Firebase Authentication
- Dados armazenados de forma criptografada no Firestore
- Conformidade com termos de uso e política de privacidade
- Verificação de e-mail obrigatória para registro

## Contribuindo

Este é um projeto acadêmico (TCC), mas sugestões são bem-vindas!

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'feat: adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## Licença

Este projeto é de uso acadêmico. Todos os direitos reservados.

## Equipe

Desenvolvido com ❤️ pela **Proggaming Team**

- Desenvolvimento e Design
- Pesquisa e Conteúdo Educacional
- Testes e QA

## Contato

- **GitHub**: [@AlvesKZ](https://github.com/AlvesKZ)
- **Website**: [proggamingpage.web.app/intro](https://proggamingpage.web.app/intro/)

---

**⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!**
