# Agents - agency-agents

## Allowed Actions
- Ler agentes e documentacao existente.
- Adaptar exemplos para uso local do workspace MedShare.
- Criar outputs versionados em `outputs/`.

## Agents To Use
- `../../shared_agents/strategist.md`
- `../../shared_agents/reviewer.md`
- `../../shared_agents/tester.md`

## Constraints
- Manter este projeto generico, sem acoplar regras MedShare ao conteudo upstream.
- Referenciar contratos globais quando houver input/output estruturado.
- Preservar nomes, licencas e estrutura original sempre que possivel.

## What Not To Do
- Nao substituir agentes compartilhados do workspace por copias locais.
- Nao mover arquivos originais sem necessidade.
- Nao gravar outputs fora de `outputs/`.
