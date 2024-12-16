# Aplicativo Seguro para Mulheres

Este é um aplicativo web projetado para fornecer um espaço seguro para mulheres, oferecendo ajuda confidencial e informa��ões confiáveis.

## Estrutura do Projeto

## Funcionalidades

- **Denúncia Confidencial**: Permite relatar casos de violência de forma anônima e segura.
- **Saúde Sexual e Reprodutiva**: Fornece informações confiáveis para cuidar da saúde.
- **Conexão com Entidades**: Facilita o contato com organizações de apoio.

## Como Usar

1. Clone o repositório:

## Funcionalidades

- **Denúncia Confidencial**: Permite relatar casos de violência de forma anônima e segura.
- **Saúde Sexual e Reprodutiva**: Fornece informações confiáveis para cuidar da saúde.
- **Conexão com Entidades**: Facilita o contato com organizações de apoio.

## Como Usar

1. Clone o repositório:
    ```sh
    git clone https://github.com/beneditotulio/WomenSafety.git
    ```
2. Abra o arquivo `index.html` em um navegador web.

## Estrutura do Código

- `index.html`: Contém a estrutura HTML e o estilo CSS embutido para a página principal do aplicativo.
- `New Text Document.txt`: (Descreva o propósito deste arquivo, se necessário)

### Excertos Relevantes

#### Cabeçalho e Navegação

```html
<header class="header">
    <h1>Bem-vinda ao Seu Espaço Seguro</h1>
    <p>Ajuda confidencial e informações confiáveis ao seu alcance.</p>
</header>

<nav>
    <a href="#denuncias">Denúncia</a>
    <a href="#saude">Saúde</a>
    <a href="#apoio">Apoio</a>
</nav>

<section class="feature" id="denuncias">
    <h2>Denúncia Confidencial</h2>
    <p>Relate casos de violência de forma anônima e segura.</p>
    <button onclick="showDenunciaForm()">Denunciar Agora</button>
    <div id="denuncia-form" class="hidden">
        <textarea placeholder="Descreva o caso..." rows="5" style="width: 100%;"></textarea>
        <button onclick="submitDenuncia()">Enviar</button>
    </div>
</section>

<section class="feature" id="denuncias">
    <h2>Denúncia Confidencial</h2>
    <p>Relate casos de violência de forma anônima e segura.</p>
    <button onclick="showDenunciaForm()">Denunciar Agora</button>
    <div id="denuncia-form" class="hidden">
        <textarea placeholder="Descreva o caso..." rows="5" style="width: 100%;"></textarea>
        <button onclick="submitDenuncia()">Enviar</button>
    </div>
</section>

<section class="feature" id="saude">
    <h2>Saúde Sexual e Reprodutiva</h2>
    <p>Informações confiáveis para cuidar de sua saúde.</p>
    <button onclick="showInfoSaude()">Saber Mais</button>
    <div id="info-saude" class="hidden">
        <p>Aqui você encontra conteúdos educativos e dicas sobre saúde sexual e reprodutiva.</p>
    </div>
</section>

<section class="feature" id="apoio">
    <h2>Conexão com Entidades</h2>
    <p>Entre em contato com organizações de apoio.</p>
    <button onclick="showContato()">Conectar</button>
    <div id="contato-entidades" class="hidden">
        <p>Contate entidades confiáveis através do número <strong>123-456-789</strong> ou e-mail <strong>apoio@seguro.com</strong>.</p>
    </div>
</section>

function showDenunciaForm() {
    document.getElementById('denuncia-form').classList.toggle('hidden');
}

function submitDenuncia() {
    alert('Denúncia enviada com sucesso!');
    document.getElementById('denuncia-form').classList.add('hidden');
}

function showInfoSaude() {
    document.getElementById('info-saude').classList.toggle('hidden');
}

function showContato() {
    document.getElementById('contato-entidades').classList.toggle('hidden');
}