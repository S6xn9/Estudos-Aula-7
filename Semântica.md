
# 🧠 Anotações de Estudo: Semântica da HTML5

## 📌 Assunto: Semântica da HTML5

---

## 1. O que é Semântica em HTML?
Em HTML, semântica refere-se ao significado dos elementos e do conteúdo que eles contêm.  
Usar HTML de forma semântica significa escolher as tags que melhor descrevem o propósito e o tipo de informação, não só para estilizar.

**Contraste com tags não semânticas:**
- **Não semânticas** (`<div>`, `<span>`): genéricas, servem como contêineres para CSS/JS, sem significado próprio.
- **Semânticas** (`<header>`, `<nav>`, `<article>`, etc.): descrevem o tipo de conteúdo e fornecem significado estrutural.

---

## 2. Por que a semântica é importante?
- **Acessibilidade**:  
  Leitores de tela usam a estrutura semântica para navegar logicamente.  
  _Exemplo:_ um leitor de tela anuncia "Navegação Principal" ao encontrar `<nav>`.

- **SEO**:  
  Motores de busca entendem melhor o contexto e relevância do conteúdo.  
  Elementos semânticos ajudam crawlers a identificar seções importantes.

- **Manutenibilidade**:  
  Código mais legível e compreensível para desenvolvedores.  
  Facilita colaboração e futuras manutenções.

- **Compatibilidade**:  
  Segue os padrões web e garante renderização consistente entre navegadores.

---

## 3. Principais elementos semânticos da HTML5

### `<header>`
Representa o conteúdo introdutório de uma seção ou da página.
```html
<header>
  <h1>Meu Blog</h1>
  <nav>...</nav>
</header>
```

### `<nav>`
Seção de links de navegação principais.
```html
<nav>
  <ul>
    <li><a href="/">Home</a></li>
    <li><a href="/sobre">Sobre</a></li>
  </ul>
</nav>
```

### `<main>`
Conteúdo principal do documento. Deve haver apenas um `<main>` por página.
```html
<main>
  <article>...</article>
</main>
```

### `<article>`
Conteúdo independente e autocontido (post, notícia, comentário).
```html
<article>
  <h2>Título do Post</h2>
  <p>Conteúdo do post...</p>
</article>
```

### `<section>`
Seções temáticas de conteúdo, geralmente com cabeçalho.
```html
<section>
  <h2>Seção de Destaques</h2>
  <p>Texto...</p>
</section>
```

### `<aside>`
Conteúdo tangencial relacionado ao principal (barra lateral, links extras).
```html
<aside>
  <h3>Links Relacionados</h3>
  <ul>...</ul>
</aside>
```

### `<footer>`
Rodapé de uma seção ou da página.
```html
<footer>
  <p>&copy; 2025 Meu Blog</p>
</footer>
```

---

## 4. Semântica para textos e multimídia

### `<figure>` e `<figcaption>`
Agrupa mídia e legenda.
```html
<figure>
  <img src="arvore.jpg" alt="Árvore verde">
  <figcaption>Uma bela árvore no parque.</figcaption>
</figure>
```

### `<time>`
Representa datas e horários de forma interpretável.
```html
<p>Publicado em <time datetime="2025-07-18">18 de Julho de 2025</time>.</p>
```

---

## 5. Dicas finais
- Planeje a **estrutura** antes de pensar no visual.
- Use **CSS** para estilo, não para marcar significado.
- Valide seu HTML com ferramentas como o **W3C Validator**.
- `<div>` e `<span>` ainda valem para fins de estilização e scripts.

---

## 🚀 Conclusão
Dominar a semântica da HTML5 é essencial para criar páginas **acessíveis**, bem **estruturadas** e **otimizadas** para buscadores.
