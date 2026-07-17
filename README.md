# Magic Mug — Site de Canecas Personalizadas

Identidade **pop art / orgulho nordestino**, alinhada ao Instagram [@magicmug20](https://www.instagram.com/magicmug20/):
cores vibrantes, contornos grossos estilo HQ, humor e brasilidade.

## Arquivos
- `index.html`: página completa e responsiva.
- `logo.jpg`: logo oficial (usada no selo do cabeçalho e do rodapé).
- `img/`: artes reais das canecas usadas na galeria.
- `ScrennShots/`: originais baixados do Instagram (backup — não usados diretamente pelo site).

## Imagens da galeria
A seção **Galeria** (`#galeria`) usa estes arquivos em `img/`:
`cangaceiro.png`, `oxente.png`, `dia-do-nordestino.png`, `andar-com-fe.png`,
`deus-me-proteja.png` e `galeria-1.jpg`.

Para trocar ou adicionar uma arte: salve o arquivo em `img/` e ajuste o `src`
correspondente no HTML (seção `#galeria`). Formato retrato (~3:4) cai melhor,
pois os quadros são verticais. Se um arquivo faltar, aparece um placeholder
colorido no lugar (o site não quebra).

## Trocar a logo
A logo fica em `logo.jpg` (imagem quadrada). No cabeçalho e no rodapé ela aparece
recortada dentro de um selo redondo. Se trocar a logo e o recorte sair torto,
ajuste no CSS a regra `.brand-badge` (`background-size` e `background-position`).

## Configurar o WhatsApp
No final do arquivo `index.html`, procure:

```javascript
const whatsappNumber = "";
```

Adicione o número oficial com DDI e DDD, somente números:

```javascript
const whatsappNumber = "5575999999999";
```

## Antes de publicar
- Configurar o número do WhatsApp.
- Confirmar cidade e formas de entrega.
- Adicionar preços somente caso a empresa trabalhe com tabela fixa.
- Confirmar prazo de produção, opções de canecas e capacidade.
- (Opcional) Trocar a arte Tom & Jerry (`img/galeria-1.jpg`) por uma versão em
  resolução cheia — a atual é uma miniatura.

## Hospedagem
Pode ser publicado no Netlify, Vercel, GitHub Pages ou em uma hospedagem comum.
