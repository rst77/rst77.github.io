+++
authors = ["Renato Teixeira"]
title = "Evidência é necessária. Na engenharia de software, também é difícil."
date = "2026-05-04"
description = "Reflexão crítica sobre Engenharia de Software Baseada em Evidências e o desafio de aplicar pesquisas científicas em decisões tecnológicas reais."
tags = [
    "LegacyModernization",
    "SoftwareArchitecture",
    "TechnologyDecisionMaking",
    "EvidenceBasedSoftwareEngineering",
    "SoftwareEngineering"
]
categories = [
    "Modernization",
]
series = ["Modernization"]
+++

![Conceito de Engenharia de Software Baseada em Evidências](/images/202605/ev.png)

No artigo anterior, defendi que a engenharia de software normalizou decisões importantes tomadas sobre bases frágeis demais. **Hype, pressão de mercado, convicção pessoal, linguagem sofisticada e ansiedade por adoção** ainda ocupam espaço demais em um campo que gosta de se apresentar como engenharia. Mas existe uma resposta fácil — e perigosa — para essa crítica: “então basta seguir a evidência”. Seria ótimo se fosse tão simples. Não é. E talvez uma das maiores maturidades que possamos desenvolver em engenharia de software seja justamente reconhecer essa tensão: **precisamos de mais evidência, mas produzir, interpretar e aplicar evidência em software é muito mais difícil do que normalmente admitimos**.

Essa dificuldade não torna a evidência menos importante. **Torna a nossa responsabilidade maior.** A ideia de uma engenharia de software baseada em evidências nasce de uma analogia com a medicina baseada em evidências. Na medicina, um médico não decide apenas com base em intuição: ele deve combinar a melhor evidência disponível, sua experiência clínica e os valores e circunstâncias do paciente. Esse ponto é fundamental, porque o médico não se relaciona com a evidência de forma abstrata. Ele está diante de um paciente específico, com sintomas específicos, histórico específico, riscos específicos e valores próprios. A evidência importa, mas precisa ser interpretada à luz da realidade daquele paciente.

Quando um médico conversa com outro médico, eles podem discutir estudos, tratamentos, efeitos, riscos e protocolos. Mas a decisão clínica não termina na conversa entre especialistas. Ela volta ao paciente. Em software, a situação é menos limpa. Quando decidimos adotar uma tecnologia, mudar uma arquitetura, introduzir um método de desenvolvimento ou modernizar um sistema legado, raramente existe um “paciente” único diante de nós. **O paciente está distribuído:** aparece nos desenvolvedores que terão que manter a solução, nos operadores que responderão pelos incidentes, nos clientes que sofrerão indisponibilidade, nas áreas de negócio que dependem do sistema, nos executivos que assumem o risco, nos orçamentos que serão consumidos e nos sistemas futuros que herdarão as consequências da decisão.

Na medicina, o médico integra evidência à condição do paciente. Na engenharia de software, precisamos integrar evidência a um ecossistema de stakeholders, restrições, interesses, dependências e riscos. E isso muda tudo. Porque, se o paciente é distribuído, **o risco também é distribuído. O custo é distribuído. A responsabilidade é distribuída. As consequências são distribuídas.** Por isso, em software, não basta perguntar: **“essa técnica funciona?”** A pergunta real costuma ser mais desconfortável: **“funciona para quem, em qual contexto, com qual equipe, sob quais restrições, durante quanto tempo e com quais efeitos colaterais?”** Essa é uma pergunta muito mais difícil — e muito mais honesta.

## O primeiro problema: software depende demais de habilidade humana

Uma das dificuldades centrais da evidência em engenharia de software é que métodos, práticas e ferramentas raramente operam sozinhos. **Eles dependem de pessoas.** E pessoas não são variáveis simples. Pense em práticas como code review, TDD, pair programming, DevOps, arquitetura de microsserviços, observabilidade, refatoração, engenharia de plataformas ou modernização incremental. Nenhuma delas “funciona” no abstrato. Elas funcionam — ou falham — quando executadas por pessoas específicas, com níveis específicos de experiência, em equipes específicas, dentro de culturas específicas, sob pressões específicas.

Isso significa que a mesma prática pode gerar resultados muito diferentes em contextos diferentes. Um time maduro pode usar microsserviços para aumentar autonomia, escalabilidade e velocidade de evolução. Outro time pode usar microsserviços para criar um monólito distribuído, mais caro, mais frágil e mais difícil de operar. **A prática é a mesma. O resultado não é.** O problema não está apenas na técnica. Está na combinação entre técnica, habilidade, contexto e execução. É aqui que muita discussão técnica se torna ingênua: perguntamos se determinada prática “é boa” ou “é ruim”, como se estivéssemos avaliando uma substância química com propriedades estáveis.

