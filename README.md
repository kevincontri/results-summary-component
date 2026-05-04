# Results Summary Component — Frontend Mentor Challenge

Solução para o desafio [Results Summary Component](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV) do Frontend Mentor. O objetivo foi construir um componente fiel ao design proposto, com foco em boas práticas de HTML semântico e CSS moderno.

---

## Visão Geral

### Desktop

<img width="1141" height="645" alt="image" src="https://github.com/user-attachments/assets/ff051970-0864-46a5-b444-cf955aaabb5d" />

### Mobile

<img width="398" height="783" alt="image" src="https://github.com/user-attachments/assets/afc992bc-1544-4863-96e0-b684a5ac442f" />

### Demo ao vivo

[Acesse o projeto no GitHub Pages](https://kevincontri.github.io/results-summary-component)

---

## Sobre o projeto

O componente exibe o resultado de um teste de habilidades cognitivas, dividido em duas seções:

- **Result** — painel esquerdo com gradiente, mostrando a pontuação geral do usuário em círculo destacado, classificação e percentual comparativo.
- **Summary** — painel direito listando as quatro categorias avaliadas (Reaction, Memory, Verbal e Visual), cada uma com cor e ícone próprios, além do botão de continuar.

---

## Tecnologias utilizadas

- HTML5 semântico
- CSS3
  - Custom Properties (variáveis CSS)
  - Flexbox
  - Media Queries
  - Transitions & efeitos de hover
  - Gradientes lineares
- Google Fonts — [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk)

---

## Funcionalidades

- Layout responsivo: exibição em coluna no mobile e em linha no desktop
- Efeito de hover nos cards de categoria com `translate3d` e `box-shadow` colorida por categoria
- Botão "Continue" com transição de cor via gradiente ao passar o mouse
- Paleta de cores centralizada em variáveis CSS para fácil manutenção

---

## Estrutura do projeto

```
results-summary/
├── assets/
│   ├── favicon-32x32.png
│   ├── icon-reaction.svg
│   ├── icon-memory.svg
│   ├── icon-verbal.svg
│   └── icon-visual.svg
├── index.html
├── style.css
```

---

## O que aprendi

- Uso de **CSS Custom Properties** para centralizar toda a paleta de cores e facilitar manutenção
- Aplicação de **Media Queries** para adaptar o layout de duas colunas (desktop) para uma coluna (mobile)
- Combinadores de seletores CSS (`img + p`, `p + p`) para estilizar elementos adjacentes sem adicionar classes extras
- Criação de efeitos de hover com `transform: translate3d` para movimentação e `box-shadow` colorida por categoria

---

## Autor

- GitHub — [@kevincontri](https://github.com/kevincontri)
- Frontend Mentor — [@kevincontri](https://www.frontendmentor.io/profile/kevincontri)
