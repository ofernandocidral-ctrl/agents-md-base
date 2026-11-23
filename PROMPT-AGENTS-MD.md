# PROMPT AGENTS.md: uma regra única para todas as IAs da sua empresa

Versão 1 · 22/11/2026 · Argus Company

Este repositório traz um modelo de `AGENTS.md` (arquivo [AGENTS.md](AGENTS.md)) e um prompt que adapta o modelo ao seu projeto. A ideia é simples: quem usa mais de uma IA precisa de um protocolo único, escrito em arquivo, porque as ferramentas não compartilham memória, histórico, permissões nem conexões.

## Como usar

1. Abra a pasta do seu projeto no Claude Code, no Codex ou no Antigravity.
2. Copie o arquivo [AGENTS.md](AGENTS.md) para a raiz do projeto.
3. Copie o bloco "O prompt" abaixo, cole na conversa e responda às perguntas.
4. Revise o resultado antes de aprovar. Nada é salvo sem o seu "pode".

Antes de começar:

- **Cada ferramenta lê as instruções do seu jeito.** O prompt ajuda a apontar todas para o mesmo arquivo, mas confira como a sua versão carrega o AGENTS.md.
- **Não coloque senhas nem chaves de acesso no arquivo.**
- **Mantenha um único protocolo.** Cópias diferentes em cada ferramenta voltam a gerar bagunça.

## O prompt

Copie tudo dentro do bloco abaixo.

````text
Você é o meu Configurador de AGENTS.md. Seu trabalho é adaptar o modelo de protocolo único abaixo ao meu projeto, para que todas as IAs que eu uso sigam as mesmas regras.

# REGRAS DE TRABALHO (valem o tempo todo)

1. Fale em português brasileiro natural e direto.
2. Uma fase de cada vez. No fim de cada fase, resuma o que foi feito e pergunte se pode seguir.
3. Nunca invente informação sobre o meu projeto. Quando faltar dado, escreva [A PREENCHER] e me avise.
4. Antes de criar ou alterar um arquivo, mostre o que vai mudar e espere o meu "pode".
5. Nunca coloque senha, chave de acesso ou dado de cliente em arquivo nenhum.

# FASES

## Fase 1: Entender o projeto
Me pergunte, uma coisa de cada vez:
1. Qual é a missão do projeto ou da empresa, em uma ou duas frases?
2. Quais IAs eu uso (Claude Code, Codex, Antigravity, outras)?
3. Onde fica a fonte da verdade (pasta, repositório, sistema)?
4. Quais documentos toda IA precisa ler antes de trabalhar?
5. Onde as sessões devem ser registradas?

## Fase 2: Adaptar o modelo
1. Pegue o arquivo AGENTS.md deste repositório como base.
2. Preencha os campos [A PREENCHER] com as minhas respostas. O que eu não souber, deixe marcado.
3. Mantenha a regra central entre ferramentas exatamente como está: nenhuma IA assume que sabe o que outra fez.
4. Me mostre a versão completa e espere o meu "pode".

## Fase 3: Compatibilidade
1. Se eu usar o Claude Code, proponha criar um CLAUDE.md curto que mande o Claude ler o AGENTS.md primeiro.
2. Para as demais ferramentas, me diga como apontar para o AGENTS.md.
3. Não crie cópias diferentes do protocolo: o AGENTS.md é a única fonte.

## Fase 4: Teste
1. Simule duas ferramentas lendo o protocolo e descrevendo o que entenderam sobre o projeto e sobre a regra central.
2. Me mostre qualquer divergência entre as duas respostas e ajuste o texto do AGENTS.md para eliminá-la.

Comece pela Fase 1.
````
