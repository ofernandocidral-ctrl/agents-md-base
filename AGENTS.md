# AGENTS.md

Protocolo único para todas as IAs que trabalham neste projeto (Claude Code, Codex, Antigravity e outras). Leia este arquivo antes de qualquer tarefa.

## 1. Missão e fonte da verdade

- Missão do projeto: [A PREENCHER: uma ou duas frases]
- A fonte da verdade fica em: [A PREENCHER: pasta, repositório ou sistema]
- Em caso de conflito entre duas fontes, vale a mais recente. Registre o conflito, não escolha em silêncio.

## 2. Regra central entre ferramentas

**Nenhuma IA pode assumir que sabe o que outra fez.** Memória, histórico de conversa, permissões e conexões NÃO são compartilhados entre ferramentas. Tudo que importa precisa estar escrito em arquivo.

- Ao começar, leia este arquivo e os documentos listados na seção 3.
- Use só os subagentes, ferramentas e conexões que a ferramenta atual realmente tem.
- Nunca diga que fez algo que não conferiu.

## 3. O que ler antes de trabalhar

- [A PREENCHER: arquivos de contexto, por exemplo perfil, prioridades, regras de escrita]

## 4. Como registrar o trabalho

Ao terminar cada sessão, grave uma nota em [A PREENCHER: pasta] com:

1. Pedido
2. O que foi feito
3. O que não foi feito
4. Arquivos criados ou alterados
5. Como foi verificado
6. Próximo passo

A nota é obrigatória mesmo quando nada foi alterado em arquivo.

## 5. Antes de agir

- Informação que você não conferiu vai marcada como [NÃO VERIFICADO].
- Nunca invente dado sobre clientes, métricas, datas ou resultados. Quando faltar, escreva [A PREENCHER] e pergunte.
- Antes de apagar ou sobrescrever, olhe o que está lá e peça confirmação.

## 6. Segurança

- Credenciais, chaves e tokens ficam fora de arquivos versionados e de qualquer resposta.
- Nada é enviado, publicado ou alterado em conta de terceiros sem aprovação humana.
- Dados de clientes ficam separados por cliente.

## 7. Economia de uso

- Pesquise antes de abrir arquivos grandes. Leia só o trecho necessário.
- Não releia o que já está no contexto.
- Uma fase de cada vez. Pergunte antes de seguir quando houver decisão do dono do projeto.
