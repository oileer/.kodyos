# .escritorio — Seu CEO de IA em 5 minutos

> Um sistema de agentes de IA personalizado que você cria uma vez e usa para sempre.

## O que é isso?

A maioria das pessoas usa IA de forma reativa — pergunta, recebe resposta, repete.

O Escritório de IA muda isso. Você deixa de ser alguém que usa IA e passa a ser alguém que **orquestra** IA.

Um CEO digital que conhece seus projetos, seus clientes, suas ferramentas e sabe delegar para os agentes certos na hora certa.

## Como instalar

### Pré-requisito
- [Claude Code](https://claude.ai/code) instalado

### Instalação

1. Abra o Claude Code na pasta raiz do seu computador
2. Cole o link deste repositório no chat:
   ```
   https://github.com/oileer/.escritorio
   ```
3. O Claude vai ler o `CLAUDE.md` e iniciar a entrevista
4. Responda as perguntas — leva menos de 5 minutos
5. Seu CEO estará criado e pronto para usar

## O que você vai ter no final

```
sua-pasta/
└── .escritorio/
    ├── CEO.md                    ← seu orquestrador personalizado
    ├── memoria/
    │   └── CEO/
    │       └── CONTEXTO-AGENTES.md
    └── agentes/
        └── (você cria conforme precisar)
```

## Como usar depois

Abra o Claude Code em qualquer projeto e diga:

> "Ative o CEO"

Ele vai conhecer seus projetos, seus clientes e vai coordenar tudo a partir daí.

## Exemplos de agentes que você pode criar depois

| Agente | Para quê |
|--------|----------|
| Dev | Código, bugs, automações |
| Criativo | Roteiros, copys, posts |
| Vendas | Scripts, follow-up, propostas |
| Operações | Tarefas, arquivos, organização |
| Pesquisador | Tendências, concorrentes, referências |

Cada agente é um arquivo `.md` dentro da pasta `.escritorio/agentes/`. O CEO sabe quando chamar cada um.

## Por que funciona

LLMs só são boas quando têm contexto. Sem contexto, a IA chuta. Com contexto, ela executa.

Este repositório ensina a IA a **perguntar** o contexto certo antes de construir qualquer coisa. O resultado é um sistema que foi feito pra você — não pra mais ninguém.

---

Criado por [@eullerlolato](https://x.com/eullerlolato_)
