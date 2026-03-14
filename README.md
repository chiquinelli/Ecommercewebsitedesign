# Fast Rodas - E-commerce de Rodas Automotivas

![Fast Rodas Logo](./docs/screenshots/logo.png)
<!-- Adicione uma captura do logo/header aqui -->

## 📋 Sobre o Projeto

Fast Rodas é uma plataforma moderna de e-commerce especializada na venda de rodas automotivas de alta performance. O projeto oferece uma experiência de compra premium com design arrojado inspirado em marcas automotivas, utilizando cores escuras (preto/cinza) com detalhes em vermelho para transmitir velocidade e performance.

### 🎯 Objetivo

Criar uma plataforma de alta conversão focada na venda de rodas automotivas online, com layout moderno, navegação intuitiva e forte apelo visual.

---

## 🖼️ Screenshots

### Página Inicial (Homepage)

![Homepage - Hero Section](./docs/screenshots/home-hero.png)
<!-- Capture: Seção hero com banner "Performance Wheels for Your Car" -->

**Seção Hero:**
- Banner impactante com imagem de rodas de alta performance
- Título destacado: "Performance Wheels for Your Car"
- Call-to-action "Shop Now"
- Gradiente escuro sobre a imagem

![Homepage - Categories](./docs/screenshots/home-categories.png)
<!-- Capture: Seção de categorias (Sport, SUV, Truck Wheels) -->

**Categorias em Destaque:**
- Sport Wheels
- SUV Wheels
- Truck Wheels

![Homepage - Featured Products](./docs/screenshots/home-products.png)
<!-- Capture: Grid de produtos em destaque -->

**Produtos em Destaque:**
- Grid responsivo com 4 produtos
- Cards com imagem, preço, avaliação e botão de adicionar ao carrinho

![Homepage - Benefits](./docs/screenshots/home-benefits.png)
<!-- Capture: Seção de benefícios -->

**Benefícios:**
- Entrega Rápida
- Pagamento Seguro
- Garantia de Qualidade

![Homepage - Instagram](./docs/screenshots/home-instagram.png)
<!-- Capture: Seção de preview do Instagram -->

**Preview do Instagram:**
- Grid 2x4 com imagens
- Link para @fastrodas

---

### Página de Produtos (Products Listing)

![Products - Desktop](./docs/screenshots/products-desktop.png)
<!-- Capture: Página de produtos completa no desktop -->

**Visão Geral:**
- Filtros laterais à esquerda
- Grid de produtos à direita
- Barra de ordenação

![Products - Filters](./docs/screenshots/products-filters.png)
<!-- Capture: Sidebar de filtros em detalhe -->

**Filtros Disponíveis:**
- Categoria (Sport, SUV, Truck)
- Marca (Racing Pro, Elite Motors, etc.)
- Tamanho da Roda (17", 18", 19", 20", 21", 22")
- Faixa de Preço (slider de $0 a $2000)
- Botão "Reset Filters"

![Products - Mobile Filters](./docs/screenshots/products-mobile.png)
<!-- Capture: Filtros mobile (slide-out panel) -->

**Versão Mobile:**
- Menu de filtros em slide-out panel
- Grid responsivo de produtos
- Botão de filtros flutuante

---

### Página de Detalhes do Produto

![Product Detail - Top](./docs/screenshots/product-detail-top.png)
<!-- Capture: Parte superior da página de produto -->

**Seção Principal:**
- Galeria de imagens com thumbnails
- Informações do produto
- Avaliações com estrelas
- Preço destacado (com preço antigo riscado se houver desconto)

![Product Detail - Selectors](./docs/screenshots/product-selectors.png)
<!-- Capture: Seletores de tamanho e cor -->

**Seletores:**
- Seleção de Tamanho da Roda
- Seleção de Cor
- Quantidade (com botões +/-)
- Botão "Add to Cart"
- Botão "Buy via WhatsApp"

![Product Detail - Specs](./docs/screenshots/product-specs.png)
<!-- Capture: Tabela de especificações técnicas -->

**Especificações Técnicas:**
- Material
- Peso
- Largura (Width)
- PCD (Padrão de Furação)
- Offset
- Acabamento (Finish)

![Product Detail - Related](./docs/screenshots/product-related.png)
<!-- Capture: Produtos relacionados -->

**Produtos Relacionados:**
- Grid com 4 produtos da mesma categoria
- Facilita cross-selling

---

### Header e Footer

![Header - Desktop](./docs/screenshots/header-desktop.png)
<!-- Capture: Header fixo no desktop -->

**Header (Sticky):**
- Logo "FAST RODAS" (branco e vermelho)
- Menu de navegação
- Barra de busca
- Ícone do carrinho com contador
- Responsivo com menu hamburger no mobile

![Header - Mobile Menu](./docs/screenshots/header-mobile.png)
<!-- Capture: Menu mobile expandido -->

**Menu Mobile:**
- Menu expansível
- Links de navegação
- Barra de busca

![Footer](./docs/screenshots/footer.png)
<!-- Capture: Footer completo -->

