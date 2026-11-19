# FALHAS — copilot-agentic

| data | o que quebrou | menor correção | prompt \| infra |
|---|---|---|---|
| 2026-09-07 | Prompt Mestre no clipboard xrdp (`thinclient_drives/.clipboard`) virou 0 bytes depois que o clipboard do cliente mudou; só as 60 primeiras linhas foram lidas; curso montado a partir do 2º arquivo enviado (`doc/Copilot_Agentes_Empresas_Formacao_Completa.md`) | copiar arquivo do clipboard pra disco (`doc/`) na PRIMEIRA leitura, antes de qualquer outra coisa | infra |
