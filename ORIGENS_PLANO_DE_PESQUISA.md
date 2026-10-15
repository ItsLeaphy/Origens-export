# ORIGENS | Plano diretor da pesquisa aprofundada

**Versão:** 1.0  
**Data:** 14 de outubro de 2026  
**Estado:** plano de pesquisa; a investigação de gabinete específica desta fase ainda precisa ser executada. Nenhuma hipótese comercial está validada.

## 1. Identidade e fronteiras do projeto

### Nomenclatura fixa

- **ORI:** antigo projeto chamado Origens. Projeto separado.
- **ORI Cantina:** antigo Origens Cantina, a ideia de aplicativo de cantina escolar. A pesquisa antiga pode fornecer lições, mas não determina a estratégia deste projeto.
- **ORIGENS:** projeto atual. Marketplace de busca de produtos que agrega ofertas de lojas locais/regionais.

A pesquisa ativa deste documento é exclusivamente sobre o **ORIGENS**. Os outros dois nomes aparecem apenas para manter o histórico organizado.

### Tese de trabalho

Uma pessoa quer comprar um produto específico. Em vez de pesquisar lojas uma a uma ou depender exclusivamente de marketplaces nacionais, ela pesquisa o próprio produto no ORIGENS. A plataforma apresenta ofertas de comerciantes da região, permitindo comparar preço, localização, disponibilidade e forma/prazo de aquisição. A primeira versão investigada prioriza compra ou reserva com retirada presencial. Entrega local rápida poderá ser incorporada futuramente, caso haja densidade de pedidos e economia logística compatíveis.

**Formulação curta:** “Pesquise o produto. Descubra quais lojas da sua região realmente o têm disponível. Compare e compre para retirar; futuramente, receba em casa rapidamente.”

Essa formulação é uma hipótese de produto, não uma alegação de que o modelo já funciona.

### O que está dentro do escopo

- Produtos físicos comercializados por lojas locais e regionais.
- Busca iniciada pelo produto, marca, modelo, tipo ou necessidade, e não pelo nome da loja.
- Agregação e comparação de ofertas de múltiplos lojistas.
- Disponibilidade local suficientemente confiável, com atualização e indicação de confiança/recência.
- Compra ou reserva para retirada como fluxo inicial a investigar.
- Caminhos técnicos e comerciais para adicionar entrega local rápida futuramente.
- Modelos de negócio, aquisição de oferta/demanda, catalogação, normalização de produtos, atualização de estoque, pagamentos e economia unitária.

### O que está fora do escopo central desta fase

- Transformar o produto em marketplace de serviços, agenda genérica, classificados generalistas ou “app de tudo”.
- Tratar escolas, campus ou instituições educacionais como mercado-alvo padrão.
- Presumir que alimentos são a categoria inicial por causa do histórico ORI Cantina.
- Construir aplicativo, escolher stack ou especificar código antes de responder às perguntas comerciais e operacionais fundamentais.
- Tratar entrega em até duas horas como promessa pronta. O prazo é uma hipótese futura que depende de cobertura, parceiros, densidade e custo.
- Concluir que a proposta é diferenciada só por ser local.

As escolas, universidades, bairros, redes de comerciantes e outras comunidades podem ser estudadas como canais ou unidades comerciais candidatas, mas nenhum deles recebe prioridade por padrão.

## 2. Pergunta estratégica central

**Conseguimos tornar pesquisável a oferta real das lojas de uma região para que uma pessoa encontre, compare e compre um produto localmente com menos esforço e mais rapidez do que usando os canais atuais, e depois oferecer entrega rápida com economia sustentável?**

A pesquisa deve manter separados dois problemas:

1. **Descoberta e compra local com retirada:** uma hipótese que pode ser testada sem construir rede própria de entrega.
2. **Entrega local rápida:** uma hipótese adicional, operacional e economicamente mais exigente, que só deve ser aprofundada como modelo executável depois de compreender densidade de oferta e procura.

## 3. Princípios de pesquisa e disciplina de evidência

