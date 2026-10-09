# Via Flora Aromaterapia

Landing page estática, pronta para upload ao GitHub.

## Arquivos

- `index.html`: página completa com CSS e JavaScript embutidos.
- `assets/`: logo, cinco fotos e seis prints reais das avaliações.
- `.nojekyll`: permite servir os arquivos diretamente em hospedagem estática.

Mantenha esta estrutura ao subir os arquivos. Não há dependências, instalação ou etapa de build.

## Configuração

No início do script de `index.html`, substitua `COLE_AQUI_O_ID_DO_PIXEL` pelo ID numérico do Pixel da Meta.
O link do grupo do WhatsApp já está preenchido em `LINK_DO_GRUPO`.

O Pixel configurado envia `PageView` ao carregar e `Lead` nos cliques dos três botões do grupo.
`Lead` representa o clique no convite, sem confirmação de entrada no grupo.

## Conteúdo e interação

A foto principal horizontal está incluída. O botão aparece antes dela.
Os seis prints originais aparecem no HTML mesmo sem JavaScript, sem link externo para o Google.
O carrossel permite deslizar. Em navegador com JavaScript, há setas e ampliação dentro da página.
A logo usa os pixels originais, com transparência aplicada por SVG.
O movimento do fundo é leve e respeita a preferência por movimento reduzido.

## Conferência

Arquivos e referências conferidos; JavaScript validado.
Após publicar, confira no celular e teste os eventos com seu Pixel configurado.
