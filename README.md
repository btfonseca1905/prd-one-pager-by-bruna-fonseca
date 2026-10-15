# One-Pager de Produto by Bruna Fonseca

Skill para conduzir uma entrevista de Product Discovery e transformar as respostas em um **One-Pager de Produto em Markdown (`.md`)**.

Criada por **Bruna Fonseca**, Product Manager, professora e fundadora da b-a.BA Educação Corporativa, criadora da imersão D² [do Discovery ao Delivery].

## O que a Skill faz

1. Conversa com você **uma pergunta por vez**.
2. Entende o produto, a dor do cliente, a proposta de valor e o público-alvo.
3. Ajuda a selecionar as três funcionalidades mais importantes.
4. Confirma informações, hipóteses e pendências antes de finalizar.
5. Gera um documento `.md` conciso, pronto para compartilhar ou versionar.

## Estrutura do One-Pager

- **Cabeçalho:** Nome do Produto, Autor / Responsável, Data e Status.
- **1. Visão Geral do Produto:** duas frases sobre o produto e o problema que resolve.
- **2. O Problema:** dor do cliente e evidência breve, quando disponível.
- **3. A Solução:** como funciona e sua proposta de valor.
- **4. Persona:** quem usa o produto e em qual contexto.
- **5. Features:** três funcionalidades e seus benefícios.

Se não houver dados de pesquisa, a Skill sinaliza que a hipótese precisa ser validada. Ela não inventa estatísticas ou depoimentos.

## Estrutura dos arquivos

```text
gerar-one-pager-produto/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── one-pager-template.md
```

## Instalar no VS Code com Codex

1. Clone o repositório:

   ```bash
   git clone https://github.com/btfonseca1905/prd-one-pager-by-bruna-fonseca.git
   ```

2. Para uso em um projeto Codex, copie a pasta `gerar-one-pager-produto` para `.agents/skills/` no diretório do projeto, preservando os arquivos internos.
3. Abra o projeto no VS Code com a integração do Codex configurada e inicie uma conversa.

A descoberta automática depende do agente e da configuração. Para outros agentes, consulte o diretório de Skills previsto por eles.

## Como usar

> Use a Skill `gerar-one-pager-produto` para criar um One-Pager de Produto comigo. Faça uma pergunta por vez e, no final, gere o documento `.md`.

## Observações

- A Skill produz um documento executivo curto, não um PRD completo.
- A qualidade depende das informações fornecidas e da validação de hipóteses.
- O agente só poderá salvar diretamente um `.md` quando tiver acesso de escrita.

## Autoria

**Bruna Fonseca** | b-a.BA Educação Corporativa | D² [do Discovery ao Delivery]