Mas práticas de engenharia de software não se comportam assim. **Uma prática pode ser poderosa em mãos maduras e perigosa em mãos despreparadas.** Pode ser adequada em uma organização e desastrosa em outra. Pode resolver um problema local e criar um problema sistêmico. A habilidade humana não é detalhe; é parte do fenômeno. E isso torna a evidência mais difícil de produzir. Também torna a certeza mais suspeita.

## O segundo problema: o ciclo de vida esconde as consequências

O segundo grande desafio é que, em software, muitas decisões só revelam suas consequências reais ao longo do tempo. Uma arquitetura pode parecer elegante no início. Um framework pode acelerar os primeiros meses. Um processo pode melhorar indicadores locais. Uma migração pode produzir ganhos imediatos. Uma ferramenta pode impressionar em uma prova de conceito. Mas **software não vive em prova de conceito**. Software vive em manutenção, integração, incidente, mudança de requisito, troca de equipe, orçamento reduzido, auditoria e operação contínua. É aí que muitas decisões mostram seu verdadeiro custo.

Esse é um ponto crítico: **uma técnica pode produzir um bom resultado imediato e ainda assim piorar o resultado final do sistema ao longo do ciclo de vida**. O contrário também pode acontecer: uma decisão pode parecer mais lenta no início, mas preservar melhor a capacidade de evolução futura. Essa distância entre efeito imediato e consequência de longo prazo torna a evidência em software especialmente difícil. Como isolar o impacto de uma decisão arquitetural tomada hoje sobre a confiabilidade de um sistema daqui a dois anos? Como saber se o sucesso veio da ferramenta, da equipe, do contexto, da liderança, do investimento, da maturidade operacional ou simplesmente de uma combinação feliz de fatores?

Em software, causalidade raramente aparece limpa. **Ela vem misturada.** E, quando a consequência finalmente aparece, muitas vezes já esquecemos a cadeia de decisões que a produziu. É por isso que tantas organizações aprendem mal com a própria experiência: elas lembram do resultado, mas não compreendem a dinâmica que levou até ele.

## O terceiro problema: o contexto não é acessório

Existe uma frase implícita em muitas discussões técnicas que deveríamos abandonar: **“funcionou lá, então deve funcionar aqui.”** Essa frase é sedutora. Também é perigosa. Em engenharia de software, **contexto não é cenário; contexto é parte da decisão**. Uma prática que funcionou em uma big tech com times altamente especializados, autonomia organizacional, infraestrutura madura e cultura de engenharia consolidada pode não funcionar da mesma forma em uma empresa tradicional, com sistemas legados críticos, orçamento restrito, dependência de fornecedores e baixa tolerância a incidentes.

Uma estratégia que fez sentido em um produto digital nativo pode ser inadequada para uma instituição financeira com décadas de integrações, restrições regulatórias e conhecimento de negócio distribuído em sistemas antigos. Uma tecnologia que brilhou em um laboratório pode falhar silenciosamente na operação. Isso não significa que não possamos aprender com outros contextos. Podemos e devemos. Mas **aprender não é copiar. Aprender é traduzir.** E tradução exige entendimento.

O problema é que a indústria frequentemente confunde evidência com história de sucesso. Uma empresa apresenta um case. Um fornecedor transforma em narrativa. Um evento transforma em referência. Um mercado transforma em tendência. E, de repente, uma experiência altamente contextualizada vira prescrição universal. **Isso não é evidência robusta. É storytelling com boa iluminação.**

## O quarto problema: compartilhamos melhor sucessos do que fracassos

Aqui existe uma diferença cultural importante. Na medicina, há mecanismos mais desenvolvidos para que eventos adversos, efeitos colaterais e falhas alimentem o corpo de conhecimento coletivo. A ideia não é apenas celebrar o tratamento que funcionou, mas aprender também com aquilo que produziu consequências inesperadas. Em software, fazemos o contrário com frequência: **publicamos os sucessos, celebramos as migrações bem-sucedidas, mostramos a arquitetura final, apresentamos os ganhos e transformamos a jornada em palestra.**

