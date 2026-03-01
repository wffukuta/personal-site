# W.F.Fukuta — Personal Site

Portfólio pessoal com foco em projetos de engenharia de software, evolução técnica e entregas práticas publicadas para web.

## Objetivo
Este repositório reúne uma vitrine simples e direta dos meus projetos, com informações de:
- domínio (gênero)
- status atual
- suporte
- stack usada
- resultado entregue
- descrição resumida
- link para acesso

## Sobre o site
A página principal carrega os dados de projetos a partir de uma planilha publicada em TSV no Google Sheets, renderizando cards dinamicamente no front-end.

## Stack técnica
- HTML5
- CSS3
- JavaScript (vanilla)
- Google Sheets (TSV) como fonte de conteúdo

## Como executar localmente
```bash
python3 -m http.server 4173 --bind 0.0.0.0
```
Depois acesse `http://localhost:4173`.

## Diferenciais
- Estrutura leve, sem dependências pesadas.
- Atualização de conteúdo orientada por planilha.
- Interface em tema escuro com feedback visual de status de suporte.

## Próximos passos
- Filtros por status/gênero.
- Busca por projeto.
- Melhorias de SEO e metadados sociais.
- Seção de contato e links profissionais (GitHub/LinkedIn).
