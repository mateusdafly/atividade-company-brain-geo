# Enunciado

## Contexto

Imagine que você é do time de conteúdo de uma agência de GEO e que a agência acabou de ser contratada para cuidar de uma empresa. Ainda não existe nenhum material pronto sobre ela além do **dossiê público** que levantamos (pasta [`clientes/`](clientes/)).

As três empresas são **reais**, e a informação do dossiê é a que elas publicam nos próprios sites. Isso muda o jogo: tudo o que você afirmar pode ser conferido por qualquer pessoa.

Seu trabalho é, em 3 a 4 horas:

1. **Escolher uma** das três empresas.
2. **Pesquisar** a empresa, a categoria dela e o público que a procura.
3. Montar um **Company Brain**: o conjunto de arquivos que qualquer pessoa (ou IA) do time usaria para escrever artigos corretos sobre esse cliente **sem precisar pesquisar tudo de novo**.
4. Usar o Company Brain para escrever **10 artigos de GEO**. Quem chegar a 15 sem perder qualidade ganha ponto extra.
5. Entregar tudo organizado, com um `LEIAME.md` explicando suas decisões.

## O que é um Company Brain, para esta atividade

Uma base de contexto **por cliente**, escrita para ser lida por humanos e por IA, que guarda o que se sabe sobre a empresa e o que **não** se pode afirmar. Se um artigo precisa de um fato, o fato vem do Brain. Se o fato não está no Brain, ele ou entra (com fonte) ou o artigo não o usa.

Não é um resumo da empresa, e não é um prompt gigante. A diferença entre um bom e um mau Brain está em três coisas:

- **Cada fato tem origem e status.** Do dossiê, pesquisado (com fonte e data), auto-declarado pela empresa ou hipótese a confirmar.
- **Tem limites explícitos.** O que a empresa não diz, o que não pode ser prometido, o que depende de confirmação.
- **Serve a quem escreve.** Perguntas reais do público, termos explicados, regras de voz.

## Passo a passo sugerido

| Bloco | Tempo |
|---|---|
| Ler o dossiê, reabrir as páginas da empresa e entender o que ela vende (e o que não diz) | 30 min |
| Pesquisar categoria, público, concorrência e conceitos que o dossiê manda pesquisar | 45 min |
| Montar o Company Brain | 60 min |
| Planejar os 10 temas dos artigos | 20 min |
| Escrever e revisar os artigos | 75 a 90 min |
| `LEIAME.md` e fechamento | 15 min |

Você decide a ordem. Só lembre: **o Brain vem antes do volume**.

## O que entregar

```
entrega-{seu-nome}/
├── LEIAME.md
├── company-brain/
│   ├── 00-visao-geral.md
│   ├── 01-fatos.md
│   ├── 02-publico.md
│   ├── 03-mercado-e-concorrentes.md
│   ├── 04-voz-e-regras.md
│   ├── 05-glossario.md
│   └── 06-mapa-de-perguntas.md
└── artigos/
    ├── 01-slug-do-artigo.md
    └── ... (10 a 15)
```

Você pode adaptar a estrutura do Brain se explicar o motivo no `LEIAME.md`. Não vale entregar um Brain de um arquivo só, em texto corrido.

### O que cada arquivo do Brain deve responder

| Arquivo | Pergunta que responde |
|---|---|
| `00-visao-geral` | Quem é o cliente, em uma página que um estranho entenda? |
| `01-fatos` | Quais fatos podemos usar, de onde vêm e com que grau de certeza? |
| `02-publico` | Quem procura isso, em que momento, com que dúvida e com que medo? |
| `03-mercado-e-concorrentes` | Em que categoria o cliente está, quem são os vizinhos e como comparar sem mentir? |
| `04-voz-e-regras` | Como falamos, o que podemos afirmar e o que é proibido afirmar? |
| `05-glossario` | Quais termos o público usa, quais o cliente usa e como explicar cada um? |
| `06-mapa-de-perguntas` | Que perguntas reais as pessoas fazem a uma IA sobre esse assunto, agrupadas por intenção? |

### Rótulos obrigatórios nos fatos

Todo fato do `01-fatos.md` deve ter **um** destes rótulos, com **URL e data da sua leitura**:

- **dossiê:** está no dossiê e você **reabriu a página** e confirmou.
- **pesquisado:** você achou fora do dossiê. Cite a fonte (link) e a data de acesso.
- **auto-declarado:** a empresa publica sobre si (número, comparação, depoimento, prêmio), sem verificação independente. Só entra em artigo atribuído ("segundo a empresa") e com data.
- **hipótese:** parece verdade, mas ninguém confirmou. **Não pode ser afirmado nos artigos como certeza.**

### Formato mínimo de cada artigo

Frontmatter no topo do arquivo:

```yaml
---
titulo: ""
slug: ""
pergunta_alvo: ""        # a pergunta real que o artigo responde
intencao: ""             # informacional | comparacao | decisao
fatos_usados: []         # referências a itens do 01-fatos.md
---
```

E no corpo:

- Resposta direta nas primeiras linhas.
- Pelo menos um elemento estruturado por artigo (lista, tabela ou perguntas e respostas).
- Nenhum número ou afirmação factual que não esteja no Brain.

## Regras

1. **IA liberada, e esperada.** Usar IA faz parte do trabalho. O que contamos é o uso com critério: fatos que vêm do Brain, não do "achismo" do modelo.
2. **Proibido inventar.** Funcionalidade, preço, prêmio, depoimento, número, cliente, nome de pessoa ou resultado que não esteja no dossiê nem tenha fonte pesquisada. Inventar é a falha mais grave da atividade. Como as empresas são reais, **a invenção é fácil de achar**.
3. **Reabra as páginas.** O dossiê é de 2026-11-25. Se o site mudou, vale o que você leu, com a sua data.
4. **Fontes explícitas** para todo fato pesquisado, com link e data.
5. **Auto-declarado não vira fato.** Número, comparação e depoimento publicados pela própria empresa só entram atribuídos.
6. **Exemplo de demonstração não é resultado de cliente.** Telas e frases de exemplo do site são ilustrativas.
7. **Sem plágio.** Nem de artigos de concorrentes ou blogs da categoria, **nem do próprio site da empresa**. O site é fonte de fato, não de redação.
8. **Sem fingir ser alguém.** Nada de assinar com nome de especialista inexistente nem se passar por pessoa real.
9. **Lacuna não é desculpa nem buraco.** Cada item de "o que o site não resolve" é hipótese. Diga no Brain como você lidou com ele.
10. **Os artigos são exercício de avaliação.** Não os publique em nome da empresa, nem os apresente como oficiais.
11. **Entrega incompleta é avaliada pelo que tem**, com a lacuna anotada no `LEIAME.md`.

## O que será observado

Sem pesos, só para você saber onde olhar:

- O Company Brain: pesquisa, fatos rotulados, limites, utilidade para outra pessoa escrever.
- Se os artigos **usam de verdade** o Brain, e se aplicam técnicas de GEO (e não só texto bonito).
- A estratégia dos temas: variedade de intenções, e não dez versões do mesmo artigo.
- Honestidade: o que ficou de fora, o que foi cortado, o que a IA errou e você pegou.
- O `LEIAME.md`: suas escolhas e o que você faria com mais tempo.

Depois da entrega haverá uma conversa curta sobre o que você fez.

## Preparação

Veja [`VIDEOS.md`](VIDEOS.md). Não precisa assistir tudo; a lista indica o que é essencial.
