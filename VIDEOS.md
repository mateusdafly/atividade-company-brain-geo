# Preparação: vídeos e leituras

Veja isso **antes** do dia da atividade. O tempo da atividade (3 a 4 horas) é para pesquisar a empresa e produzir, não para aprender o básico.

Os vídeos daqui são só sobre **três coisas**: o que é um **Company Brain**, o que é **GEO**, e **como fazer o que a atividade pede**. Nenhum é sobre as empresas: o que cada uma faz, você descobre nos sites e nas fontes delas.

## Leia isto primeiro

- **⭐ = essencial.** **✔ = a transcrição foi lida e a descrição abaixo diz o que o vídeo realmente traz.** Vídeo sem ✔ ainda não foi conferido: a descrição vem só do título e do resumo.
- Os ⭐ somam **cerca de 1h20**. O resto é opcional.
- A **duração** de cada vídeo foi conferida em 2026-11-25. Título e canal são os que aparecem no YouTube.
- **Nenhum desses vídeos é o gabarito.** Vários são de agências e fornecedores, com tom promocional. Alguns são, em parte, demonstração de uma ferramenta paga. Pegue vocabulário e método, e confronte com as fontes primárias da seção "Leituras" no fim.
- Vários vídeos de Company Brain usam o **Claude** como exemplo. O método (arquivos de contexto organizados) funciona com qualquer IA.
- **A maior parte está em inglês.** Ligue a legenda. Só dois vídeos da lista são em português (o de RAG e o "Company Brain EXPLICADO").

## Como a lista se encaixa na atividade

| O que você vai fazer | Onde se prepara |
|---|---|
| Entender o que é um **Company Brain** e montar o seu | Blocos 2 e 3 |
| Entender como a IA usa o contexto que você dá | Bloco 4 (opcional) |
| Entender **GEO** | Bloco 5 |
| Escrever os **10 artigos** | Bloco 6 |
| Montar o **mapa de perguntas**, a **voz** e as **regras** | Bloco 7 |

---

## 1. Base mínima: como a IA "sabe" e "cita" (pule se já souber)