1. **Não sair da tese:** toda pesquisa precisa responder a uma pergunta sobre busca de produtos, inventário local, compra/retirada ou entrega local futura. Serviços só entram se forem diretamente necessários à tese, e não como expansão abstrata.
2. **Não proteger a ideia:** concorrentes, custos ou limitações que enfraqueçam a tese devem ser apresentados sem suavização.
3. **Não confundir presença online com demanda:** número de comerciantes, população conectada ou uso de e-commerce não prova intenção de comprar no ORIGENS.
4. **Separar níveis de evidência:**
   - **Fato confirmado:** fonte primária/autoridade ou documentação verificável.
   - **Alegação comercial:** algo afirmado por uma empresa sobre si mesma.
   - **Evidência indireta:** pesquisa relacionada, mas não específica da tese.
   - **Inferência:** conclusão analítica derivada de fatos/evidências.
   - **Hipótese não validada:** premissa que exige experimento ou dado ainda inexistente.
5. **Toda alegação atual ou competitiva precisa de fonte e data.** Priorizar páginas oficiais, documentação, dados públicos, preços atuais e relatos independentes. Comparar datas e geografia.
6. **Não inventar tração, números, entrevistas, taxas ou disponibilidade de produtos.** Quando o dado não existir publicamente, registrar a lacuna e definir como obtê-lo.
7. **Cada módulo termina com uma decisão ou questão pendente clara.** Não repetir pesquisa já feita, salvo quando a tese ou evidência mudar.
8. **A pesquisa de gabinete não prova a viabilidade comercial.** Seu objetivo é eliminar falhas óbvias, fortalecer o modelo e deixar os experimentos de campo bem desenhados.

## 4. Arquitetura da pesquisa: módulos e dependências

A sequência abaixo é deliberada. Não começar por arquitetura de software ou por entrega. Primeiro precisamos entender o trabalho que o usuário tenta realizar, as ofertas que deve encontrar e a possibilidade real de reunir inventário local.

### Módulo 1 — Definição rigorosa da experiência e das missões de compra

**Pergunta:** em que situações alguém escolhe procurar um produto localmente em vez de comprar num marketplace nacional, pesquisar no Google/Maps ou consultar WhatsApp/Instagram?

Pesquisar:
- Compras urgentes versus planejadas; “preciso hoje” versus “posso esperar”.
- Produtos que o consumidor tende a pesquisar por nome/modelo, por categoria ou por necessidade.
- Alternativas atuais e etapas da jornada: busca, comparação, confirmação de estoque, compra, retirada.
- O que o consumidor considera melhor: preço, disponibilidade agora, distância, rapidez, confiança, variedade ou facilidade.
- Comportamentos de consulta local que terminam em compra presencial.

**Entregável:** mapa de missões de compra, alternativas atuais, barreiras de troca e hipóteses explícitas sobre quando ORIGENS seria a primeira escolha.

**Não aceitar como resposta:** “as pessoas querem conveniência” sem exemplos, fontes e distinção entre compras urgentes e planejadas.

### Módulo 2 — Categorias de produto e escolha do primeiro território competitivo

**Pergunta:** quais categorias oferecem a combinação mais promissora de procura local, urgência, estoque em lojas físicas e capacidade de agregação?

Comparar candidatos sem escolher por intuição: acessórios de tecnologia, eletrônicos e periféricos, material escolar/escritório, papelaria/impressão com produtos definidos, utilidades domésticas, ferramentas/peças, cosméticos, presentes, brinquedos, produtos para pets e outros encontrados nas evidências. Alimentação entra apenas se competir bem com essas alternativas, não por herança do projeto anterior.

Critérios: demanda e frequência prováveis, urgência, ticket, margem do lojista, variedade por loja, padronização do produto, identificadores/SKU, facilidade de confirmar estoque, concorrência online, dispersão de oferta, taxa provável de recompra, logística e devoluções.

**Entregável:** matriz comparativa com 3–5 categorias candidatas e critérios explícitos para escolher uma categoria-âncora. A primeira seleção será uma hipótese de pesquisa, não uma escolha final sem campo.

### Módulo 3 — Concorrentes diretos, modelos adjacentes e falhas do mercado

**Pergunta:** quais empresas já agregam produtos de lojas locais ou resolvem a mesma missão de compra, e por que o usuário escolheria ORIGENS?

A investigação deve incluir:
- Plataformas hiperlocais e de descoberta por produto, inclusive Tem Aí, GoDelve e iniciativas regionais descobertas em busca aprofundada.
- Integração de inventário local em Google Search/Maps e Google Merchant Center, com atenção à disponibilidade real no Brasil.
- Marketplaces nacionais (Amazon, Shopee, Mercado Livre), serviços de entrega rápida (Amazon Now, Rappi Turbo e similares) e opções de retirada/click-and-collect.
- Plataformas de catálogo, PDV, ERP e e-commerce usadas pelos lojistas, que podem ser substitutos ou fontes de integração.
- Casos internacionais de local inventory discovery, click-and-collect, marketplace de varejo local e modelos que cresceram, mudaram de modelo ou encerraram.

