# Card Profile

Um componente de cartão de perfil simples e responsivo em HTML/CSS/JS pronto para uso e personalização.

Este repositório contém um exemplo (index.html) que demonstra um cartão de perfil com foto, nome, cargo, descrição e links de contato.

## Conteúdo do repositório

- `index.html` — Demonstração do cartão de perfil.
- `img/` — Pasta para imagens usadas no exemplo (avatar, ícones, etc.).
- `.vscode/` — Configurações do editor (não essenciais para uso).

## Visualização

Para ver o componente localmente:

1. Clone o repositório:

   git clone https://github.com/wallisson-tech/Card_Profile.git

2. Abra o arquivo `index.html` no navegador (duplo clique ou arraste para a janela do navegador).

Opcional: publicar no GitHub Pages selecionando a branch `main` nas configurações do repositório.

## Uso

O cartão está implementado em `index.html`. Você pode copiar o trecho HTML/CSS para integrar em seu projeto ou modificar diretamente o arquivo.

Exemplo básico (extraído do `index.html`):

```html
<!-- Estrutura do cartão -->
<div class="card">
  <img src="img/avatar.png" alt="Avatar" class="avatar">
  <h2>Nome Sobrenome</h2>
  <p class="role">Cargo / Profissão</p>
  <p class="bio">Breve descrição sobre a pessoa. Interesses, habilidades ou mensagem curta.</p>
  <div class="links">
    <a href="#">Twitter</a>
    <a href="#">LinkedIn</a>
  </div>
</div>
```

Substitua `img/avatar.png`, o nome, cargo e descrição conforme necessário.

## Customização

- Cores e tipografia: altere as regras CSS no próprio `index.html` (ou mova para um arquivo `.css` separado).
- Layout: o cartão é responsivo; ajuste `max-width`, `padding` e `flex` conforme seu design.
- Conteúdo dinâmico: incorpore os dados via JavaScript se quiser popular o cartão de forma programática.

## Contribuições

Pull requests são bem-vindas. Para contribuir:

1. Fork deste repositório.
2. Crie uma branch com sua feature: `git checkout -b feature/nome-da-feature`.
3. Faça commits claros e envie a branch: `git push origin feature/nome-da-feature`.
4. Abra um Pull Request descrevendo as alterações.

## Licença

Adicione uma licença apropriada (ex.: MIT) criando um arquivo `LICENSE` no repositório.

## Contato

Se quiser ajuda para adaptar o cartão ao seu projeto, abra uma issue ou entre em contato via perfil do GitHub.
