---
title: 'Bug Bash'
date: 2025-03-27T11:26:23-03:00
draft: false
categories:
- Quality Engineering
---

Em projetos de software, principalmente os que levam mais tempo com uma complexidade maior em regras de negócios e/ou alterações, é comum que seja necessário um plano de teste melhor estruturado para dar visibilidade sobre o escopo das mudanças, regras de negócio e o que será testado. Em muitos casos, uma pessoa no time é responsável por executar todos os cenários, documentar os bugs, porém, essa é uma ótima oportunidade para o QA promover colaboração entre os membros do time, promovendo a colaboração e troca de conhecimento sobre uma determinada funcionalidade, além de fortalecer a cultura de qualidade do time e o sentimento de que "Qualidade é responsabilidade de todos“.

## O que é Bug Bash?

O Bug Bash é uma estratégia colaborativa de testes que visa aproveitar os diferentes perfis de usuário de todos os integrantes da equipe envolvida com o desenvolvimento do produto, independente de função ou cargo, para testarem, em um curto espaço de tempo pré-estabelecido, uma determinada funcionalidade ou nova versão do software.

Com a participação de pessoas com diversas habilidades é possível reunir uma abundância de pontos de atenção em curto espaço de tempo, além de permitir que as pessoas se familiarizem com a nova versão do produto/funcionalidade que tanto aguardam.

Para promover um Bug bash,  muita organização é necessária para que o objetivo seja alcançado com sucesso no período estabelecido.

## Organizando um Bug Bash

- Defina um objetivo claro para o evento, por exemplo, testar a funcionalidade, usabilidade, responsividade, navegabilidade, etc ou modelo do bug bash, se será baseado em um checklist de cenários/casos de testes ou aberto para que os participantes possam explorar e testar livremente o que bem entender!

- Marque um momento com os participantes no qual todos possam realmente estar ali, colaborando, trocando informações e interagindo de modo que todos possam participar, mostre para o time a importância desse tipo de evento e não esqueça de agendar mais tempo na agenda para caber uma **abertura** para explicar como o evento irá acontecer e o **encerramento** para que seja possível coletar os resultados do bug bash;

- Caso o evento seja guiado por um checklist de cenários/casos de testes, tente priorizar os casos que possuem mais risco para o negócio, de modo que seja factível executar todos os casos dentro do tempo limite;

- **Como o tempo será curto, prepare tudo de antemão**: ambiente no qual será testado, número da versão, contas para teste, o que está ou não em escopo, cenários de teste, como reportar os problemas no Jira (título claro, descrição, cenário esperado, cenário observado e evidências), uma planilha para auxiliar na organização;

## Executando um Bug Bash

- Chegado o grande dia, faça uma apresentação curta de abertura para os participantes, explicando cada um dos pontos explicados, objetivos, tempo, regras  e informações adicionais;

- **Mostre-se disponível para tirar qualquer tipo de dúvida dos participantes sobre a funcionalidade, cenários de testes, regra de negócio.** Então esteja ciente de que talvez não sobre muito tempo para você colocar a mão na massa (mas claro, tudo depende do nível de maturidade/familiaridade do time com o assunto), com o tempo, é comum que os conceitos e a informação de “como testar” fique cada vez mais obvia;

- É importante que os participantes testem dentro das regras estabelecidas (seguindo um checklist ou de forma exploratória);

- É comum que participante com pouco contexto (novos integrantes no time), se sinta um pouco acuado, interaja trazendo-(o/a) para o contexto e ambiente de troca;

- Incentive as pessoas para compartilharem suas telas e esclarecer suas dúvidas de forma clara, promovendo aprendizagem;

- Caso surja mais de uma discussão/dúvida simultaneamente, abra uma segunda chamada temporária no teams, de modo que seja possível expandir o assunto e retorne para a chamada principal quando terminar, trazendo um resumo do que foi discutido. Não esqueça de documentar!

- Finalizando o tempo limite, faça uma cerimônia de encerramento colhendo feedbacks dos participantes e agradecendo sua participação, caso seja possível, mostre os resultados prévios obtidos: quantos casos de testes foram verificados, quantos bugs foram abertos, quantos feedbacks de melhorias foi reportado pelo time, etc.

- Se não der tempo de executar, todos os casos não têm problema, tente testar o máximo que conseguir dentro do período definido;

- Por último, mas não menos importante (Bônus): Pense em maneiras de gamificar o bug bash, gerando premiação para o participante que reportou mais problemas ou o problema mais crítico para o negócio, use a imaginação e promova engajamento;

## Comunicando os resultados

- Escolha como reportará os resultados: via e-mail, PDF, apresentação para o time, independente do formato, não demore nessa etapa!

- Em alguns casos será necessário consultar a pessoa que reportou determinado bug para coletar mais informações;

- Apareceram novos cenários/casos de testes? Ótimo… não esqueça de enriquecer a planilha de cenários para uma próxima iteração;

- Conte com a ajuda de stakeholders para endereçar os problemas como PM, TL, Design, visando uma priorização clara sobre o que é impeditivo para o release e o que pode ser postergado;

- Compartilhe e colete feedbacks com os participantes para melhorar o processo na próxima iteração e manter o time engajado;

Happy testing! 🐞🎉
