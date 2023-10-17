# Formatações em HTML

Sobre estruturações, formatações de texto, acessibilidade e etc...

## Tags de formatação de textos
- i: texto em itálico;
- b: texto em negrito;
- strong: ênfase no texto;
- u: texto sublinhado;
- mark: marca-texto;
- sup: texto acima;
- sub: texto abaixo;
- blockquote: citação;
- font: formatação de letra (geralemente indica utilizar o CSS nessa parte, ok?)
    - color: mudar cor da fonte;
    - face: fonte a ser utilizada.

## Tags Div e Span
Elas são indispensáveis para a estruturação e divisão de setores nos sites.

```
<div id="menu">
    <div class="home">Página inicial</div>
    <div class="search">Pesquisar</div>
    <div class="chat">Conversas</div>
    <div class="profile">Perfil</div>
</div>
```
As div são "display-block", ou seja, ocupam todo o espaço lateral da página.

```
<p>exemplo <span>de</span> tag</p>
```
A tag span não ocupa todo o espaço como a div.

## Fieldset
Tag para estruturação, muito utilizada para deixar as divisões, principalmente em formulários, mais estilizadas.
```
<fieldset>
    <legend>Dados pessoais</legend>
    <div class="row">
        <label>Nome:</label><input type="text">
        <label>E-mail:</label><input type="email">
    </div>
</fieldset>
<fieldset>
    <legend>Dados Adicionais</legend>
    <div class="row">
        <label>Idade:</label><input type="number" min="0">
        <label>Telefone:</label><input type="number">
    </div>
</fieldset>
```

## Iframes
A "mesma coisa" que o antigo embed, permite que uma janela seja criada onde conteúdos de terceiros sejam inseridos.
```
<iframe src="https://web.dio.me/home">
```
