# Change log — revisão do manuscrito EAAI

**Data:** 7 de novembro de 2026

## Alterações desta revisão

- Reescrito o resumo e reposicionados introdução e trabalhos relacionados para descrever a pergunta realmente avaliada: reconstrução contemporânea de T, visibilidade e CO, com validação por cenário completo e baselines espaciais.
- Atualizada a configuração de três casos para os nove cruzamentos de potência (5/10/20 MW) e velocidade de entrada (1/2/3 m/s), identificando seis casos de desenvolvimento e três casos reservados.
- Incorporados os resultados de seis rodadas de desenvolvimento e da avaliação única congelada de P05V03, P10V01 e P20V02. Os valores por cenário e os resumos são apresentados separadamente.
- Incluídos erros Ridge brutos e após projeção, com o efeito da projeção explicitado; mantida a indisponibilidade para entradas fora da regra min--max e a ressalva de que essa regra não valida suporte conjunto nem segurança.
- Atualizada a análise das faixas locais com distribuição das classes, concordância, subestimação, misses Critical e MAE do índice gradual. A regra permanece descrita como interpretação de pesquisa, sem validade operacional ou humana demonstrada.
- Reescritos discussão e conclusão para comunicar resultados mistos, limitações de validação e ausência de evidência de superioridade geral ou novidade algorítmica estabelecida.
- Removidas do fluxo do manuscrito as duas figuras de desempenho da análise exploratória de três casos; mantida a figura de layout. Os arquivos antigos permanecem arquivados, mas não são incluídos como resultados atuais.
- Atualizados os fragmentos LaTeX de tabelas, instruções de leitura e estado da etapa. O PDF foi compilado e revisado visualmente; tem 10 páginas.

## Integridade científica

Nenhuma simulação, observação física ou métrica nova foi inventada. Os resultados numéricos vêm dos arquivos e relatórios da etapa `eaai-development-six-scenario-2026-11-07`. Os parâmetros, os limiares de severidade e a divisão desenvolvimento/reservado foram preservados; os casos reservados não foram retreinados nem usados para selecionar modelos.

## Pendências antes de submissão

**Atualização de 14 de novembro de 2026:** o coautor Prof. Saulo aprovou as modificações desta versão. O apoio do CNPq foi confirmado e incluído na declaração de financiamento. Ainda falta depositar os dados e códigos em um repositório persistente e atualizar a citação do depósito antes da submissão. Não há alegação de validação física, de malha, de geometria ou de uso operacional.



## Repository update — 14 November 2026

- Published the coauthor-approved manuscript revision under the EAAI target and updated its funding statement with CNPq Funding Code 131754/2025-4.
- Added the reproducibility and manuscript status notes, source, bibliography, used table fragments, and layout figure.
- Added the two existing author-review ZIP packages with SHA-256 checksums; no simulation data or scientific results were changed by this repository update.
- No DOI-registered archival deposit has been created and the manuscript has not yet been resubmitted.
