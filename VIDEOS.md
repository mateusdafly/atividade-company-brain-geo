# Preparação: vídeos e leituras

Veja isso **antes** do dia da atividade. O tempo da atividade (3 a 4 horas) é para pesquisar a empresa e produzir, não para aprender o básico.

Os vídeos daqui são só sobre **três coisas**: o que é um **Company Brain**, o que é **GEO**, e **como fazer o que a atividade pede**. Nenhum é sobre as empresas: o que cada uma faz, você descobre nos sites e nas fontes delas.

## Leia isto primeiro

- Os itens marcados com ⭐ são os essenciais. Somam **cerca de 1h55**. O resto é opcional.
- A **duração** de cada vídeo foi conferida em 2026-11-25. Título e canal são os que aparecem no YouTube.
- **Nenhum desses vídeos é o gabarito.** Muitos são de agências e fornecedores, com tom promocional e pouca evidência. Pegue vocabulário e método, e confronte com as fontes primárias da seção "Leituras" no fim.
- Vários vídeos de Company Brain usam o **Claude** como exemplo. O método (arquivos de contexto organizados) funciona com qualquer IA.
- A maior parte está em inglês. Ligue a legenda se precisar.
- Não assisti a todos do início ao fim: as descrições abaixo vêm do título e do resumo do vídeo. Se algum não valer o tempo, pule e diga no seu `LEIAME.md`.

## Como a lista se encaixa na atividade

| O que você vai fazer | Onde se prepara |
|---|---|
| Entender o que é um **Company Brain** e montar o seu | Blocos 2 e 3 |
| Dar **contexto certo** à IA para ela escrever sem inventar | Bloco 4 |
| Entender **GEO** | Bloco 5 |
| Escrever os **10 artigos** | Bloco 6 |
| Montar o **mapa de perguntas** do público | Bloco 7 |
| Definir **voz e regras** | Bloco 8 |

---

## 1. Base mínima: como a IA "sabe" e "cita" (opcional, se faltar o básico)

