# Instruções para agentes de código

## Sobre este repositório

- Este projeto é uma aplicação estática publicada pelo GitHub Pages em <https://raiugami.github.io/relatorio-protocolos/>.
- `index.html` é a aplicação principal e contém o Leitor Procon. A implementação é autocontida em um único arquivo HTML; preserve esse formato, salvo pedido explícito do usuário.
- `lideranca.html` é a página da visão de liderança.
- O GitHub Pages publica a raiz do branch `main`. Uma alteração mesclada em `main` pode ser publicada no site.
- Não há suíte de testes automatizados configurada neste repositório no momento.

## Fluxo de trabalho

1. Antes de editar, confira `git status`, branch atual e diff. Preserve alterações que já existam; nunca as descarte ou sobrescreva.
2. Faça cada tarefa em uma branch própria, criada a partir do `main` atualizado. Não trabalhe diretamente em `main`, não faça push para `main` e não faça merge; entregue a branch/PR para revisão humana.
3. Descreva mudanças com escopo pequeno. Como `index.html` concentra muitas partes da aplicação, combine um único agente como autor de alterações nesse arquivo por vez. Se houver trabalho simultâneo, peça ao outro agente que revise ou teste até o primeiro concluir, evitando conflitos e perda de mudanças.
4. Edite os arquivos-fonte na raiz. Não trate cópias exportadas, capturas de tela ou arquivos temporários como fonte da verdade.
5. Ao terminar, revise `git diff --check` e o diff completo. Teste no navegador a página afetada; para alterações no leitor, valide ao menos a seleção de PDF/ZIP, os dados extraídos e a visualização de anexos quando aplicável.
6. Ao entregar, informe objetivo, arquivos alterados, verificações feitas, resultado e limitações ou riscos restantes. Não alegue testes que não executou.

## Dados e privacidade

- Use apenas dados fictícios em exemplos e testes. Nunca adicione PDFs reais de consumidores, nomes, CPFs, protocolos, dados bancários ou outros dados pessoais ao repositório, issues, commits ou PRs.
- Mantenha o processamento de reclamações no navegador e não envie o conteúdo dos documentos a servidores, serviços de IA, telemetria ou armazenamento persistente sem autorização explícita do usuário.
- Evite incluir dados extraídos de documentos em logs, mensagens de erro ou URLs.

## Compatibilidade

- Preserve o comportamento existente e a compatibilidade com o uso da aplicação publicada pelo GitHub Pages e aberta localmente quando aplicável.
- Não adicione dependências, etapas de build ou serviços externos sem justificar a necessidade no PR.
- Mantenha o idioma da interface em português do Brasil.
