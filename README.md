# Calculator

Calculadora web com visual neon/glow, construída em **HTML, CSS e JavaScript puro** — operações básicas de aritmética com suporte a números decimais e expressões encadeadas.

🔗 **Demo:** [erickkadr.github.io/Calculator/calc.html](https://erickkadr.github.io/Calculator/calc.html)

<div align="center">
  <img width="100%" src="https://user-images.githubusercontent.com/99443921/214458205-8be4d3f0-d3ec-4606-a5ce-2c219ab7c991.gif"/>
</div>

## Sobre o projeto

Calculadora clássica de aritmética, com teclado numérico, operações (`+ - × ÷`), apagar (backspace), limpar (`AC`) e igual. O visual usa um tema escuro com glow azul/roxo ao redor do painel e dos botões.

## Motivação

Projeto de estudo para praticar **manipulação de DOM e eventos em JavaScript puro** — sem framework, sem biblioteca de cálculo — construindo a lógica de entrada/expressão do zero e testando a leitura da expressão digitada como uma string avaliável.

## Funcionalidades

- Quatro operações básicas: soma, subtração, multiplicação e divisão
- Suporte a números decimais e expressões com múltiplas operações
- Botão de apagar (backspace) que remove o último caractere digitado
- Botão `AC` para limpar tudo
- Interface com ícones (Font Awesome) e efeito neon/glow

## Tecnologias

- **HTML5**
- **CSS3** (glow/box-shadow, layout em grade)
- **JavaScript** (manipulação de DOM, eventos de clique)
- **Font Awesome** (ícones dos botões)

## Como rodar localmente

Sem build, sem dependência — abra `calc.html` no navegador ou sirva a pasta:

```bash
npx serve .
# depois acesse /calc.html
```

> Nota: o arquivo de entrada é `calc.html` (não `index.html`).

---

### Made with ♥ by Erick Dantas | [Contato](https://www.linkedin.com/in/erickkadr/)
