# Festas de São Pedro Caíde de Rei 🎉

Website oficial das Festas de São Pedro de Caíde de Rei - uma plataforma dinâmica e envolvente com informações, recursos e atualizações sobre a celebração anual.

**🌐 [Visita o Website](https://festasspedrocaide.netlify.app/)**

## 📋 Tabela de Conteúdos

- [Sobre](#sobre)
- [Tecnologias](#tecnologias)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Desenvolvimento](#desenvolvimento)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Deployment](#deployment)
- [Contribuição](#contribuição)

## Sobre

O website das Festas de São Pedro é uma plataforma moderna desenvolvida para compartilhar informações, história e atualizações sobre uma das celebrações mais importantes de Caíde de Rei. O site oferece uma experiência responsiva e intuitiva para todos os visitantes.

## Tecnologias

- **[Astro](https://astro.build)** - Gerador de sites estático moderno para criar websites rápidos usando componentes
- **[Tailwind CSS](https://tailwindcss.com)** - Framework CSS utilitário para design custom
- **[Netlify](https://netlify.com)** - Plataforma de hospedagem e deployment

## Funcionalidades

✨ **Design Responsivo** - Experiência perfeita em todos os dispositivos (móvel, tablet, desktop)

✨ **Conteúdo Dinâmico** - Fácil atualização de conteúdo com Astro

✨ **Performance Otimizada** - Geração estática para velocidade máxima

✨ **Estilo Customizado** - Branding completo com Tailwind CSS

✨ **SEO Friendly** - Otimizado para motores de busca

## Instalação

### Pré-requisitos

- Node.js 16.0 ou superior
- npm ou yarn

### Passos

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/DiogoMotaMoreira/FestasS-oPedro.git
   cd FestasS-oPedro
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   # ou
   yarn install
   ```

3. **Crie o arquivo `.env` (se necessário):**
   ```bash
   cp .env.example .env.local
   ```

## Desenvolvimento

### Iniciar servidor de desenvolvimento

```bash
npm run dev
```

O servidor estará disponível em `http://localhost:3000`

### Comandos Disponíveis

| Comando | Descrição |
|---------|-----------|
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run build` | Compila o projeto para produção (`./dist/`) |
| `npm run preview` | Prévia local da versão compilada |
| `npm run astro -- --help` | Ajuda com comandos Astro |

## Estrutura do Projeto

```
FestasS-oPedro/
├── FestasSPedro/
│   ├── public/              # Arquivos estáticos (imagens, fonts, etc)
│   │   └── favicon.svg
│   ├── src/
│   │   ├── layouts/         # Layouts reutilizáveis
│   │   │   └── Layout.astro
│   │   ├── pages/           # Páginas (rotas automáticas)
│   │   │   └── index.astro
│   │   └── components/      # Componentes reutilizáveis
│   ├── package.json
│   └── astro.config.mjs     # Configuração do Astro
├── README.md
└── .gitignore
```

## Deployment

O projeto está configurado para deployment automático na **Netlify**.

### Deploy Manual

1. Compile o projeto:
   ```bash
   npm run build
   ```

2. A pasta `dist/` contém os arquivos prontos para produção

3. Faça upload para Netlify ou qualquer outro serviço de hospedagem estático

### Deploy Automático com Netlify

O repositório está conectado ao Netlify. Cada push para `main` dispara um deploy automático.

**Status atual:** [Visita o site](https://festasspedrocaide.netlify.app/)

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um **fork** do repositório
2. Crie uma branch para sua funcionalidade (`git checkout -b feature/MinhaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFuncionalidade'`)
4. Push para a branch (`git push origin feature/MinhaFuncionalidade`)
5. Abra um **Pull Request**

## Documentação Adicional

- [Documentação Astro](https://docs.astro.build)
- [Documentação Tailwind CSS](https://tailwindcss.com/docs)
- [Netlify Docs](https://docs.netlify.com)

---

**Desenvolvido com ❤️**
