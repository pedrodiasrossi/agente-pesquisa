# Agente de Pesquisa

Pasta de contexto para um agente de IA que me ajuda nas pesquisas científicas.

## Como usar

1. Preencha os arquivos em `pesquisa/` (comece por `perfil.md` e `objetivos.md`).
2. Ajuste `AGENTS.md` e `agent/persona.md`.
3. Abra esta pasta no harness de sua preferência.
4. Converse. Ao fim de cada sessão, peça: "registra o que fizemos".

## Estrutura

```
agente-pesquisa/
├── AGENTS.md          Definição do agente (lida por qualquer harness)
├── CLAUDE.md          Aponta para o AGENTS.md (Claude Code)
├── agent/
│   └── persona.md     Tom e postura do agente
├── pesquisa/
│   ├── perfil.md      Quem sou, minha área e ferramentas
│   ├── objetivos.md   Perguntas, hipóteses e metas
│   ├── trabalho-feito.md   Linha do tempo do que já fiz
│   ├── decisoes.md    Decisões metodológicas e motivos
│   ├── resultados/    Um arquivo por experimento ou análise
│   └── literatura/    Um arquivo por artigo lido
├── skills/            Guias passo a passo de tarefas
└── docs/
    └── como-me-alimentar.md   Lembretes para mim mesmo
```