Mas os efeitos colaterais raramente aparecem com a mesma clareza. Poucas organizações contam em público que uma adoção tecnológica aumentou a complexidade operacional. Poucas explicam que a migração para uma nova arquitetura criou dependências invisíveis. Poucas admitem que uma ferramenta prometida como aceleradora passou a ser mais uma camada de lock-in. Poucas compartilham que uma modernização “bem-sucedida” transferiu custo para a manutenção futura. Não porque as pessoas sejam desonestas necessariamente, mas porque **o mercado recompensa narrativas de sucesso**. Fracassos são tratados como fraqueza competitiva, não como contribuição para o aprendizado coletivo.

E isso empobrece a evidência disponível. Como campo, aprendemos demais com apresentações polidas e de menos com os efeitos colaterais reais das nossas decisões. Talvez a engenharia de software ainda precise aprender uma coisa simples: **não existe maturidade coletiva sem memória compartilhada dos erros**.

## O quinto problema: evidência não substitui julgamento

Existe outro risco: transformar a defesa da evidência em uma nova forma de ingenuidade. **Evidência não é oráculo.** Ela não decide por nós, não elimina ambiguidade, não remove trade-offs, não torna contexto irrelevante e não transforma engenharia em receita. Uma decisão baseada em evidências não é uma decisão automática; é uma decisão mais responsável. A evidência ajuda a reduzir a arbitrariedade, qualificar a conversa, comparar alternativas, expor incertezas e separar conhecimento de preferência. Mas ainda precisamos julgar.

E julgar bem exige aceitar que algumas decisões continuarão sendo tomadas sob incerteza. Isso não é falha. É a natureza do campo. A diferença é que existe uma distância enorme entre **decidir sob incerteza** e **decidir sem fundamento**. A primeira é inevitável. A segunda é negligência disfarçada de pragmatismo.

## O que isso significa para quem está começando

Para iniciantes na área, essa discussão pode parecer abstrata. Não é. Ela aparece todos os dias em decisões simples: qual framework aprender, qual prática adotar no time, qual arquitetura defender, qual ferramenta recomendar, qual tendência seguir, qual legado criticar, qual solução considerar moderna. O conselho mais importante talvez seja este: **desconfie de respostas muito rápidas para problemas muito contextuais**.

Quando alguém disser que uma prática é obviamente melhor, pergunte: **melhor em que contexto?** Quando alguém disser que uma tecnologia é o futuro, pergunte: **o futuro de qual problema?** Quando alguém disser que todo mundo está adotando, pergunte: **com quais resultados?** Quando alguém disser que isso é padrão de mercado, pergunte: **com base em que evidência?** Essas perguntas não tornam você menos prático. Tornam você menos manipulável. E, em uma indústria movida por narrativas fortes, isso é uma competência técnica importante.

## A dificuldade da evidência não é desculpa

O fato de evidência ser difícil em software não justifica decidir de qualquer jeito. Pelo contrário. Justamente porque evidência é difícil, deveríamos ser **mais cuidadosos, mais explícitos sobre nossas premissas, mais honestos sobre nossas incertezas, mais críticos em relação a modismos, mais atentos aos efeitos de longo prazo, mais dispostos a aprender com falhas e mais rigorosos ao generalizar casos de sucesso**.

A alternativa à evidência imperfeita não deveria ser a convicção performática. Deveria ser uma prática de decisão mais humilde, mais estruturada e mais consciente. Talvez a maturidade em engenharia de software não esteja em fingir que sabemos com certeza o que funciona. Talvez esteja em **construir melhores formas de perguntar, observar, comparar e decidir — mesmo quando a certeza continua parcial**.

Porque evidência em software é difícil. Mas decisões importantes sem evidência custam caro. E, no fim, talvez esse seja o ponto central:

> **Uma engenharia madura não é aquela que elimina a incerteza.**  
> **É aquela que se recusa a usar a incerteza como desculpa para decidir mal.**

<br>

---

<br>

Este artigo é baseado em *Evidence-Based Software Engineering*, de Barbara A. Kitchenham, Tore Dybå e Magne Jørgensen, apresentado na ICSE 2004. O artigo propõe que decisões em engenharia de software devem integrar a melhor evidência de pesquisa disponível, a experiência prática e os valores humanos, ao mesmo tempo em que reconhece as dificuldades específicas de produzir e aplicar evidências em contextos de software.

Referência: Kitchenham, B. A., Dybå, T., & Jørgensen, M. (2004). *Evidence-Based Software Engineering*. Proceedings of the 26th International Conference on Software Engineering (ICSE 2004). https://www.simula.no/research/evidence-based-software-engineering