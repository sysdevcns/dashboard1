# Dashboard Executivo — Dados Demonstrativos

## Visão geral

Este projeto contém um dashboard HTML demonstrativo para apresentação de indicadores executivos. Os dados, nomes, empresas, projetos e referências corporativas foram substituídos por informações fictícias, permitindo o uso seguro como protótipo, material de apresentação ou base visual para novos produtos de dados.

## Arquivo principal

- `dashboard_v3_dados_ficticios.html` — dashboard estático em HTML, CSS e JavaScript.

## Como utilizar

1. Baixe o arquivo HTML.
2. Abra-o em um navegador moderno, como Chrome, Edge ou Firefox.
3. Para publicar internamente, hospede o arquivo em um servidor web, repositório GitHub Pages, SharePoint ou portal corporativo.
4. Para adaptar ao ambiente produtivo, substitua os dados demonstrativos por uma fonte controlada, como API, arquivo JSON, banco de dados ou camada semântica publicada.

## Características

- Layout responsivo para desktop e dispositivos móveis.
- Tema visual configurável.
- Indicadores, gráficos e tabelas demonstrativas.
- Estrutura adequada para prototipação de dashboards.
- Dados fictícios, sem referência a empresas, pessoas, projetos ou valores corporativos reais.

## Estrutura recomendada para evolução

```text
dashboard/
├── dashboard_v3_dados_ficticios.html
├── README_DASHBOARD.md
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
└── data/
    └── dados_demonstrativos.json
```

## Integração futura com dados

Para uma versão conectada à plataforma de dados, recomenda-se que o dashboard consuma apenas objetos de publicação, como `REL_*`, APIs controladas ou tabelas de serving. Evite conectar a interface diretamente às camadas Bronze, Prata ou às tabelas técnicas da camada Ouro.

Fluxo recomendado:

```text
Fontes → Ingestão → Bronze → Prata → Ouro → REL_/API → Dashboard
```

## Boas práticas

- Não inserir credenciais no HTML ou JavaScript.
- Não expor dados sensíveis em arquivos estáticos.
- Versionar alterações no Git.
- Manter uma versão demonstrativa separada da versão produtiva.
- Registrar alterações relevantes de layout, métricas e regras de cálculo.

## Observação

Este dashboard é uma referência visual e funcional. As regras de negócio devem permanecer centralizadas na camada semântica e nos objetos de publicação da plataforma de dados.
