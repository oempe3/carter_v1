# TrendApp — Nível do cárter x horas trabalhadas (2025)

Pronto para publicar no **GitHub Pages**. Veja `index.html`.

## Publicação
1. Crie um repositório (ex.: `trendapp-carter-2025`).
2. Envie `index.html`, `assets/logo.png`, `data/data.csv` e `data/summary.json` para `main`.
3. Em **Settings → Pages**, selecione **Branch: main / root**.

## Atualização
Substitua `data/data.csv`. Colunas aceitas:
- Data (ou DataISO), Motor, Nivel_RDO, Nivel_Insp (opcional), Hora (opcional).

## Regras implementadas
- Tema escuro (tipo Flutter), logo no topo + “UTE PERNAMBUCO III”.
- Título “Nível do cárter x horas trabalhadas separadoras 2025”.
- 1 série por motor (linhas suavizadas), marcadores com rótulo (Hora).
- *Tooltip* com: Inspeção, H_inspeção, Dif_cm, Horas ano, Horas mês.
- Linhas verticais verdes pontilhadas nas **10 primeiras** datas do CSV.
- 23 cartões de resumo (ou quantos motores existirem).