| | Vídeo | Canal | Duração | O que traz |
|---|---|---|---|---|
| ⭐✔ | [Large Language Models explained briefly](https://www.youtube.com/watch?v=LPZh9BOjkQs) | 3Blue1Brown | 7:58 | Explica com clareza que um modelo de linguagem **prevê a próxima palavra** e por que a resposta muda a cada vez. Não fala de busca nem de citação de fontes. |
| ✔ | [O que é RAG - Dicionário IA](https://www.youtube.com/watch?v=xWe3adsDfVk) (em português) | NoCode StartUp | 6:07 | A analogia da "estante de livros" nos primeiros minutos ajuda. **O resto é, em boa parte, divulgação da comunidade do canal.** Cuidado: o vídeo diz "treinar" o agente com seus documentos, mas **RAG não treina o modelo**: ele busca trechos dos documentos na hora e os entrega ao modelo para responder. |
|  | [[1hr Talk] Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) | Andrej Karpathy | 59:48 | Visão longa e completa. Opcional. |

## 2. O que é um Company Brain

| | Vídeo | Canal | Duração | O que traz |
|---|---|---|---|---|
| ⭐ | [Company Brain EXPLICADO](https://www.youtube.com/watch?v=1Wq1mJ-PAeQ) (em português) | Pelado Nerd | 13:04 | Pelo título: o conceito, em português. |
| ⭐ | [Intro: Build a Company Brain Every AI Can Use](https://www.youtube.com/watch?v=ui1wN4du8K4) | Darby Rollins, Gen AI University | 9:10 | Pela descrição, a ideia de um Brain feito de **arquivos em markdown numa pasta**, que qualquer IA consegue ler. É o formato que você vai entregar. |
|  | [How to Build An AI Brain For Your Company](https://www.youtube.com/watch?v=lOjZT82t0JA) | Ash Behrens | 18:28 | Pela descrição, usa o padrão "raw, wiki, schema" atribuído a Andrej Karpathy. |
|  | [Building a Shared Company Brain for Humans, Agents, and Workflows](https://www.youtube.com/watch?v=q0v0eplAeYA) | Box | 2:14 | Vídeo de fornecedor. Curto; serve para ver como uma empresa vende o conceito. |
|  | [Build a Company Brain: Unlock Hidden Knowledge with AI](https://www.youtube.com/watch?v=QbLrXMbRSCY) | Open eLMS | 5:21 | Vídeo de fornecedor. |

**O que observar:** cada autor define "Company Brain" de um jeito. Anote **onde as definições divergem**. Você vai precisar escolher uma definição para o seu `00-visao-geral.md`.

## 3. Como montar o seu (a parte prática)

Os vídeos mais próximos do que você vai fazer: transformar conhecimento em **arquivos de contexto** que uma IA usa.

| | Vídeo | Canal | Duração | O que traz |
|---|---|---|---|---|
| ⭐ | [How to setup a business brain (powered by Claude)](https://www.youtube.com/watch?v=7-yAe5Tzn0U) | Brian Casel | 19:09 | Pelo título: passo a passo de montagem de um "cérebro" para um negócio. |
|  | [Build Your Second Brain With Claude Code, Karpathy's Method](https://www.youtube.com/watch?v=lnsExa1UbnM) | AI for Work | 15:17 | Pela descrição, um "cérebro" local só de arquivos em markdown. Ferramentas mais técnicas, mas a organização das pastas vale. |
|  | [5. Context Files: How to Teach Claude the Way You Work](https://www.youtube.com/watch?v=PjKsrBRwu7g) | Axon Perform | 4:20 | Arquivos de contexto que dizem à IA quem você é e como trabalha. |

**O que observar:** como o autor **divide o conhecimento em arquivos**, **como separa fato de opinião**, e **o que ele deixa de fora**.

## 4. Dar contexto à IA (opcional)

| | Vídeo | Canal | Duração | O que traz |
|---|---|---|---|---|
| ✔ | [Context Engineering Clearly Explained](https://www.youtube.com/watch?v=jLuwLJBQkIs) | Tina Huang | 12:48 | A ideia central: dar à IA **"a informação certa, no formato certo, na hora certa"**. **Mas o vídeo é sobre construir agentes de IA** (prompts de sistema, ferramentas, memória), com um trecho patrocinado, e isso está longe do que você vai fazer. Aproveite a definição e as quatro estratégias do final (**escrever, selecionar, comprimir e isolar** contexto). |

## 5. O que é GEO

| | Vídeo | Canal | Duração | O que traz |
|---|---|---|---|---|
| ⭐✔ | [What Is GEO? Generative Engine Optimization Explained (2026): 5 Key Principles](https://www.youtube.com/watch?v=Oq7qV4_5W-A) | Alex Moreau, AI for Ads & SEO-GEO | 7:03 | **Em parte é demonstração de uma ferramenta (Ryze), com link na descrição.** Mesmo assim traz uma checklist com fontes: medir onde as IAs **nomeiam** a sua marca, **responder primeiro e com números**, dizer algo que só você pode dizer, deixar os robôs de busca entrarem (robots.txt) e atualizar as páginas. |
|  | [What Is Generative Engine Optimization (GEO)? A Beginner's Guide](https://www.youtube.com/watch?v=p0pf2M1t5xI) | Found in AI Podcast, Cassie Clark Marketing | 12:09 | Não conferido. |
|  | [Generative Engine Optimization (GEO) Explained](https://www.youtube.com/watch?v=5F0_IFIVeWs) | Howseen AI | 1:56 | Não conferido. |

## 6. Como escrever um artigo de GEO

É a parte que mais pesa nos seus 10 artigos.

| | Vídeo | Canal | Duração | O que traz |
|---|---|---|---|---|
| ⭐✔ | [How to Get Your Brand Cited by ChatGPT - The GEO Playbook That Actually Works](https://www.youtube.com/watch?v=3wpzzM9DiT0) | Anand Iyer | 16:58 | O mais completo da lista. Plano de 7 passos: teste manual de perguntas, acesso dos robôs, **resposta primeiro e títulos em forma de pergunta**, **densidade de fatos** (dados com fonte no lugar de adjetivos), clareza da marca em vários sites, e atualização frequente. **Atenção: quase todas as estatísticas dele são ditas sem fonte** (ex.: "94% dos compradores B2B usam IA", "tabelas rendem 4x mais citações", "conteúdo com mais de 13 semanas deixa de ser citado"). Trate cada número como **auto-declarado**. |
| ⭐✔ | [AEO/GEO Citation Game Plan in 2026 – Pillar 2: Structured Content for AI Search Visibility](https://www.youtube.com/watch?v=lA8Jo3yIfkk) | Kevin C. Roy, GreenBananaSEO | 4:19 | Curto e prático. Estrutura de página em **três blocos**: **resposta** (nas 2 a 5 primeiras frases), **prova** (listas, tabelas, perguntas e respostas) e **caminho** (as perguntas seguintes, tiradas de "as pessoas também perguntam"). É parte 2 de 4 de uma série. |
|  | [GEO Checklist: 5 Rules to Get Your Business Cited in AI Answers](https://www.youtube.com/watch?v=X7TqNxVjW-4) | WKND | 9:40 | Não conferido. |
|  | [How to Get Cited by Perplexity AI: Optimizing for AI Search (GEO Course)](https://www.youtube.com/watch?v=_R47uiMef7Y) | FreeAcademy AI | 7:33 | Não conferido. |
|  | [Optimize Existing Blog Posts for GEO (Without Rewriting Everything)](https://www.youtube.com/watch?v=iypzmWZf2yU) | Rebecca Grace Designs | 19:46 | Não conferido. |
|  | [How to do GEO as a Beginner (full AI SEO Course)](https://www.youtube.com/watch?v=dXhUg9Eu0xM) | Vasco's SEO Tips | 17:27 | Não conferido. |

### Onde os vídeos discordam (leia com atenção)

Os dois vídeos ⭐ de escrita **não dizem a mesma coisa** sobre um ponto:

- **Schema markup** (marcação técnica para buscadores): Kevin Roy diz que é **"super importante"**; Anand Iyer lista como **mito** que o schema aumente citações diretamente.
- **llms.txt** (arquivo-resumo do site para IAs): Anand diz que não é necessário; Alex Moreau, citando o guia do Google, diz que **não ajuda nem atrapalha** a busca do Google, mas que é "um arquivo pequeno para agentes de IA".
- **Números:** nenhum dos vídeos mostra a fonte dos percentuais que cita.

**Nenhum deles prova o que diz.** Para o seu Brain, a conclusão certa é marcar cada técnica contestada como **hipótese**, e dizer **como você testaria** (por exemplo, perguntando às IAs e vendo quem é citado, como no bloco "Para praticar sozinho"). Onde um vídeo cita um estudo (o paper de GEO, a documentação do Google), vá à fonte.

## 7. Perguntas, voz e regras

Não há vídeo que eu recomende com segurança para o seu `06-mapa-de-perguntas.md`: os que encontrei sobre "descobrir os prompts que as pessoas usam" são, na maioria, demonstrações de ferramentas pagas. Use o que os vídeos do bloco 6 já ensinam:

- **Três tipos de pergunta para testar** (Anand Iyer): de **categoria** ("melhores X para Y"), de **comparação** ("A versus B") e **comerciais** ("vale a pena?", preço).
- **Perguntas de follow-up** (Kevin Roy): olhe "as pessoas também perguntam" no Google para achar o que vem depois da primeira dúvida.
- **Pergunte você mesmo às IAs** e anote as perguntas que elas sugerem e as fontes que citam (veja "Para praticar sozinho").

Para **voz e regras** (`04-voz-e-regras.md`), a base é uma lista clara do que **pode** e do que **não pode** ser afirmado, mais alguns **textos reais** da própria empresa como referência de tom. Isso é método seu, não de vídeo.

Opcional, sem conferência: [Webinar: Why Your GEO Strategy is Probably Wrong (And What Actually Works)](https://www.youtube.com/watch?v=l_vv9q6MxwU), The Grow and Convert Marketing Show, 31:22. Pelo resumo, é uma visão crítica de práticas populares de GEO.

---

## Leituras (fontes primárias)

Mais importantes que qualquer vídeo da lista.

- ⭐ **[GEO: Generative Engine Optimization](https://arxiv.org/abs/2311.09735)** (artigo acadêmico, arXiv). O paper que deu nome à área. Leia o resumo e a seção sobre as técnicas testadas. Pergunta: em que tipo de pergunta cada técnica funcionou melhor?
- ⭐ **[Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)** (Google Search Central). A posição oficial do Google sobre conteúdo útil.
- **[AI features and your website](https://developers.google.com/search/docs/appearance/ai-features)** (Google Search Central). Como o Google trata o conteúdo do seu site nos recursos de IA da busca.
- **[Company Brain conecta o contexto do negócio à inteligência artificial](https://startups.com.br/branded-content/company-brain-conecta-o-contexto-do-negocio-a-inteligencia-artificial/)** (startups.com.br). É **conteúdo de marca** de uma fornecedora brasileira, não matéria neutra. Leia como fonte de vocabulário e depois confronte com outras.

## Para praticar sozinho

Pergunte a duas IAs diferentes (por exemplo, ChatGPT e Perplexity) algo sobre a categoria da empresa que você escolheu. Observe:

- Que fontes elas citam e que **tipo de página** é citada (blog de empresa, notícia, documentação, órgão oficial, fórum)?
- A resposta começa direto ou enrola?
- Quais marcas aparecem, e em que ordem?
- **A empresa que você escolheu aparece?** Se aparece, o que dizem dela e está certo? Se não aparece, quem aparece no lugar?

Isso vale mais do que mais uma hora de vídeo.