**Footer:**
- Informações da marca
- Links rápidos
- Atendimento ao cliente
- Contato (telefone, email, endereço)
- Redes sociais
- Botão do WhatsApp
- Copyright

---

## 🚀 Funcionalidades

### ✅ Implementadas

#### Homepage
- [x] Hero section com banner de alta qualidade
- [x] Call-to-action "Shop Now"
- [x] Categorias em destaque (Sport, SUV, Truck)
- [x] Grid de produtos em destaque
- [x] Banner promocional (20% OFF)
- [x] Seção de benefícios (ícones + descrições)
- [x] Preview do Instagram
- [x] Design totalmente responsivo

#### Página de Produtos
- [x] Listagem completa de produtos
- [x] Filtros por categoria
- [x] Filtros por marca
- [x] Filtros por tamanho
- [x] Filtro por faixa de preço (slider)
- [x] Ordenação (Popular, Preço, Mais Recentes)
- [x] Grid responsivo (1-2-3 colunas)
- [x] Contador de produtos
- [x] Reset de filtros
- [x] Filtros mobile (slide-out panel)

#### Página de Produto
- [x] Galeria de imagens com thumbnails
- [x] Navegação entre imagens
- [x] Informações detalhadas do produto
- [x] Sistema de avaliações com estrelas
- [x] Seletor de tamanho
- [x] Seletor de cor
- [x] Seletor de quantidade
- [x] Botão "Adicionar ao Carrinho"
- [x] Botão "Comprar via WhatsApp" (com mensagem pré-formatada)
- [x] Tabela de especificações técnicas
- [x] Produtos relacionados
- [x] Breadcrumb de navegação
- [x] Badge de desconto

#### Componentes Globais
- [x] Header sticky com navegação
- [x] Logo animado
- [x] Menu responsivo
- [x] Barra de busca
- [x] Carrinho de compras (ícone com contador)
- [x] Footer completo com links e informações
- [x] Botão WhatsApp flutuante no footer

---

## 🎨 Design System

### Paleta de Cores

```css
--background: #0a0a0a        /* Preto profundo */
--card: #1a1a1a              /* Cinza escuro */
--secondary: #262626         /* Cinza médio */
--primary: #dc2626           /* Vermelho (accent) */
--foreground: #ffffff        /* Branco */
--muted-foreground: #a3a3a3  /* Cinza claro */
```

### Tipografia

