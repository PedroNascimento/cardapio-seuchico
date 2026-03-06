<div align="center">
  <img src="public/images/logo.png" alt="Logo Seu Chico Botequim" width="150" />
</div>

<br />

<div align="center">
  <strong>Seu Chico Botequim – Cardápio Digital</strong>
  <br />
  Uma aplicação frontend moderna e responsiva de cardápio digital, com suporte multilíngue e excelente experiência de usuário.
</div>

<div align="center">
  <br />
  <a href="https://seuchicobotequim-cardapio.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Acessar_Cardápio_Digital-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Deploy na Vercel" />
  </a>
</div>

## 📌 Sobre o Projeto

O **Cardápio Digital – Seu Chico Botequim** é uma aplicação web desenvolvida para modernizar a experiência do cliente no estabelecimento. O projeto surgiu da necessidade de substituir o cardápio físico por uma solução digital acessível, rápida e fácil de navegar — especialmente em dispositivos móveis.

O objetivo é oferecer uma experiência fluida e imersiva, onde o cliente localiza qualquer prato ou bebida rapidamente, com informações claras sobre descrição, código e preço — tudo isso disponível em **5 idiomas**, sem recarregar a página.

O desenvolvimento priorizou **acessibilidade visual** (conformidade WCAG AA), qualidade do código TypeScript e uma UI refinada, tornando este projeto um exemplo de construção frontend moderna ponta a ponta.

### 🎯 Principais Funcionalidades Adotadas

- **Modernidade Visual e Mobile-First**: Interface projetada especificamente para oferecer a melhor experiência em smartphones, mas se adaptando em harmonia até para telas desktop.
- **Multilíngue Dinâmico**: Abstração elaborada para suportar até 5 idiomas (Português, Inglês, Espanhol, Francês e Italiano). A troca de idiomas traduz seções e pratos em tempo real utilizando a _Context API_ do React.
- **Navegação Elegante e Spy-Scroll**: A barra de navegação das categorias rastreia suavemente onde o usuário está no cardápio. À medida que percorre a tela, o indicador ativo transita (_Intersection Observer_).
- **Refinamento de UX Analítico**: Foco severo em espaçamento de "Touch Targets" (área de toque WCAG para botões) no mobile, indicadores de scroll horizontal de feedback visual (gradiente edge-fade) e contraste das cores.
- **SEO & Core Web Vitals Auditado**: Arquivos de metadados, Open Graph preview para links (WhatsApp) e compressão das imagens WebP integradas utilizando diretrizes estritas do framework.

## 💻 Tecnologias Empregadas

Toda a arquitetura técnica foi firmada nas tecnologias nativas mais recomendadas do mercado de Frontend contemporâneo:

- **[React](https://reactjs.org/)** – A fundação para criação de interfaces interativas e reativas.
- **[Next.js 14/15 (App Router)](https://nextjs.org/)** – A espinha dorsal do projeto para providenciar SSG e performance robusta.
- **[TypeScript](https://www.typescriptlang.org/)** – Para entregar integridade, tipagem estática e manutenção de contratos do Menu TS.
- **[Tailwind CSS](https://tailwindcss.com/)** – Empregado para estilização sem sair da camada HTML com design tokens reutilizáveis.
- **[Lucide React](https://lucide.dev/)** – Bibliotecas de vetores limpos e adaptáveis.
- **[Vercel](https://vercel.com/)** – Hospedagem Edge/Serverless otimizada para o ecossistema e repositório.

## 🚀 Como visualizar o projeto rodando

Você pode testar a aplicação viva e veloz através deste link oficial do Deploy:
👉 **[Acesse o cardápio em Produção](https://seuchicobotequim-cardapio.vercel.app/)**

### 💻 Como executar o código-fonte localmente

Caso queira inspecionar a arquitetura no seu ambiente local, rodar o app não toma mais de dois minutos:

**Pré-requisitos**: Um gerenciador de dependências rodando, por exemplo, o **Node.js**.

1. Clone esse repositório:

```bash
git clone {INSIRA_A_Sua_URL_do_Git}
```

2. Acesse a pasta base:

```bash
cd cardapio-seuchico
```

3. Resolva e instale as dependências:

```bash
npm install
```

4. Suba o servidor Next de desenvolvimento:

```bash
npm run dev
```

5. O aplicativo inicializará na rota padrão. Acesse: `http://localhost:3000`

---

> Projeto construído não apenas para providenciar o Menu Digital, mas para demonstrar código limpo, boas práticas, performance, acessibilidade e engenharia moderna de Frontend.