Para cada caso, registrar: mercado e geografia; promessa; como a oferta/estoque entra na plataforma; compra, retirada e entrega; receita; escala/trajetória apenas quando verificável; aquisição de lojistas e compradores; limitações; proximidade real da tese ORIGENS.

**Entregável:** mapa competitivo por mecanismo, não apenas por nomes, seguido de uma conclusão sobre espaços pouco atendidos e ameaças.

### Módulo 4 — O problema mais difícil: inventário, catálogo e disponibilidade confiável

**Pergunta:** como agregar estoque de muitas lojas sem exigir que cada comerciante administre manualmente centenas ou milhares de produtos?

Investigar os caminhos possíveis:
- Cadastro manual limitado, planilha/CSV e importação em lote.
- Catálogo digital já existente do lojista.
- Integração com PDV, ERP, e-commerce ou plataformas de estoque.
- Fornecedores de dados de produtos, GTIN/EAN/ISBN, SKU e normalização de marca/modelo/variante.
- Leitura de catálogos, APIs disponíveis, sincronização e atualização programada, sempre respeitando contratos, direitos e termos de uso.
- Estoque por loja versus estoque centralizado; quantidade exata versus estado de disponibilidade; reserva temporária.
- Indicação de recência e confiança: “atualizado há X”, “confirmado pela loja”, “estoque sincronizado” ou confirmação antes de concluir.

Medir o que as fontes permitem sobre custo, cobertura, qualidade e exigência de trabalho. Não presumir que todo lojista tenha PDV, API, código de barras ou estoque digital.

**Entregável:** matriz de métodos de inventário com custo/complexidade, cobertura esperada, esforço para o vendedor, risco de dado desatualizado e rota inicial plausível.

**Portão de decisão:** se não existir um caminho operacional plausível para oferecer inventário confiável com esforço controlável, essa é uma possível razão para rever a tese antes de falar em arquitetura.

### Módulo 5 — Proposta de valor e experiência de busca

**Pergunta:** que resultado deve fazer o consumidor pensar em ORIGENS primeiro quando deseja comprar um produto localmente?

Comparar propostas específicas, por exemplo:
- “Encontre agora quem tem este produto por perto.”
- “Compare preço e disponibilidade em várias lojas locais sem mandar dez mensagens.”
- “Compre perto, retire hoje e evite esperar a entrega do e-commerce.”

Testar cada formulação contra alternativas e evidências. A marcação “disponível” precisa ter um significado operacional verificável.

Investigar a jornada ideal: pesquisa textual, correspondência de produto, marca/modelo/variante, lista de ofertas por loja, preço total, distância, horário, recência do estoque, retirada, pedido/reserva e solução quando a disponibilidade muda. Identificar o que deve aparecer antes de clicar e que informação é indispensável para comparar ofertas corretamente.

**Entregável:** promessa principal, promessa secundária, fluxo de compra e princípios de experiência. Não produzir uma lista genérica de funcionalidades sem ligar cada uma a uma barreira observada.

### Módulo 6 — Modelo de negócio, unit economics e captura de valor

**Pergunta:** como a plataforma gera receita sem inviabilizar a participação do lojista nem tornar a compra pior para o consumidor?

Comparar, especialmente para varejo físico e busca por produto:
- Comissão sobre venda transacionada.
- Taxa fixa por pedido, quando o ticket comportar.
- Leads qualificados/encaminhamento, quando a compra continuar fora do app.
- Assinatura ou serviço pago para lojistas, caso exista valor operacional independente da demanda.
- Destaques patrocinados, somente se houver tráfego e intenção de compra suficientes.
- Modelo híbrido com distinção clara entre serviços pagos e venda intermediada.

Usar tabela atual de PSP/marketplace e separar taxa publicada de taxa negociada. Modelar ticket e comissão por categoria, custo de pagamento, estornos, fraude, suporte, tributação, aquisição dos dois lados, esforço de atualizar estoque e margem do vendedor. Mostrar cenários e sensibilidade sem aparência de precisão indevida.

**Entregável:** planilha ou tabela reproduzível com contribuição por pedido, contribuição mensal por unidade comercial e volume aproximado de equilíbrio. Toda premissa não observada deve estar marcada.

