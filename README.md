# Plano 30 — Secar e Ficar Forte

App pessoal de uma página só (`index.html`) para acompanhar dieta, treino e hábitos pelo celular, com o calendário real de **13/11/2026 a 31/12/2027**.

Abra pelo GitHub Pages: **https://reset-hightide.github.io/plano30/**

## O que tem
- **Hoje**: dia real com data, calendário do mês (toque num dia para abrir), agenda do dia (acordo 6h30 ou 3h30), refeições, checklist com intensidade (🌱 mínimo · 🎯 na meta · 🔥 acima), água de 250 em 250 ml e o treino do dia com cronômetro de descanso.
- **Hábitos**: mapa de calor no estilo do GitHub, por mês ou pelo ano inteiro, uma faixa por indicador (treino, proteína, dieta, água, passos, sono, estudo, leitura, jogo) e a barra do caminho até 31/12/2027.
- **Dieta**: metas de macros, opções de cada refeição e trocas.
- **Progresso**: peso e cintura com data, gráfico do peso e backup dos dados.
- **Regras**: mandamentos, ciclos de 4 semanas (base → carga → volume → intensidade) e quando ajustar.

## Onde ficam os dados
- Nesta página do GitHub os registros ficam salvos no navegador do celular (`localStorage`, chave `plano30v2`). Use **Progresso → Baixar backup** de vez em quando e **Restaurar backup** para levar para outro aparelho.
- A mesma página também roda como artifact do Claude. Lá os registros vão para um banco de dados na conta e aparecem em qualquer aparelho.
- A versão antiga (dias 1–30, chave `plano30`) é migrada sozinha na primeira abertura.

## Arquivos
- `index.html`: o app (HTML, CSS e JS num arquivo só, sem dependências).
- `app.html`: o mesmo app sem o cabeçalho `<html>`, usado na versão artifact.
