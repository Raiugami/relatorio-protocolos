# Gestão de Produtividade

Aplicação web para registrar a rotina diária dos analistas PROCON e acompanhar os resultados da equipe pela visão da liderança. O projeto é composto por duas páginas estáticas, publicadas pelo GitHub Pages.

## Aplicações

- [Aplicação do analista](https://raiugami.github.io/relatorio-protocolos/) — [abrir `index.html`](./index.html). Registra produção e jornada no Controle Diário, ocorrências, fechamento mensal e, para PROCON CADASTRO, leitura e conclusão de cadastros.
- [Visão da liderança](https://raiugami.github.io/relatorio-protocolos/lideranca.html) — [abrir `lideranca.html`](./lideranca.html). Importa fechamentos e apresenta indicadores consolidados, ranking, análise individual, ocorrências e horas extras.

## Uso

1. Abra a aplicação correspondente ao seu perfil.
2. Na aplicação do analista, configure nome, funcional, setor, jornada e metas. Registre a produção e as horas trabalhadas no Controle Diário.
3. Exporte o fechamento mensal em JSON para compartilhar os resultados com a liderança.
4. Na Visão da liderança, importe os arquivos de fechamento para consultar e comparar os resultados por setor e competência.

Os dados do analista e os fechamentos importados pela liderança são mantidos no armazenamento local do navegador. Use as opções de backup e exportação da aplicação para guardar cópias e transferir dados entre navegadores.

## Páginas do projeto

| Arquivo | Aplicação |
| --- | --- |
| `index.html` | Ferramentas de registro e acompanhamento do analista |
| `lideranca.html` | Painel gerencial e análise dos fechamentos importados |

O projeto usa HTML, CSS e JavaScript no navegador. Não é necessário instalar dependências para abrir as páginas localmente; para usar a janela flutuante do contador, abra a aplicação publicada em HTTPS num navegador compatível.