### Módulo 7 — Entrada no mercado e liquidez da oferta/demanda

**Pergunta:** qual é a menor unidade de mercado que pode oferecer variedade útil de produtos e compradores suficientes para transações recorrentes?

Comparar cidade inteira, zona/bairro, corredor comercial, rede de lojas, categoria e canal de compradores. Escolher por densidade do inventário relevante e aquisição possível, não por conveniência narrativa.

Investigar como atrair lojas sem pedir que cadastrem o catálogo todo, como gerar procura de consumidores, como medir a primeira compra, como incentivar recompra e como evitar que ORIGENS vire uma vitrine vazia.

**Entregável:** 2–3 hipóteses de entrada ranqueadas, com critérios, riscos, custo inicial provável e experimento adequado para cada uma.

### Módulo 8 — Entrega rápida como expansão, não como pressuposto do MVP

**Pergunta:** quando e como a entrega local adicionaria valor e poderia ser economicamente sustentável?

Comparar cenários de entrega por lojista, courier terceirizado, parceiros sob demanda e operação própria somente como referência. Investigar custo por corrida, tempo de coleta, distâncias, densidade de pedidos, remuneração do entregador, tentativas de entrega, retorno e responsabilidade por perdas. Comparar disposição do consumidor para pagar frete com o valor da comissão e o ticket.

Definir o que “entrega em duas horas” significaria operacionalmente: área coberta, horários, percentil de cumprimento, disponibilidade de produto e o que acontece em atrasos. Não prometer esse SLA até haver dados reais.

**Entregável:** decisão condicional sobre entrega: não investigar agora além dos benchmarks; fazer um piloto logístico futuro; ou abandonar o prazo de poucas horas caso a economia não feche.

### Módulo 9 — Operação, confiança e riscos diretamente ligados ao produto

**Pergunta:** quais controles são necessários para manter promessa confiável?

Cobrir apenas o que afeta a tese: produto anunciado que não existe, preço errado, variações incompatíveis, retirada perdida, duplicidade de resgate, devolução, privacidade, proteção de dados, responsabilidades do marketplace e pagamentos. Revisar requisitos legais atuais relevantes para venda de bens e operar com fontes oficiais.

**Entregável:** matriz de riscos e controles mínimos antes do piloto e antes do checkout integrado. Não deixar que esta etapa se transforme numa revisão genérica de toda legislação de startups.

### Módulo 10 — Viabilidade de dados e arquitetura conceitual

**Pergunta:** qual estrutura mínima de produto sustenta a experiência sem criar abstração prematura?

A pesquisa precisa avaliar, em nível conceitual:
- Produto canônico (o item pesquisável) versus oferta do lojista (preço, estoque, condição e localização).
- Marca, modelo, variante e identificadores.
- Unidade comercial/loja e múltiplas localizações de um lojista.
- Disponibilidade e data/hora da última confirmação.
- Pedido/reserva, estado de pagamento e resgate.
- PWA/web mobile primeiro versus aplicativo nativo.
- Importação de catálogo e mecanismos de atualização.
- Busca textual, sinônimos, erros de digitação e comparação entre produtos idênticos.

**Entregável:** modelo conceitual e fronteira de MVP. Não escrever especificação de implementação completa até concluir mercado, proposta e inventário.

### Módulo 11 — Caso de negócio integrado e condição de “paper-ready”

**Pergunta:** a ideia está coerente o suficiente no papel para que a próxima fase possa ser validação de campo, sem ainda afirmar que foi validada?

Consolidar os módulos em uma tese única, com evidências e perguntas ainda abertas.

**O documento de pesquisa só estará pronto para campo quando contiver:**
1. Uma missão de compra inicial claramente definida.
2. As alternativas mais relevantes e o diferencial pretendido.
3. Duas ou três categorias/territórios candidatos, comparados e ordenados.
4. Um caminho plausível para agregar e manter inventário local com esforço estimado.
5. Uma jornada de busca e compra compreensível.
6. Um modelo de receita candidato e economia unitária com premissas rastreáveis.
7. Um plano condicional para logística futura, sem promessas não testadas.
8. Os riscos fatais identificados e as evidências que poderiam invalidar a tese.
9. Um protocolo de validação de campo específico para ORIGENS.
10. Uma decisão recomendada, grau de confiança e critérios explícitos para mudar de ideia.

