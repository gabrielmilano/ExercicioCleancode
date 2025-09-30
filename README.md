# 🔢 Primitive Obsession - Code Smell

> Material educacional interativo sobre o Code Smell "Primitive Obsession" desenvolvido para a disciplina de Clean Code

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Sobre o Projeto

Este projeto apresenta de forma clara e interativa o conceito de **Primitive Obsession**, um dos Code Smells mais comuns em desenvolvimento de software. O material foi desenvolvido como atividade acadêmica e inclui explicações teóricas, exemplos práticos e um quiz interativo.

## 👥 Equipe

- **[Seu Nome]** - [Seu RA]
- **[Nome Colega 2]** - [RA]
- **[Nome Colega 3]** - [RA]

> ⚠️ **Importante:** Edite os nomes e RAs no arquivo `index.html` (linhas 164-168)

## 🎯 O que é Primitive Obsession?

**Primitive Obsession** ocorre quando usamos tipos primitivos (int, string, float, boolean) para representar conceitos complexos do domínio, ao invés de criar classes ou objetos específicos. Este code smell resulta em:

- ❌ Validações duplicadas
- ❌ Falta de encapsulamento
- ❌ Código difícil de manter
- ❌ Perda de semântica
- ❌ Propensão a erros

## ✨ Funcionalidades

### 📚 Conteúdo Educacional
- Definição clara e objetiva do Code Smell
- Lista completa de consequências
- Exemplos de código lado a lado (antes e depois da refatoração)
- Syntax highlighting para melhor legibilidade

### 🎮 Quiz Interativo
- 3 perguntas sobre Primitive Obsession
- Feedback visual imediato
- Sistema de pontuação
- Respostas corretas destacadas automaticamente

### 🎨 Design Responsivo
- Layout moderno com gradientes
- Compatível com desktop e mobile
- Animações suaves
- Interface intuitiva

## 🚀 Como Executar

### Opção 1: Live Server (VS Code)

1. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. Abra o arquivo `index.html` no VS Code
3. Clique com botão direito e selecione **"Open with Live Server"**
4. O projeto abrirá automaticamente no navegador

### Opção 2: Python HTTP Server

```bash
# No diretório do projeto, execute:
python -m http.server 8000

# Ou, se estiver usando Python 2:
python -m SimpleHTTPServer 8000
```

Depois acesse: `http://localhost:8000`

### Opção 3: Diretamente no Navegador

Simplesmente abra o arquivo `index.html` no seu navegador favorito (Chrome, Firefox, Edge, Safari)

## 📁 Estrutura do Projeto

```
primitive-obsession/
│
├── index.html          # Página principal (HTML + CSS + JS inline)
└── README.md          # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e animações
  - Flexbox e Grid Layout
  - Gradientes e animações CSS
  - Media Queries para responsividade
- **JavaScript Vanilla** - Interatividade do quiz
  - Manipulação do DOM
  - Event Listeners
  - Lógica de pontuação

## 📖 Conteúdo Incluído

### 1. Título e Identificação ✅
- Nome do Code Smell
- Identificação da equipe

### 2. Definição do Code Smell ✅
- Explicação clara em 2-3 frases
- Contexto de quando ocorre

### 3. Consequências ✅
- 6 principais problemas listados
- Formato visual com ícones

### 4. Exemplos de Código ✅
- **Código Ruim**: Usando tipos primitivos
- **Código Refatorado**: Usando Value Objects
- Comparação lado a lado
- Syntax highlighting

### 5. Material Criativo ✅
- **Quiz Interativo** com:
  - 3 perguntas sobre o tema
  - Sistema de seleção de respostas
  - Verificação automática
  - Feedback visual (cores)
  - Mensagens personalizadas por desempenho

## 🎨 Personalização

### Cores
As cores principais podem ser alteradas nas variáveis CSS:

```css
/* Gradiente principal */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Gradiente do header */
background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);

/* Gradiente do quiz */
background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
```

### Equipe
Edite a seção de equipe no arquivo `index.html`:

```html
<div class="team">
    <h3>👥 Equipe</h3>
    <p>[Seu Nome] - [Seu RA]</p>
    <p>[Nome Colega 2] - [RA]</p>
    <p>[Nome Colega 3] - [RA]</p>
</div>
```

## 📱 Compatibilidade

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 🎯 Critérios de Avaliação Atendidos

- ✅ **Clareza e objetividade** - Explicação direta e exemplos claros
- ✅ **Criatividade** - Quiz interativo com feedback visual
- ✅ **Organização** - Estrutura bem definida e navegável
- ✅ **Funcionamento** - Sem erros, totalmente funcional

## 📚 Referências

- [Refactoring Guru - Primitive Obsession](https://refactoring.guru/smells/primitive-obsession)
- [Martin Fowler - Refactoring](https://martinfowler.com/books/refactoring.html)
- [Clean Code - Robert C. Martin](https://www.amazon.com.br/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais como parte da disciplina de Clean Code.

## 🤝 Como Contribuir

Se você é colega de turma e quer sugerir melhorias:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 💡 Dicas de Apresentação

1. **Demonstre o Quiz** - Mostre a interatividade
2. **Compare os códigos** - Explique lado a lado
3. **Destaque as consequências** - Use exemplos reais
4. **Mostre o responsivo** - Teste em diferentes tamanhos de tela

## 📞 Contato

Para dúvidas sobre o projeto, entre em contato com a equipe através dos emails institucionais.

---

⭐ **Desenvolvido com dedicação para Clean Code** ⭐

**Data de Entrega:** [Adicione a data]  
**Disciplina:** Clean Code  
**Professor(a):** [Nome do Professor]
