# Coluna Fluída | Site institucional

Onepage da Coluna Fluída (quiropraxia, ventosaterapia e Dry Needling em Barueri - SP).
Site estático em HTML, CSS e JavaScript puros, sem build e sem dependências.

## Estrutura

```
index.html        página inteira (CSS e JS embutidos)
favicon.svg
img/              fotos (provisórias, veja abaixo)
fonts/            Onest e Cormorant Garamond (latin), servidas localmente
mockup/           imagem de aprovação do layout (v1)
vercel.json       cache dos assets e URLs limpas
```

## Rodar localmente

Abra `index.html` no navegador, ou sirva a pasta:

```bash
npx serve .
```

## Publicar na Vercel

1. Suba a pasta para um repositório no GitHub.
2. Na Vercel: **Add New > Project**, escolha o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios.
4. Deploy. Depois aponte o domínio `colunafluida.com.br` em **Settings > Domains**.

## Interações

- Barra de progresso de leitura e cabeçalho que ganha fundo ao rolar.
- Blocos aparecem conforme a rolagem (progresso ligado ao scroll, vai e volta).
- Parallax suave nas fotos do hero, do bloco "Tudo na mesma consulta" e da faixa.
- A coluna vertebral do hero ondula e a bolinha amarela desce conforme a rolagem (desktop).
- Hover em botões, cards, avaliações, FAQ, menu e rodapé (só em dispositivos com mouse).
- Com `prefers-reduced-motion` ativo, tudo aparece parado.

## Pendências antes de ir ao ar

- [ ] Trocar as fotos de `img/` por fotos reais da Ellen e do espaço (as atuais são de banco de imagens e servem só de marcador; a do hero e a da seção "Quem cuida de você" não são ela).
- [ ] Colocar o logo real no lugar do símbolo provisório (cabeçalho e `favicon.svg`).
- [ ] Confirmar o horário: o site atual diz seg a sáb 8h30 às 20h, o Google Maps mostra fechamento às 20h30.
- [ ] Confirmar o registro ABQ nº 1284.
- [ ] Revisar o link do botão "Ver todas no Google" com o link oficial do perfil.
- [ ] Adicionar `og:image` com URL absoluta do domínio final.
- [ ] Se quiserem números (atendimentos, cursos), informar valores reais.

## Contato configurado

WhatsApp (11) 96176-9922. Cada card de queixa abre uma mensagem pré-preenchida diferente.
