# 🎯 Fokus

<div align="center">
  <img src="./assets/images/logo.png" alt="Fokus Logo" width="200"/>
  
  <p><strong>Otimize sua produtividade, mergulhe no que importa</strong></p>
  
  ![React Native](https://img.shields.io/badge/React_Native-0.76.6-61DAFB?style=for-the-badge&logo=react&logoColor=white)
  ![Expo](https://img.shields.io/badge/Expo-52.0.26-000020?style=for-the-badge&logo=expo&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/TypeScript-5.3.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
</div>

---

## 📋 Sobre o Projeto

**Fokus** é um aplicativo mobile de produtividade baseado na técnica Pomodoro, desenvolvido com React Native e Expo. O app oferece uma experiência simples e intuitiva para gerenciar ciclos de foco e pausas, além de incluir funcionalidades extras como busca de endereços via CEP.

Este projeto foi desenvolvido para fins educacionais como parte do curso de Análise e Desenvolvimento de Sistemas (ADS) no SENAC Rio.

---

## ✨ Funcionalidades

### 🍅 Timer Pomodoro
- **Foco**: 25 minutos de concentração total
- **Pausa Curta**: 5 minutos de descanso
- **Pausa Longa**: 15 minutos de relaxamento
- Controles de play/pause
- Interface visual intuitiva com feedback de estado

### 🏠 Busca de Endereço (ViaCEP)
- Busca de endereços completos através do CEP
- Validação de CEP inválido
- Feedback visual de carregamento
- Tratamento de erros de conexão
- Interface limpa e responsiva

---

## 🚀 Tecnologias Utilizadas

- **[React Native](https://reactnative.dev/)** `0.76.6` - Framework mobile
- **[Expo](https://expo.dev/)** `~52.0.26` - Plataforma de desenvolvimento
- **[Expo Router](https://docs.expo.dev/router/introduction/)** `~4.0.21` - Navegação file-based
- **[TypeScript](https://www.typescriptlang.org/)** `5.3.3` - Tipagem estática
- **[React Navigation](https://reactnavigation.org/)** - Sistema de navegação
- **[Expo Haptics](https://docs.expo.dev/versions/latest/sdk/haptics/)** - Feedback tátil

### Bibliotecas Adicionais
- `react-native-reanimated` - Animações fluidas
- `react-native-gesture-handler` - Gestos nativos
- `expo-blur` - Efeitos visuais
- `react-native-svg` - Ícones customizados

---

## 📱 Screenshots

<div align="center">
  <img src="./assets/images/tela_inicial.png" alt="Tela Inicial" width="250"/>
  <img src="./assets/images/pomodoro.png" alt="Timer Pomodoro" width="250"/>
</div>

---

## 🔧 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- **[Node.js](https://nodejs.org/)** (versão LTS recomendada)
- **[npm](https://www.npmjs.com/)** ou **[yarn](https://yarnpkg.com/)**
- **[Expo CLI](https://docs.expo.dev/get-started/installation/)**
- **[Git](https://git-scm.com/)**

Para testar no dispositivo físico:
- **[Expo Go](https://expo.dev/client)** (disponível na App Store e Google Play)

---

## ⚙️ Instalação e Configuração

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/fokus.git
cd fokus
```

### 2. Instale as dependências
```bash
npm install
# ou
yarn install
```

### 3. Inicie o projeto
```bash
npm start
# ou
yarn start
```

### 4. Execute em plataformas específicas

**Android:**
```bash
npm run android
```

**iOS:**
```bash
npm run ios
```

**Web:**
```bash
npm run web
```

---

## 📂 Estrutura do Projeto

```
fokus/
├── app/                      # Rotas do aplicativo (Expo Router)
│   ├── (tabs)/              # Navegação por abas
│   ├── index.jsx            # Tela inicial
│   ├── pomodoro.jsx         # Timer Pomodoro
│   └── viacep.jsx           # Busca de CEP
├── assets/                  # Recursos estáticos
│   ├── fonts/               # Fontes customizadas
│   └── images/              # Imagens e ícones
├── components/              # Componentes reutilizáveis
│   ├── ActionButton/        # Botão de ação
│   ├── FokusButton/         # Botão principal
│   ├── Icons/               # Ícones customizados
│   └── Timer/               # Componente do timer
├── app.json                 # Configuração do Expo
├── package.json             # Dependências do projeto
└── tsconfig.json            # Configuração TypeScript
```

---

## 🎨 Paleta de Cores

```css
--background: #021123      /* Fundo principal */
--card-bg: #14448080       /* Fundo dos cards */
--card-border: #144480     /* Borda dos cards */
--input-bg: #0E253F        /* Fundo dos inputs */
--input-border: #294763    /* Borda dos inputs */
--text-primary: #FFFFFF    /* Texto principal */
--text-secondary: #98A0A8  /* Texto secundário */
--text-card: #D6E4F0       /* Texto dos cards */
--error: #FF7A7A           /* Mensagens de erro */
```

---

## 🧪 Testes

Execute os testes com:

```bash
npm test
# ou
yarn test
```

---

## 📄 Scripts Disponíveis

| Comando | Descrição |
|---------|-----------|
| `npm start` | Inicia o servidor de desenvolvimento |
| `npm run android` | Abre o app no emulador/dispositivo Android |
| `npm run ios` | Abre o app no simulador iOS |
| `npm run web` | Abre o app no navegador |
| `npm test` | Executa os testes |
| `npm run lint` | Verifica o código com ESLint |

---

## 🌐 API Utilizada

- **[ViaCEP](https://viacep.com.br/)** - API gratuita para consulta de CEP

---

## 🎯 Próximas Funcionalidades

- [ ] Persistência de dados com AsyncStorage
- [ ] Histórico de sessões Pomodoro
- [ ] Notificações ao fim dos timers
- [ ] Tema claro/escuro
- [ ] Estatísticas de produtividade
- [ ] Sons personalizados
- [ ] Integração com calendário

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

---

## 📝 Licença

Este é um projeto fictício desenvolvido para fins educacionais, sem fins comerciais.

**Desenvolvido com 💙 por Fábio - Aluno SENAC Rio**

---

## 📧 Contato

Para dúvidas ou sugestões sobre o projeto:

- GitHub: [@seu-usuario](https://github.com/FmGs85)


---

<div align="center">
  <p>⭐ Se este projeto foi útil, deixe uma estrela!</p>
</div>
