# Desafio Técnico para Dev Júnior
Bem-vindo ao desafio técnico para a vaga de Desenvolvimento Júnior! Este teste está dividido em duas etapas, cada uma avaliando habilidades diferentes:

Desafio de Power BI – Focado em transformação de dados, modelagem e visualização.

Desafio de Desenvolvimento Web – Avaliação de HTML, CSS (SASS/SCSS) e JavaScript puro.

Espera-se a entrega das duas atividades, porém caso você não tenha exito em uma das etapas, entregue o maximo que conseguir, qualquer entrega será avaliada.

## 📊 1. Desafio de Power BI
Objetivo
Criar um relatório interativo no Power BI consumindo dados de uma planilha do Google Sheets, com navegação entre telas e filtros compartilhados.

Requisitos
✅ Conexão com Google Sheets
Panilha para o BI: https://docs.google.com/spreadsheets/d/e/2PACX-1vScf3uQduJ5Oj3MAFHflgaC0y7qkeGjby6pdKHAYhCVnl4i7ZwbzVmo8omahswXiwglHqdcNYMajmtD/pub?output=xlsx
Panilha para o JS: https://docs.google.com/spreadsheets/d/e/2PACX-1vScf3uQduJ5Oj3MAFHflgaC0y7qkeGjby6pdKHAYhCVnl4i7ZwbzVmo8omahswXiwglHqdcNYMajmtD/pub?output=csv

Usar Power Query para importar os dados.

Garantir que os dados estejam limpos e formatados corretamente.

✅ Relatório com 3 Páginas

Visão Geral – KPIs principais (métricas-chave).

Análise Temporal – Gráfico de linhas ou barras mostrando tendências.

Análise por Categoria – Comparação entre diferentes segmentos.

✅ Interatividade

Slicers que mantenham o filtro em todas as páginas.

Botões de navegação entre telas.

Pelo menos um drill-through (ex: clicar em um resumo para ver detalhes).

Entrega
Arquivo .pbix funcional.

Breve documentação explicando:

Como reproduzir a conexão com o Google Sheets.

Transformações aplicadas nos dados.

Decisões de design (por que escolheu esses gráficos?).

## 🌐 2. Desafio de Desenvolvimento Web
Objetivo
Desenvolver uma página web que consuma dados de uma planilha do Google Sheets e os exiba de forma interativa.

Requisitos
✅ Configuração Inicial

bash
git clone https://github.com/SeduhGTI/desafioSEDUH
cd projeto
npm install  # (se aplicável)


✅ 🎨 Configuração do SASS

1. Instale o Node.js ([download aqui](https://nodejs.org/))
2. Execute no terminal:
   ```bash
   npm install -g sass

   Comando para rodar o SASS - sass --watch src/scss:dist/css

✅ Integração com Google Sheets

Consumir dados via API do Google Sheets (JSON ou Sheets API).

Tratar possíveis erros (falha na conexão, dados vazios).

✅ Interface (Front-End)

1 tela responsiva com:

Listagem dos dados (tabela ou cards).

Filtros client-side (busca, dropdown, etc.).

Um gráfico simples (Chart.js, ApexCharts, ou similar).

✅ Tecnologias

HTML semântico (acessibilidade).

SCSS/SASS (organização em partials).

JavaScript Vanilla (sem frameworks).

Webpack/Vite (opcional, mas valorizado).

✅ Bônus (Opcional)

Dark mode.

Ordenação de colunas.

Deploy no Netlify/Vercel.

Entrega
Repositório Git com commits bem estruturados.

README.md contendo:

Como executar o projeto.

Link da planilha usada.

Explicação das decisões técnicas.

📌 Instruções Finais
Escolha uma ou ambas as etapas.

Dê atenção à organização do código e documentação.

Dúvidas? Consulte o avaliador ou o documento de orientações.

Boa sorte! 🚀