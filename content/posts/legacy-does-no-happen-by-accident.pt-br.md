+++
authors = ["Renato Teixeira"]
title = "O Legado Não Acontece por Acaso: O Que Lehman Ainda Nos Ensina Sobre Evolução de Software"
date = "2026-04-14"
description = "Uma análise estratégica das Leis de Evolução de Software de Lehman, ressignificando sistemas legados não como acidentes, mas como resultado inevitável de adaptação bem-sucedida que exige disciplina estrutural contínua."
tags = [
    "LegacyModernization",
    "EnterpriseArchitecture",
    "SoftwareEngineering",
    "SoftwareEvolution",
    "MeirLehman",
    "SoftwareLifecycle"
]
categories = [
    "Modernization",
]
series = ["Modernization"]
+++

O legado não emerge como uma falha isolada, nem como uma simples consequência da idade. Na maioria dos sistemas importantes, ele é o resultado de uma adaptação contínua sob pressões reais: novos requisitos, restrições operacionais, decisões acumuladas e a necessidade constante de permanecer útil em um ambiente em mudança. 

É por isso que o artigo de **Meir Lehman (1980)** permanece tão valioso para mim. Ele não trata o software como um artefato estático, mas como algo moldado por uma evolução contínua. E por essa razão, acredito que ele merece ser muito mais conhecido por aqueles que trabalham na prática cotidiana da TI.

O que torna o artigo tão importante é que ele ajuda a construir uma compreensão mais madura da manutenção, evolução e modernização de software. Em vez de tratar o legado meramente como "tecnologia antiga", Lehman explica por que a mudança é inerente ao software que vive no mundo real, e por que essa mesma mudança cria gradualmente uma tensão estrutural. 

Para mim, as partes mais educativas do artigo ainda são as duas primeiras leis.

---

### 1. A lei da mudança contínua
A primeira lei de Lehman afirma que um programa em uso, que reflete alguma realidade externa, deve passar por mudanças contínuas ou se tornará progressivamente menos útil. Ele também deixa claro que esse processo continua até que se torne mais econômico substituir o sistema por uma versão recriada.

Esta é uma das lições mais importantes que qualquer profissional de TI pode aprender.

Sistemas úteis não permanecem parados, porque o ambiente que eles servem não permanece parado. As prioridades de negócio mudam. Os usuários mudam. As regulamentações mudam. A infraestrutura muda. As necessidades de integração mudam. As expectativas operacionais mudam. Uma vez que o software se torna parte de um ambiente vivo, ele deve evoluir com esse ambiente.

Isso parece óbvio, mas muitas decisões ruins ainda vêm da expectativa silenciosa de que um sistema importante pode ser construído, implantado e então permanecer adequado com apenas um esforço limitado. Lehman desmantela essa ilusão.

É por isso que vejo essa lei como profundamente educativa. Ela ensina que a modernização não é simplesmente sobre substituir plataformas antigas, reescrever aplicações ou mover para a nuvem. A modernização começa com a aceitação de que o software em produção está exposto a uma pressão contínua por mudanças.

### 2. A lei da complexidade crescente
A segunda lei de Lehman é igualmente importante. À medida que um programa evolui através de mudanças contínuas, sua complexidade aumenta, a menos que um trabalho explícito seja feito para mantê-la ou reduzi-la.

Esta é uma das descrições mais honestas do que acontece com sistemas reais ao longo do tempo.

Cada correção, cada ajuste, cada exceção, cada nova integração, cada contorno operacional deixa uma marca. E quando essas marcas se acumulam sem disciplina arquitetural suficiente, o sistema se torna mais difícil de entender, mais difícil de testar, mais caro de mudar e mais perigoso de evoluir. Lehman até descreve a tentação de implementar mudança sobre mudança sobre mudança, até que o sistema se torne mais complexo, mais rígido e mais resistente a novas mudanças.

Esse é um ensinamento essencial.

A complexidade crescente não significa necessariamente que o sistema falhou. Em muitos casos, significa o oposto: o sistema sobreviveu, permaneceu valioso e absorveu anos de demandas reais de negócio. O problema não é a mudança em si. O problema é a mudança sem cuidado estrutural sustentado.