### Módulo 12 — Validação de campo

Esta fase só começa depois do “paper-ready”. Não faz parte da conclusão da pesquisa de gabinete, porque depende de compradores, fornecedores, pedidos reais e, futuramente, ensaios logísticos.

A sequência provável será: entrevistas; catálogo concierge/manual; compra e retirada; teste de disponibilidade; teste de disposição a pagar; piloto de aquisição e repetição; só então desenvolvimento controlado.

---

## 5. Como vamos trabalhar a partir daqui

Para não repetir o desvio de foco, toda continuação precisa seguir este protocolo:

1. **Uma mensagem = um módulo ou submódulo delimitado.** Nada de responder com um resumo genérico da ideia quando o objetivo é investigar algo específico.
2. **Pesquisar a tese local-product-discovery.** Se a informação não estiver ligada à busca de produtos, inventário, compra/retirada, monetização dessa transação ou entrega rápida futura, fica fora do foco.
3. **Atualizar o documento mestre.** Cada etapa registra pergunta, fontes, descobertas, grau de confiança, contradições, hipótese que permanece aberta e o próximo módulo.
4. **Não repetir por inércia as doze etapas anteriores.** O primeiro ciclo de pesquisa está arquivado como histórico; esta sequência é uma fase aprofundada nova e focada no ORIGENS.
5. **Não avançar para execução, equipe, prazo de apresentação ou código durante esta fase**, exceto se o usuário mudar explicitamente essa prioridade. O objetivo atual é aperfeiçoar a tese no papel e deixá-la pronta para validação real.
6. **Não prometer “provar que a ideia é boa” apenas com pesquisa de gabinete.** O papel pode revelar concorrência, inviabilidade, custos escondidos e um modelo plausível; validade comercial exige comportamento real.

## 6. Ordem exata das próximas pesquisas

A ordem inicial recomendada é:

1. **Módulo 1: missões de compra e comportamento do consumidor.** Identificar o tipo de necessidade que faz a busca local ter vantagem sobre marketplace nacional e canais atuais.
2. **Módulo 2: seleção comparativa de categorias.** Usar os resultados do módulo 1 para comparar categorias pela disponibilidade local, urgência, densidade, ticket e compatibilidade do produto.
3. **Módulo 3: concorrência e análogos específicos.** Aprofundar o mapa em torno de descoberta de inventário local, click-and-collect e modelos que tentaram agregar estoque de varejistas independentes.
4. **Módulo 4: arquitetura de inventário e sincronização.** Testar a viabilidade de construir uma busca confiável sem exigir entrada manual de todos os SKUs.
5. **Módulo 5: proposta de valor e experiência de busca.** Consolidar a hipótese com base no que descobrimos sobre compra, categorias e concorrentes.
6. **Módulo 6: economia e monetização.** Modelar o fluxo escolhido, comparando o custo da infraestrutura de inventário, pagamento e futura logística.
7. **Módulo 7: mercado inicial e liquidez.** Escolher território e canal de aquisição com evidências, não por conveniência.
8. **Módulos 8–10: entrega, riscos e arquitetura conceitual.** Condicionados ao que sair dos módulos anteriores.
9. **Módulo 11: síntese “paper-ready”.** Fechar a investigação e recomendar qual hipótese merece validação real.
10. **Módulo 12: campo**, em etapa separada, depois da ideia estar suficientemente robusta no papel.

## 7. Estado atualizado e próxima ação

A pesquisa anterior continua útil para concorrentes, cenários de comissão, obrigações legais e riscos operacionais. Mas a definição central mudou o suficiente para justificar esta sequência nova. Não vamos tratar a antiga conclusão “etapa 12 de 12” como encerramento definitivo da investigação: ela encerrou o ciclo genérico anterior, não o desenvolvimento da tese específica do ORIGENS.

**Próxima ação recomendada: iniciar o Módulo 1, pesquisando profundamente o comportamento de quem precisa comprar um produto específico e as circunstâncias em que procura localmente em vez de comprar na Shopee, Amazon, Mercado Livre ou outro canal.** Essa pesquisa deverá produzir um mapa das missões de compra, das categorias candidatas e das condições em que disponibilidade local e velocidade são vantagens decisivas.

O arquivo `META_PESQUISA_PLATAFORMA.md` permanece como documento mestre e deverá ser atualizado a cada módulo. Esta estrutura passa a ser o plano ativo para o ORIGENS.
