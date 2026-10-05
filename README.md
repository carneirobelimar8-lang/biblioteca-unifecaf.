# Biblioteca Digital UniFECAF

Projeto acadêmico de Design Web de **Luiza Kelly dos Santos**.

Interface desenvolvida com HTML e CSS separados, sem JavaScript, frameworks,
construtores de sites ou templates prontos. Segue a sequência do protótipo:
cabeçalho, banner principal, biblioteca, quatro destaques, segundo banner,
seis materiais, três blocos de unidades, contatos e rodapé.

Site: https://biblioteca-unifecaf-luiza-kelly.carneirobelimar8.chatgpt.site

## Abrir o projeto

Na versão de entrega, abra `index.html` em um navegador. Mantenha as pastas
`css` e `assets` ao lado dele. Não é necessário instalar programas ou executar
um servidor para visualizar a interface.

## Organização da versão de entrega

* `index.html`: conteúdo, estrutura semântica, navegação e filtros nativos.
* `css/style.css`: identidade visual, layouts, filtros e responsividade.
* `assets/imagens/`: 13 arquivos SVG locais, incluindo capas ilustrativas.
* `README.md`: explicações e orientações de execução.

No repositório usado para hospedagem, os três primeiros itens estão dentro de
`dist/`. O ZIP de entrega coloca-os na raiz de `biblioteca-unifecaf/`, como
solicitado no enunciado.

## Funcionamento

* As quatro opções do menu levam às seções da mesma página.
* Os filtros usam cinco controles `input type="radio"`, associados a `label`.
* O seletor CSS `:checked` determina a categoria exibida.
* `Saiba mais` encaminha à fonte externa de cada material.
* Telefone e e-mail usam links `tel:` e `mailto:`.
* A consulta institucional é encaminhada ao portal oficial da biblioteca.

Os materiais exibidos são uma seleção demonstrativa de fontes abertas
externas; não representam a relação oficial do acervo UniFECAF. As capas e
ilustrações são desenhos vetoriais feitos para esta interface, não capas
editoriais ou fotografias dos espaços reais.

## Responsividade

* Acima de 960 pixels: três colunas no catálogo e quatro nos destaques.
* De 641 a 960 pixels: duas colunas no catálogo e nos destaques.
* Até 640 pixels: catálogo e blocos principais em uma coluna.
* O menu permanece visível e pode se reorganizar em telas estreitas.
* `max-width: 100%`, `height: auto` e o `viewBox` dos SVGs preservam imagens.

## Acessibilidade aplicada

Idioma `pt-BR`, um título principal, hierarquia de títulos, elementos
semânticos, nomes de links específicos para leitores de tela, textos
alternativos, link para pular o menu, foco visível, controles nativos e
respeito a `prefers-reduced-motion`. Isso não substitui uma auditoria completa
com tecnologias assistivas.

## Entender antes de apresentar

Leia os comentários numerados do CSS e os comentários de cada seção do HTML.
Localize o `link` que carrega o CSS, os `href` que apontam para IDs da página,
as regras de `.books-grid`, os filtros `:checked` e os dois blocos `@media`.
Experimente alterar uma cor de `:root` e uma quantidade de colunas. Reverta
as alterações se não quiser mantê-las. O enunciado exige compreensão do
código e uma demonstração pessoal do projeto no vídeo.

## Referências técnicas e institucionais

* https://www.unifecaf.com.br/biblioteca
* https://www.unifecaf.com.br/polos
* https://www.unifecaf.com.br/graduacao-presencial
* https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements
* https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/CSS_layout/Responsive_Design
* https://www.w3.org/Translations/WCAG22-pt-BR/

Data de consulta das referências: 5 de outubro de 2026.

## Demonstração para o vídeo

Abra `apresentacao.html` para visualizar o site real em quadros de 320, 390 e 768 pixels. Esta página auxiliar usa apenas HTML e CSS e permite demonstrar a responsividade sem instalar ferramentas. Em um smartphone real, use `index.html` diretamente.