| | Vídeo | Canal | Duração |
|---|---|---|---|
| ⭐ | [Large Language Models explained briefly](https://www.youtube.com/watch?v=LPZh9BOjkQs) | 3Blue1Brown | 7:58 |
| ⭐ | [O que é RAG - Dicionário IA](https://www.youtube.com/watch?v=xWe3adsDfVk) (em português) | NoCode StartUp | 6:07 |
|  | [[1hr Talk] Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) | Andrej Karpathy | 59:48 |

Se você já sabe como uma IA gera uma resposta e como ela busca e cita fontes, pule este bloco.

## 2. O que é um Company Brain

| | Vídeo | Canal | Duração | Observação |
|---|---|---|---|---|
| ⭐ | [Company Brain EXPLICADO](https://www.youtube.com/watch?v=1Wq1mJ-PAeQ) (em português) | Pelado Nerd | 13:04 | O conceito, em português. |
| ⭐ | [Intro: Build a Company Brain Every AI Can Use](https://www.youtube.com/watch?v=ui1wN4du8K4) | Darby Rollins, Gen AI University | 9:10 | Pela descrição, é a ideia de um Brain feito de **arquivos em markdown numa pasta**, que qualquer IA consegue ler. É exatamente o formato que você vai entregar. |
|  | [How to Build An AI Brain For Your Company](https://www.youtube.com/watch?v=lOjZT82t0JA) | Ash Behrens | 18:28 | Pela descrição, usa o padrão "raw, wiki, schema" atribuído a Andrej Karpathy. |
|  | [Building a Shared Company Brain for Humans, Agents, and Workflows](https://www.youtube.com/watch?v=q0v0eplAeYA) | Box | 2:14 | Vídeo de fornecedor. Curto; serve para ver como uma empresa vende o conceito. |
|  | [Build a Company Brain: Unlock Hidden Knowledge with AI](https://www.youtube.com/watch?v=QbLrXMbRSCY) | Open eLMS | 5:21 | Vídeo de fornecedor. |

**O que observar:** cada autor define "Company Brain" de um jeito. Anote **onde as definições divergem**. Isso vale mais do que decorar uma delas, e você vai precisar escolher uma definição para o seu `00-visao-geral.md`.

## 3. Como montar o seu (a parte prática)

Aqui estão os vídeos mais próximos do que você vai fazer: transformar conhecimento em **arquivos de contexto** que uma IA usa.

| | Vídeo | Canal | Duração | Observação |
|---|---|---|---|---|
| ⭐ | [How to setup a business brain (powered by Claude)](https://www.youtube.com/watch?v=7-yAe5Tzn0U) | Brian Casel | 19:09 | Passo a passo de montagem de um "cérebro" para um negócio. |
|  | [Build Your Second Brain With Claude Code, Karpathy's Method](https://www.youtube.com/watch?v=lnsExa1UbnM) | AI for Work | 15:17 | Pela descrição, um "cérebro" local só de arquivos em markdown. Ferramentas mais técnicas, mas a organização das pastas vale. |
|  | [5. Context Files: How to Teach Claude the Way You Work](https://www.youtube.com/watch?v=PjKsrBRwu7g) | Axon Perform | 4:20 | Arquivos de contexto que dizem à IA quem você é e como trabalha. Curto. |

**O que observar:** como o autor **divide o conhecimento em arquivos** (um assunto por arquivo?), **como separa fato de opinião**, e **o que ele deixa de fora**.

## 4. Contexto em vez de "prompt perfeito"

Um Company Brain é, no fundo, **engenharia de contexto**: decidir o que a IA lê antes de escrever. Isso explica por que o Brain vem antes dos artigos.

| | Vídeo | Canal | Duração |
|---|---|---|---|
| ⭐ | [Context Engineering Clearly Explained](https://www.youtube.com/watch?v=jLuwLJBQkIs) | Tina Huang | 12:48 |
|  | [Context Engineering Explained: Beyond Prompts & RAG](https://www.youtube.com/watch?v=iu3CD_E-kUY) | Tim TEN | 10:09 |
|  | [Context Engineering Explained in Just 10 min](https://www.youtube.com/watch?v=523PQmw6_3k) | Analytics Camp | 10:45 |
|  | [Context Engineering Explained: Why More Context Doesn't Mean Better AI](https://www.youtube.com/watch?v=D9vE-9mSUaw) | MLTut | 17:03 |

**O que observar:** o último vídeo defende que **mais contexto não é melhor**. Isso conta para o seu Brain: um Brain gigante e cheio de informação irrelevante piora os artigos.

## 5. O que é GEO

Todos são de produtores de conteúdo de marketing. Veja **dois ou três** e pare: eles repetem a mesma coisa. Depois leia o paper da seção "Leituras".

| | Vídeo | Canal | Duração |
|---|---|---|---|
| ⭐ | [GEO, AEO e SEO na Prática: Faça Sua Marca Aparecer no ChatGPT, Gemini e Claude](https://www.youtube.com/watch?v=o4RCOXExFSg) (em português) | Ariel Alexandre - AI builder | 14:07 |
| ⭐ | [What Is GEO? Generative Engine Optimization Explained (2026): 5 Key Principles](https://www.youtube.com/watch?v=Oq7qV4_5W-A) | Alex Moreau, AI for Ads & SEO-GEO | 7:03 |
|  | [What Is Generative Engine Optimization (GEO)? A Beginner's Guide](https://www.youtube.com/watch?v=p0pf2M1t5xI) | Found in AI Podcast, Cassie Clark Marketing | 12:09 |
|  | [Generative Engine Optimization (GEO) Explained](https://www.youtube.com/watch?v=5F0_IFIVeWs) | Howseen AI | 1:56 |

**Perguntas para fazer enquanto assiste:** o que o vídeo afirma como fato e qual a evidência? O que é só opinião do autor? O que muda se a empresa for B2B de tecnologia, em vez de varejo ou saúde?

## 6. Como escrever um artigo de GEO

É a parte que mais pesa nos seus 10 artigos.

| | Vídeo | Canal | Duração | Observação |
|---|---|---|---|---|
| ⭐ | [How to Get Your Brand Cited by ChatGPT - The GEO Playbook That Actually Works](https://www.youtube.com/watch?v=3wpzzM9DiT0) | Anand Iyer | 16:58 | Método geral. |
| ⭐ | [AEO/GEO Citation Game Plan in 2026 – Pillar 2: Structured Content for AI Search Visibility](https://www.youtube.com/watch?v=lA8Jo3yIfkk) | Kevin C. Roy, GreenBananaSEO | 4:19 | Estrutura de conteúdo para ser lido e citado por IA. |
|  | [GEO Checklist: 5 Rules to Get Your Business Cited in AI Answers](https://www.youtube.com/watch?v=X7TqNxVjW-4) | WKND | 9:40 | Checklist. |
|  | [How to Get Cited by Perplexity AI: Optimizing for AI Search (GEO Course)](https://www.youtube.com/watch?v=_R47uiMef7Y) | FreeAcademy AI | 7:33 | Foco em um mecanismo de busca por IA. |
|  | [Optimize Existing Blog Posts for GEO (Without Rewriting Everything)](https://www.youtube.com/watch?v=iypzmWZf2yU) | Rebecca Grace Designs | 19:46 | Para o caso de atualizar artigo antigo. |
|  | [How to do GEO as a Beginner (full AI SEO Course)](https://www.youtube.com/watch?v=dXhUg9Eu0xM) | Vasco's SEO Tips | 17:27 | Curso introdutório. |

**O que observar:** o que cada autor manda fazer **dentro do texto** (início da resposta, títulos, listas, dados, fontes, perguntas e respostas), e o que é só "técnica de SEO" sem relação com texto. **Anote o que se repete em vários vídeos:** é o que você pode testar com mais segurança.

## 7. Como achar as perguntas do público (mapa de perguntas)

Seu `06-mapa-de-perguntas.md` não é lista de palavras-chave. É o que as pessoas **perguntam a uma IA**.

| | Vídeo | Canal | Duração | Observação |
|---|---|---|---|---|
| ⭐ | [How to Find the Exact Prompts Your Buyers Are Using in ChatGPT Right Now](https://www.youtube.com/watch?v=QqNud-LnKac) | Infrasity | 3:09 | Curto; ponto de partida. |
|  | [How To Find Prompts Searched By Customers & ChatGPT Volumes](https://www.youtube.com/watch?v=6zeFuJ19UNM) | Alex COLLINSEO | 6:31 | Desconfie de qualquer "volume exato de prompts": pergunte de onde o dado vem. |
|  | [GEO Keyword Research and Tracking AI Search Results For Your Main Keywords](https://www.youtube.com/watch?v=dtlZTULGX4A) | Surfside PPC | 12:48 | Pesquisa de palavra-chave adaptada a GEO. |
|  | [Webinar: Why Your GEO Strategy is Probably Wrong (And What Actually Works)](https://www.youtube.com/watch?v=l_vv9q6MxwU) | The Grow and Convert Marketing Show | 31:22 | **Visão crítica.** Pelo resumo, argumenta que práticas populares de GEO não funcionam sozinhas. Uma opinião a ser pesada, não um dado. |

## 8. Tom de voz e regras de escrita

| | Vídeo | Canal | Duração |
|---|---|---|---|
|  | [Como fazer o Claude escrever no seu tom de voz (sem prompt perfeito)](https://www.youtube.com/shorts/vOg7Q3vAmwc) (em português) | Tera | 0:45 |

Vídeo bem curto. A ideia que ele traz (dar à IA textos reais como referência de voz) é o que vai no seu `04-voz-e-regras.md`.

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