- **Font Weight Medium:** 600 (títulos e destaques)
- **Font Weight Normal:** 400 (textos)
- **Títulos:** Negrito, uppercase quando apropriado
- **Accent Color:** Vermelho (#dc2626) para CTAs e destaques

### Componentes de UI

- **Buttons:** Bordas arredondadas (0.375rem), transições suaves
- **Cards:** Background #1a1a1a, border #262626, hover com borda vermelha
- **Inputs:** Background #1a1a1a, focus ring vermelho
- **Images:** Aspect ratio quadrado para produtos, hover com zoom

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- **React 18.3.1** - Biblioteca JavaScript para interfaces
- **TypeScript** - Tipagem estática
- **React Router 7.13.0** - Roteamento e navegação
- **Tailwind CSS 4.1.12** - Framework CSS utility-first
- **Vite 6.3.5** - Build tool e dev server

### Bibliotecas de UI
- **Lucide React** - Ícones modernos
- **Radix UI** - Componentes acessíveis
- **Motion** - Animações fluidas

### Ferramentas de Desenvolvimento
- **@vitejs/plugin-react** - Plugin Vite para React
- **@tailwindcss/vite** - Plugin Tailwind para Vite
- **PostCSS** - Processamento de CSS

---

## 📦 Estrutura do Projeto

```
fast-rodas/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── Header.tsx           # Cabeçalho sticky
│   │   │   ├── Footer.tsx           # Rodapé
│   │   │   ├── ProductCard.tsx      # Card de produto
│   │   │   └── ui/                  # Componentes de UI base
│   │   ├── data/
│   │   │   └── products.ts          # Dados mockados dos produtos
│   │   ├── pages/
│   │   │   ├── HomePage.tsx         # Página inicial
│   │   │   ├── ProductsPage.tsx     # Listagem de produtos
│   │   │   └── ProductPage.tsx      # Detalhes do produto
│   │   ├── App.tsx                  # Componente raiz
│   │   ├── Root.tsx                 # Layout principal
│   │   └── routes.ts                # Configuração de rotas
│   └── styles/
│       ├── theme.css                # Tema customizado (cores)
│       ├── tailwind.css             # Configuração Tailwind
│       └── fonts.css                # Importação de fontes
├── package.json
├── vite.config.ts
├── postcss.config.mjs
└── README.md
```

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Node.js 18+ instalado
- npm ou pnpm

### Instalação

1. **Clone o repositório:**
```bash
git clone <repository-url>
cd fast-rodas
```

2. **Instale as dependências:**
```bash
npm install
# ou
pnpm install
```

3. **Inicie o servidor de desenvolvimento:**
```bash
npm run dev
# ou
pnpm dev
```

4. **Acesse no navegador:**
```
http://localhost:5173
```

### Build para Produção

```bash
npm run build
# ou
pnpm build
```

Os arquivos otimizados serão gerados na pasta `dist/`.

---

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints:

- **Mobile:** < 768px
- **Tablet:** 768px - 1024px
- **Desktop:** > 1024px

### Adaptações Mobile:
- Menu hamburger no header
- Filtros em slide-out panel
- Grid de produtos 1 coluna
- Galeria de imagens stack vertical
- Footer com layout empilhado

---

## 🎯 Fluxo do Usuário

### Jornada de Compra

1. **Landing (Homepage)**
   - Usuário vê hero section com proposta de valor
   - Explora categorias destacadas
   - Visualiza produtos em destaque

2. **Descoberta (Products Page)**
   - Navega pelo catálogo completo
   - Aplica filtros (categoria, marca, tamanho, preço)
   - Ordena produtos por preferência

3. **Decisão (Product Page)**
   - Visualiza detalhes e especificações técnicas
   - Seleciona variações (tamanho, cor)
   - Adiciona ao carrinho OU compra via WhatsApp

4. **Conversão**
   - Finaliza compra pelo carrinho
   - OU inicia conversa no WhatsApp com dados pré-preenchidos

---

## 🔗 Integrações

### WhatsApp Business

Integração direta com WhatsApp para facilitar vendas:

```typescript
const whatsappMessage = `Hi! I'm interested in ${product.name} 
(${selectedSize}, ${selectedColor})`;
const whatsappLink = `https://wa.me/5511999999999?text=${encodeURIComponent(whatsappMessage)}`;
```

**Benefícios:**
- Atendimento humanizado
- Resposta rápida a dúvidas
- Conversão direta
- Redução de fricção no processo de compra

---

## 📊 Dados Mockados

O projeto utiliza dados mockados em `src/app/data/products.ts`:

- **10 produtos** com informações completas
- **3 categorias** (Sport, SUV, Truck)
- **Múltiplas marcas** (Racing Pro, Elite Motors, Chrome Master, etc.)
- **Variações de tamanho** (17" a 22")
- **Variações de cor** (Black, Silver, Chrome, Red, etc.)
- **Especificações técnicas** detalhadas
- **Múltiplas imagens** por produto

---

## 🎨 Guia de Estilo

### Princípios de Design

1. **Bold & Modern:** Tipografia forte, cores contrastantes
2. **Performance-Driven:** Visual inspirado em marcas automotivas
3. **High Conversion:** CTAs evidentes, processo simplificado
4. **Visual Hierarchy:** Informações importantes em destaque
5. **Speed:** Imagens otimizadas, transições suaves

### Elementos Visuais

- **Badges:** Indicam promoções (SALE)
- **Hover Effects:** Zoom em imagens, mudança de cor em botões
- **Transitions:** 300ms para interações suaves
- **Icons:** Lucide React para consistência
- **Gradients:** Overlays escuros sobre imagens

---

## 🌟 Destaques Técnicos

### Performance
- Lazy loading de imagens
- Otimização de bundle com Vite
- CSS utility-first (Tailwind) para reduzir CSS não utilizado

### Acessibilidade
- Componentes Radix UI (WAI-ARIA)
- Contraste adequado de cores
- Navegação por teclado
- Labels semânticos

### SEO Ready
- Estrutura HTML semântica
- Heading hierarchy correta
- Meta tags preparadas
- URLs amigáveis

### User Experience
- Loading states
- Feedback visual em interações
- Mensagens de erro claras
- Breadcrumbs para navegação

---

## 📝 Próximos Passos

### Melhorias Sugeridas

- [ ] Implementar carrinho de compras funcional
- [ ] Sistema de autenticação de usuários
- [ ] Wishlist / Lista de desejos
- [ ] Comparação de produtos
- [ ] Sistema de reviews e avaliações
- [ ] Integração com gateway de pagamento
- [ ] Painel administrativo
- [ ] Sistema de busca avançada
- [ ] Newsletter signup
- [ ] Live chat support
- [ ] Programa de fidelidade
- [ ] Calculadora de compatibilidade (veículo x roda)

### Integrações Futuras

- [ ] Backend API (Node.js/Express ou similar)
- [ ] Banco de dados (PostgreSQL/MongoDB)
- [ ] Sistema de gestão de inventário
- [ ] CRM integrado
- [ ] Analytics (Google Analytics, Hotjar)
- [ ] Email marketing (SendGrid, Mailchimp)
- [ ] Sistema de rastreamento de pedidos

---

## 👥 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

---

## 📄 Licença

Este projeto é um protótipo de demonstração.

---

## 📞 Contato

**Fast Rodas**
- Email: info@fastrodas.com
- Telefone: +1 (555) 123-4567
- WhatsApp: +55 11 99999-9999
- Instagram: [@fastrodas](https://instagram.com/fastrodas)

---

## 🙏 Agradecimentos

- Imagens via [Unsplash](https://unsplash.com)
- Ícones via [Lucide](https://lucide.dev)
- UI Components via [Radix UI](https://radix-ui.com)

---

**Desenvolvido com ⚡ e ❤️ para entusiastas automotivos**
