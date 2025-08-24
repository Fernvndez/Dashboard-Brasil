# Dashboard Brasil 🇧🇷

Um dashboard moderno e interativo apresentando dados e estatísticas relevantes sobre o Brasil, desenvolvido com React, TypeScript e Tailwind CSS.

## ✨ Características

- **Interface Moderna**: Design limpo e responsivo usando Tailwind CSS
- **Performance Otimizada**: Construído com Vite para desenvolvimento rápido
- **Type Safety**: Desenvolvido em TypeScript para maior confiabilidade
- **Componentes Reutilizáveis**: Arquitetura modular e escalável
- **Responsive Design**: Compatível com dispositivos móveis e desktop

## 🚀 Tecnologias Utilizadas

- **Frontend Framework**: React 18
- **Linguagem**: TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide React
- **Linting**: ESLint com configurações TypeScript

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/Fernvndez/Dashboard-Brasil.git
cd Dashboard-Brasil
```

2. Instale as dependências:
```bash
npm install
```

3. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

4. Abra seu navegador em `http://localhost:5173`

## 🛠️ Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção
- `npm run lint` - Executa o linter para verificar código

## 📁 Estrutura do Projeto

```
Dashboard-Brasil/
├── public/
├── src/
│   ├── components/     # Componentes reutilizáveis
│   ├── pages/         # Páginas da aplicação
│   ├── hooks/         # Custom hooks
│   ├── utils/         # Funções utilitárias
│   ├── types/         # Definições de tipos TypeScript
│   ├── App.tsx        # Componente principal
│   ├── main.tsx       # Ponto de entrada
│   └── index.css      # Estilos globais
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts
```

## 🎨 Design System

O projeto utiliza um sistema de design consistente com:

- **Palette de Cores**: Cores inspiradas na bandeira brasileira
- **Typography**: Hierarquia tipográfica bem definida
- **Spacing**: Sistema de espaçamento baseado em 8px
- **Components**: Componentes padronizados e acessíveis

## 🔧 Configuração

### Personalização do Tailwind

O arquivo `tailwind.config.js` pode ser customizado para incluir:

- Cores personalizadas do tema brasileiro
- Breakpoints específicos
- Componentes customizados
- Plugins adicionais

### Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto para configurações:

```env
VITE_API_URL=sua_api_url_aqui
VITE_APP_NAME=Dashboard Brasil
```

## 📱 Responsividade

O dashboard é totalmente responsivo com breakpoints:

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📋 Roadmap

- [ ] Integração com APIs de dados brasileiros
- [ ] Dashboard de indicadores econômicos
- [ ] Visualizações de dados demográficos
- [ ] Mapas interativos
- [ ] Modo escuro/claro
- [ ] Exportação de relatórios
- [ ] Filtros avançados
- [ ] PWA (Progressive Web App)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Autor

**Fernandez** - [@Fernvndez](https://github.com/Fernvndez)

## 🙏 Agradecimentos

- Comunidade React e TypeScript
- Contribuidores do Tailwind CSS
- Dados públicos disponibilizados pelo governo brasileiro

---

<p align="center">
  Feito com ❤️ para o Brasil 🇧🇷
</p>
