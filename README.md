# Portfolio de Projetos

Repositorio de projetos publicaveis do portfolio de Guilherme Correa, cobrindo
Power BI, dashboards HTML, analise exploratoria, Machine Learning e relatorios
interativos.

## Projetos

| Pasta | Projeto | Tipo | Entrega principal |
| --- | --- | --- | --- |
| `01-dashboard-macroeconomico-bcb/` | Dashboard Macroeconomico - Banco Central do Brasil | Power BI | Arquivo `.pbix` e documentacao. |
| `02-superstore-eda-interativa/` | Superstore - EDA e dashboard interativo | Python, HTML e JavaScript | Relatorio em `report/index.html`. |
| `03-ecommerce-360/` | E-commerce 360 - Performance e negocios | Power BI | Documentacao, dados e materiais de apoio. |
| `04-rossmann-previsao-vendas/` | Rossmann Sales Prediction | Machine Learning e series temporais | Relatorio HTML em `index.html`. |
| `05-clusterbr-municipios/` | ClusterBR - Segmentacao de municipios brasileiros | Machine Learning nao supervisionado | Relatorio HTML em `index.html`. |

## Estrutura Geral

Cada projeto tem README proprio e deve ser tratado como uma entrega
independente. As pastas podem conter:

- notebooks de exploracao/modelagem;
- dados brutos, processados ou amostras;
- dashboards HTML;
- imagens e graficos gerados;
- arquivos Power BI;
- scripts de apoio;
- documentacao complementar.

## Como Navegar

Leia primeiro o README da pasta do projeto desejado. Quando houver entrega HTML,
abra o `index.html` ou use um servidor local:

```powershell
python -m http.server 8000
```

## Manutencao

- Mantenha cada README de projeto atualizado com objetivo, dados, metodologia,
  tecnologias e forma de execucao.
- Se adicionar novo projeto, crie a pasta no padrao `NN-assunto-em-poucas-palavras/`
  (ex.: `06-copa-do-mundo/`), sempre com README, antes de publicar. O numero
  define a ordem e o nome vira o identificador do projeto no site.
- Evite versionar ambientes virtuais. A pasta `04-rossmann-previsao-vendas/.venv/` existe no
  workspace, mas nao deve ser usada como padrao para novos projetos.
- Preserve arquivos grandes que sejam parte explicita da entrega, como `.pbix` e
  HTMLs finais.

