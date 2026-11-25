# Memorix

> Empresa fictícia. Dossiê enviado pelo cliente à agência, com dados vigentes em 2026-11-01.

## Em uma frase

A Memorix conecta as ferramentas onde uma empresa guarda o que sabe (Slack, Google Drive, Notion, HubSpot e outras), organiza esse conhecimento e o entrega, com a fonte indicada, a pessoas e a agentes de IA que precisam dele para trabalhar.

## A empresa

| Item | Dado |
|---|---|
| Fundação | 2024 |
| Sede | Curitiba-PR (time híbrido) |
| Tamanho | 22 pessoas: 8 engenharia, 5 produto e design, 4 comercial, 3 sucesso do cliente, 2 operações |
| Clientes pagantes | 14 (agências, software B2B e consultorias) |
| Clientes que autorizam citar o nome | **Nenhum.** Todos pediram sigilo por enquanto. |
| Site | memorix.example (fictício; não existe site para consultar) |
| Idioma de atendimento | Português do Brasil |

## O que vende

A Memorix chama o produto de **Company Brain**: uma camada que lê as ferramentas da empresa, relaciona pessoas, clientes, projetos e decisões, e responde perguntas ou alimenta agentes de IA **citando de onde veio cada informação**.

### Como funciona (segundo o cliente)

1. **Conectores.** Lê Slack, Google Drive, Notion, HubSpot, Gmail e Google Calendar. Mais conectores estão no roteiro de produto, sem data.
2. **Mapa de contexto.** Cria uma representação ligando documentos, conversas, pessoas, clientes e decisões entre si.
3. **Três jeitos de usar:**
   - **Chat interno:** o funcionário pergunta e recebe resposta com link para a fonte.
   - **API:** sistemas da própria empresa consultam o Brain.
   - **Servidor MCP:** agentes de IA (como Claude e agentes próprios do cliente) consultam o Brain como ferramenta.
4. **Permissões herdadas.** Cada pessoa só vê o que já podia ver na ferramenta de origem.
5. **Sempre cita a fonte.** Toda resposta traz os documentos usados.

### Planos e valores

| Plano | Preço | Inclui |
|---|---|---|
| Equipe | R$ 2.900 por mês | Até 25 usuários, até 5 conectores, chat e API |
| Empresa | R$ 9.800 por mês | Até 150 usuários, conectores ilimitados, chat, API, MCP e login único (SSO) |
| Enterprise | Sob consulta | Mais de 150 usuários, contrato e ambiente dedicados |

- **Implantação:** de 2 a 4 semanas, conforme o número de conectores.
- **Piloto de 30 dias:** R$ 1.500, abatidos do primeiro mês se o cliente contratar.
- Valores válidos em 2026-11-01, sem impostos. **Qualquer artigo com preço precisa informar a data.**

### Segurança e dados

- Dados hospedados em nuvem, na região de São Paulo.
- Criptografia em trânsito e em repouso.
- Contrato de operador de dados (LGPD) e DPA disponíveis sob pedido.
- A Memorix **não usa dados dos clientes para treinar modelos próprios**.
- Certificação **SOC 2: em preparação, ainda não concluída**.

## O que a Memorix não é e não faz

- **Não substitui** CRM, ERP, wiki nem ferramenta de gestão de projetos. Ela lê essas ferramentas; não as troca.
- **Não escreve de volta** nas ferramentas conectadas. Na versão atual é somente leitura.
- **Não é chatbot de atendimento ao cliente final.** É para uso interno e para agentes da própria empresa.
- **Não treina um modelo próprio** com os dados do cliente.
- **Não busca na internet.** Só responde com o que está nas ferramentas conectadas.
- **Não tem aplicativo de celular.**
- **Não garante que a resposta esteja correta.** Se o documento de origem está errado ou desatualizado, a resposta herda o erro, e por isso mostra a fonte.

## Para quem vende

| Quem | Papel na compra | Dor típica |
|---|---|---|
| Líder de operações (COO, Head de Ops) | Decide | Conhecimento preso em pessoas; onboarding lento |
| RevOps e vendas | Usa e influencia | Informação de cliente espalhada em várias ferramentas |
| Sucesso do cliente (CS) | Usa e influencia | Responder cliente sem caçar histórico |
| TI e segurança (CTO, Head de TI) | **Aprova ou veta** | Permissões, privacidade, onde ficam os dados |
| Quem monta agentes de IA na empresa | Usa | Agente "sem memória da empresa" erra e inventa |

- **Tamanho de empresa:** de 50 a 500 pessoas.
- **Maturidade:** o cliente-alvo já usa ferramentas de IA, mas sente que elas "não conhecem a empresa".

## Concorrência que o cliente cita

Nomes que o cliente mencionou na reunião. **Não é análise, e o cliente pode estar errado sobre o que cada um faz.** Confira antes de comparar.

- Glean
- Notion AI
- Guru
- Strattum (empresa brasileira que também usa o termo "Company Brain")

O cliente também diz que "o maior concorrente é a empresa não fazer nada e continuar pedindo contexto pelo Slack".

## O que o cliente quer da agência

- Que, quando alguém perguntar a uma IA **o que é um Company Brain**, como funciona ou como escolher um, a Memorix apareça como fonte e, quando fizer sentido, como opção recomendada.
- Ser lida como **autoridade em explicar a categoria**, e não só como vendedora de uma ferramenta.
- Contrato de 6 meses. O cliente mede sucesso por aparecer em respostas de IA e por pedidos de demonstração vindos de leitores dos artigos.

## Regras do cliente

- **Tom:** direto e técnico, sem jargão desnecessário. Quem lê é gente de negócio, não só engenheiro.
- **Proibido:** dizer que a IA "sabe tudo" ou "elimina o trabalho"; citar nome de cliente; prometer resultado numérico (horas economizadas, aumento de vendas) sem fonte; prometer a certificação SOC 2 como concluída.
- **Obrigatório:** quando falar de preço, informar a data; quando falar de segurança, não afirmar o que não consta no dossiê.
- **Assinatura:** artigos assinados pela "equipe Memorix". Não inventar autor.
- **Comparações:** podem citar concorrentes pelo nome, desde que com fatos conferidos em fonte pública e com a data da consulta.

## Ainda não confirmado

> **Cada item abaixo é hipótese.** Trate como tal no seu Brain e nos artigos.

- Se o servidor MCP funciona com o **ChatGPT**. Com Claude e agentes próprios sim; com o ChatGPT estão testando.
- Se o conector do **Microsoft Teams** entra no segundo semestre de 2027 (o cliente disse "provavelmente").
- Quantos documentos o Brain consegue indexar por cliente (o cliente falou em "centenas de milhares", sem número).
- Tempo de resposta médio do chat (o cliente disse "poucos segundos", sem medição).
- Se existe versão em inglês do produto.
- Se há desconto para contrato anual.

## O que você precisa pesquisar

O dossiê **não ensina** o que é a categoria nem o público. Fica por sua conta:

- O que é, de fato, um "Company Brain"? Como difere de busca corporativa, wiki, chatbot interno, RAG e "agente de IA"?
- Quais perguntas o público faz sobre esse assunto, e em que fase da decisão?
- O que os produtos citados pelo cliente realmente fazem (com fonte e data).
- Quais termos o mercado usa para a mesma coisa ("context layer", "memória corporativa", "knowledge graph" etc.) e como diferem.
- Que objeções um líder de TI levanta antes de conectar ferramentas da empresa a uma IA.