É por isso que esta segunda lei permanece tão educativa na prática. Ela nos lembra que não há evolução contínua sem custo estrutural. Nenhum sistema útil de vida longa escapa dessa tensão. E quando esse custo é ignorado por muito tempo, o sistema entra na zona familiar onde a resposta desacelera, a mudança se torna cara, o teste se torna estressante e a modernização começa a parecer maior e mais arriscada do que deveria.

---

### O que estas duas leis ensinam juntas
Quando leio Lehman, vejo estas duas leis como uma base para entender a evolução do software.

* **A primeira ensina:** se um sistema é útil, ele precisará mudar.
* **A segunda ensina:** se ele muda continuamente, sua estrutura tenderá a se deteriorar, a menos que alguém trabalhe ativamente contra essa tendência.

Tomadas em conjunto, essas duas ideias explicam muito do que ainda enfrentamos na TI corporativa. Elas explicam por que sistemas centrais se tornam legados mesmo quando permanecem relevantes. Elas explicam por que a modernização não deve ser tratada como um evento raro, mas como uma capacidade permanente. Elas explicam por que a arquitetura não pode ser apenas uma preocupação de design inicial. E elas explicam por que a manutenção não é uma fase secundária da engenharia de software, mas uma parte central da vida econômica e técnica do software. 

Lehman argumenta explicitamente que a mudança deve ser planejada e controlada, e que a avaliação econômica de um sistema deve considerar os custos totais do ciclo de vida, em vez de apenas seu custo de desenvolvimento inicial.

---

### As outras leis importam também
Embora eu considere as duas primeiras leis as mais imediatamente educativas para os praticantes, as leis restantes também adicionam uma perspectiva importante.

* **Terceira lei de Lehman (lei fundamental da evolução de programas):** argumenta que a evolução do software segue uma dinâmica subjacente que torna o processo estatisticamente regular e, até certo ponto, autorregulado. Isso importa porque sugere que a evolução não é apenas uma sequência de decisões locais isoladas, mas um processo mais amplo com padrões observáveis.
* **A quarta lei (conservação da estabilidade organizacional):** aponta para uma taxa de trabalho invariante durante a vida ativa de um programa. Na prática, isso é um lembrete de que a evolução do software é moldada não apenas pelo código, mas pela capacidade e limites organizacionais. Mais pressão ou mais pessoas não produzem automaticamente mudanças proporcionalmente mais eficazes.
* **A quinta lei (conservação da familiaridade):** sugere que o conteúdo de lançamentos sucessivos tende a permanecer estatisticamente restrito. Essa é outra ideia poderosa para os praticantes: sistemas e organizações só conseguem absorver uma certa quantidade de mudança por vez sem se desestabilizarem.

Mesmo quando lidas brevemente, essas leis reforçam a mesma lição mais ampla: a evolução do software não é arbitrária. Ela possui padrões, restrições e consequências que devem ser compreendidos como parte da prática de engenharia.

---

### Por que este artigo ainda importa
O que eu mais valorizo no artigo de Lehman é que ele educa sem simplificar demais. Ele trata o software como um fenômeno técnico, organizacional e econômico ao mesmo tempo. E isso permanece extremamente relevante.

Enquanto agora falamos sobre nuvem, microsserviços, engenharia de plataforma, observabilidade, refatoração em larga escala e desenvolvimento assistido por IA, Lehman ainda nos lembra de algo mais fundamental: o software em uso real deve evoluir, e essa evolução carrega um custo estrutural. Ignorar qualquer lado dessa equação leva a um julgamento ruim.

É por isso que acredito que este texto merece circular muito mais amplamente entre os profissionais de TI. Antes de debater a próxima tendência tecnológica, vale a pena entender a natureza do problema que acompanha todo sistema importante de vida longa: a inevitabilidade da mudança e a tendência igualmente inevitável de crescimento da complexidade.

Para qualquer pessoa que trabalhe com sistemas legados, poucas combinações são tão esclarecedoras quanto essa.

O legado não acontece por acidente. E quanto mais seriamente entendermos isso, melhor poderemos modernizar com julgamento.