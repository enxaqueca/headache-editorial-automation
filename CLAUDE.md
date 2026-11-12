# headache-editorial-automation

Projeto de automação editorial de conteúdo sobre cefaleia e enxaqueca.

## Comece aqui, em toda sessão (regra fixa)

O trabalho deste projeto fica no **Dropbox**, na pasta `/Claude Code/Headache Editorial Automation/`. Este repositório guarda só estas regras de partida.

Antes de responder ou de fazer qualquer coisa:

1. Ler, nessa pasta do Dropbox, o arquivo `CLAUDE.md` (regras completas do projeto) e o handoff de data e letra maiores (`HANDOFF-AAAA-MM-DD[letra].md`: é o estado atual do trabalho).
2. Nunca pedir ao Dr. Feldman que cole ou reenvie o que está no Dropbox: ler a pasta.
3. Tratá-lo por "você", nunca "senhor". Sempre em português do Brasil. Sem jargão.
4. No que é técnico, decidir, fazer e avisar. Perguntar só o que é conduta médica, opinião dele ou voz.
5. Ao terminar, atualizar o handoff no Dropbox e acrescentar a linha da sessão em `SESSOES.md`, sem ele pedir.

Como ler e gravar no Dropbox: o conector lista, lê e cria arquivos novos, mas não sobrescreve. Para atualizar um arquivo, usar a API com as variáveis de ambiente `DROPBOX_APP_KEY`, `DROPBOX_APP_SECRET` e `DROPBOX_REFRESH_TOKEN` (hosts `api.dropboxapi.com` e `content.dropboxapi.com`; nunca `api.dropbox.com`), pelo cliente `codigo/hea/dbx.py` da própria pasta. Nunca gravar nem imprimir credenciais.

Onde as regras deste arquivo e as do `CLAUDE.md` do Dropbox divergirem, vale o do Dropbox, que é o mais atualizado.

## Repositório (regra fixa)

- O repositório deste trabalho é **exclusivamente** `enxaqueca/headache-editorial-automation`.
- Não ler, alterar, clonar nem enviar nada para nenhum outro repositório da conta, ainda que o GitHub dê acesso a eles.
- Se uma tarefa parecer exigir outro repositório, parar e perguntar antes.

## Fluxo de trabalho

- Autorização permanente da autora: enviar ao GitHub (`git push`) direto no `main` sempre que houver alteração concluída, sem pedir confirmação.
- Não usar branches nem pull requests, salvo se a autora pedir.
- Antes de enviar, conferir o conteúdo; nunca reescrever o histórico (`push --force`).
- Ao terminar, informar em linguagem simples o que foi enviado.
- Mensagens de commit em português.

## Regras editoriais aprovadas

- **Subtítulos em H2.** Seções do texto usam H2 (diretriz atual conferida). O H1 é reservado ao título do artigo.
- **Tom de voz:** seguir a amostra aprovada pela autora (ver `docs/amostra-tom.md` quando for adicionada).

## Referência: Yoast

- O site do Yoast (yoast.com) é a principal referência de SEO e legibilidade da autora.
- Usar como base para **discussão**, não como regra a seguir cegamente: quando uma recomendação do Yoast conflitar com clareza, precisão médica ou o tom aprovado, apontar o conflito e propor a melhor solução.
- Ao citar uma recomendação do Yoast, informar o link do artigo de origem.

## Pendências

- [ ] Adicionar o plano do projeto (`docs/plano.md`).
- [ ] Adicionar a amostra de tom aprovada (`docs/amostra-tom.md`).
- [ ] Adicionar o passo a passo de configuração (`docs/passo-a-passo.md`).
