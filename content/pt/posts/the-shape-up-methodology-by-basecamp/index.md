+++
title = 'A metodologia Shape Up da Basecamp'
date = 2024-12-09T12:44:36-03:00
draft = false
+++

---

> Esse post faz parte de uma série de posts sobre a metodologia Shape Up da Basecamp. Nesse post, vamos falar sobre o que é Shape Up e apresentar um panorama geral do processo. No próximo post, vamos focar em como cada etapa funciona na prática. Se você é desenvolvedor, gerente de produto ou parte de um time de tecnologia, essa série é para você!

---

## Introdução

De forma geral, *Shape Up* é um framework criado pela Basecamp que busca resolver os desafios comuns enfrentados por times de desenvolvimento de produto, especialmente aqueles causados pelas dores do crescimento. [Saiba mais sobre as origens e objetivos do Shape Up no site oficial da Basecamp](https://basecamp.com/shapeup/0.3-chapter-01#growing-pains).

Essa metodologia ajuda equipes a se organizarem melhor ao modelar problemas com antecedência, permitindo construir e entregar soluções dentro de um período fixo de tempo (6 semanas). Isso resulta em maior eficiência e geração de valor para o negócio. Ideal para empresas menores, o Shape Up equilibra a necessidade de processos estruturados com a flexibilidade de adaptação. Ele minimiza escopos excessivos e garante que as equipes se concentrem em tarefas de alta prioridade.

### **Glossário de termos importantes:**

- `Pitch`: Um problema que precisa ser resolvido; é a unidade de trabalho no Shape Up.
- `Tríade`: Composta por um Product Manager, um Tech Lead e um Designer; responsável por refinar os *Pitches*.
- `Time dev`: Equipe de desenvolvimento que executa o trabalho.
- `Apetite`: Tempo estimado para resolver um *Pitch*; geralmente 6 semanas.
- `Rabbit Hole`: Problemas que surgem durante a execução de um *Pitch* e estão fora do escopo.
- `Cool Down`: Período de 2 semanas de descanso entre os ciclos de 6 semanas.

---

## Por que Shape Up?

1. **Balanço entre autonomia e responsabilidade**  
   Times têm liberdade para executar, mas dentro de parâmetros claros e objetivos.

2. **Foco na entrega de valor**  
   As equipes priorizam o que realmente importa para o negócio.

3. **Redução de riscos**  
   Refinamento prévio minimiza incertezas durante a execução.

4. **Escopo controlado**  
   O *Pitch* delimita o trabalho a ser feito, evitando escopos excessivos.

---

## Processo

No *Shape Up*, todo problema é refinado previamente pela *tríade* (PM+TL+PD) antes de entrar em desenvolvimento. O processo é dividido em dois grandes grupos:

1. **Fora do Ciclo** (*Upstream*)

2. **Dentro do Ciclo** (*Downstream*)

![Shape Up process](shape-up-process.png)

---

### Fora do Ciclo

#### **Shape**

O *Shaping* é um processo de refinamento realizado pela *tríade* (PM+TL+PD) durante 6 semanas. Durante essa etapa, a *tríade* explora o problema profundamente, consulta especialistas quando necessário e documenta todo o contexto (ex.: framing, métricas, fluxos, protótipos). O objetivo é modelar o problema de forma que o time de desenvolvimento possa trabalhar com autonomia na solução.

> *Se o refinamento for bem feito, a execução será mais eficiente. Isso cria um ciclo positivo de autonomia para ambas as partes (ciclo visioso).*

**O inverso também é verdadeiro, você já entendeu a lógica né?**

Vale ressaltar que a quantidade de contexto em um Pitch pode variar por diversos motivos: complexidade do assunto (negócio), complexidade técnica e maturidade do time.

> ℹ️ *A etapa de shaping ocorre em paralelo ao ciclo de BUILD.*

#### **Betting Table**

Após o *Shaping*, os stakeholders se reúnem na "mesa de apostas" para decidir quais *Pitches* serão priorizados. Durante essa reunião, a *tríade* apresenta cada *Pitch*, explicando o problema, a solução proposta, o *apetite* e os *rabbit holes*. Os stakeholders, então, decidem quais *Pitches* entrarão no próximo ciclo de BUILD.

> ℹ️ *Essa etapa ocorre após as 6 semanas de SHAPE.*

---

### Dentro do Ciclo

#### **Build**

O *Build* é o ciclo de 6 semanas onde o time de desenvolvimento constrói, testa e entrega a solução para o problema. Durante esse período, o foco é exclusivamente na entrega dentro do *apetite* definido. Novos problemas descobertos durante a execução são documentados para tratamento em futuros ciclos de SHAPE.

> ℹ️ *BUILD ocorre em paralelo com o ciclo de SHAPE.*

#### **Cool Down**

Após o ciclo de 6 semanas de *Build*, ocorre uma pausa de 2 semanas conhecida como *Cool Down*. Esse momento é dedicado a:

- Refletir sobre o ciclo anterior.
- Resolver problemas menores, como dívidas técnicas.
- Revisar documentação e preparar-se para o próximo ciclo.

> *Essa pausa é fundamental para manter a saúde do time e melhorar processos.*

---

Até o próximo post! 🚀 *"No próximo, vamos explorar as etapas de SHAPE e BUILD em maior profundidade."*
