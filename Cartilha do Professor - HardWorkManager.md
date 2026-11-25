# HardWorkManager - Cartilha do Professor
### Guia de Aplicação Pedagógica do jogo HardWorkManager para o Ensino do **Domínio de Recursos - PMBOK® Guide 8ª Edição**

| Público-alvo | Duração | Formato |
| :--- | :--- | :--- |
| Alunos de graduação em áreas da Ciência da Computação. | 60 ou 100 minutos | Equipes de 2 ou 3 alunos, 1 dispositivo por equipe |

---

## Sumário do Manual

### Parte A — Para usar o jogo na próxima aula (~10 min)
* [01. Apresentação do Jogo e Acesso](#01-apresentação-do-jogo-e-acesso)
* [02. Equipes e Preparação da Aula](#02-equipes-e-preparação-da-aula)
* [03. Papéis, Fluxo da Rodada e Métricas](#03-papéis-fluxo-da-rodada-e-métricas)
* [04. Cronograma da Aula (100 min)](#04-cronograma-da-aula-100-min)
* [05. Roteiro de Reflexão Pós-Partida (25 min)](#05-roteiro-de-reflexão-pós-partida-25-min)

### Parte B — Material de consulta
* [06. Objetivos de Aprendizagem](#06-objetivos-de-aprendizagem)
* [07. Relação com o PMBOK 8 - Domínio de Recursos](#07-relação-com-o-pmbok-8---domínio-de-recursos)
* [08. Glossário e Conceitos Formais](#08-glossário-e-conceitos-formais)
* [09. Papel do Professor Durante a Partida](#09-papel-do-professor-durante-a-partida)
* [10. Memorial de Decisões — Atividade opcional (segunda aula)](#10-memorial-de-decisões--atividade-opcional-segunda-aula)
* [11. Dificuldades Comuns e FAQ](#11-dificuldades-comuns-e-faq)
* [12. Adaptações da Atividade](#12-adaptações-da-atividade)
* [13. Apêndice Teórico-Científico](#13-apêndice-teórico-científico)

---

> **Parte A — Para usar o jogo na próxima aula:** essencial (~10 min de leitura) para aplicar o jogo em sala.

## 01. Apresentação do Jogo e Acesso

O **HardWorkManager** (https://hardworkmanager.vercel.app) ensina o **Domínio de Recursos do PMBOK® 8ª Edição**. Em um projeto fictício de sistema universitário, equipes lideram decisões sobre pessoas, ambientes e ferramentas, sem exigir base prévia em programação.

> **O professor não precisa configurar nada no jogo.** A cada partida, o jogo sorteia 6 dos 50 dilemas (um de cada módulo e um sexto de qualquer módulo, sem repetir) e embaralha a ordem das alternativas. Basta abrir o link em um computador por equipe.

### Dinâmica em grupo
* 1 dispositivo por equipe (computador, notebook, tablet ou celular).
* No voto individual, há aviso de sigilo para os colegas não olharem a tela; revelação, debate e votação final são coletivos.

---

## 02. Equipes e Preparação da Aula

| Item | Recomendação |
| :--- | :--- |
| **Pré-requisito** | Ao menos uma aula introdutória sobre o Domínio de Recursos do PMBOK 8. |
| **Turma e equipes** | 15 a 40 alunos, em **equipes de 2 ou 3 alunos** (ver Seção 12 para outros tamanhos). |
| **Espaço e materiais** | Mesas ou carteiras de **2-3 lugares**, 1 dispositivo por equipe e 1 projetor para o debriefing. |

### Checklist técnico
* [ ] Teste `https://hardworkmanager.vercel.app` 1 dia antes nos navegadores do laboratório (Chrome/Edge).
* [ ] O progresso fica salvo no navegador (`localStorage`): oriente a não fechar a aba nem limpar os dados.
* [ ] Tenha rede alternativa (ponto de acesso do celular) caso o Wi-Fi falhe.

---

## 03. Papéis, Fluxo da Rodada e Métricas

### 3.1 Papéis e sorteio

| Papel | Foco no jogo |
| :--- | :--- |
| **Gerente de Projetos (GP)** | Coordenação, liderança servidora, alinhamento de prioridades e voto de desempate. |
| **Líder Técnico** | Infraestrutura, recursos virtuais, riscos técnicos e redução de retrabalho. |
| **Líder de Design e Telas** | Experiência e acessibilidade dos usuários do sistema e fluxo de aprovação. |

Os papéis são **sorteados depois do cadastro dos jogadores**. Toda equipe tem um GP. Com dois jogadores, o segundo papel é sorteado entre Líder Técnico e Líder de Design e Telas; com três, os três papéis são usados. Não há como voltar e sortear de novo. O sorteio evita que um estudante escolha o papel de GP para conduzir as decisões dos colegas (problema do jogador alfa, observado no teste piloto).

### 3.2 Fluxo da rodada

Cada partida tem **6 dilemas (2 ciclos de 3 dilemas)**:

1. **Leitura do dilema:** 2 minutos, com cronômetro visível.
2. **Voto individual:** 1 minuto por jogador; os demais não olham a tela; sem voto no tempo, conta como abstenção.
3. **Revelação dos votos:** se unânimes, a decisão é aplicada.
4. **Debate estruturado** (se houver divergência): 30 segundos por jogador, com troca automática da vez. Fala primeiro quem teve menos votos, começando por quem se absteve, e o GP fala por último.
5. **Segunda votação:** aberta, em uma única tela; o GP não pode se abster. Em caso de empate, prevalece o voto do GP.
6. **Consequências e lições:** mostra o que aconteceu no projeto, variação das métricas, conceito do PMBOK 8 e lições.
7. **Revisão de ciclo:** ao fim de cada ciclo de 3 dilemas, resume decisões, consequências e ameaças pendentes.

<!-- TODO: inserir figura-2-fluxo-rodada.png -->

A partida termina antes se **Capacidade de Entrega**, **Qualidade do Produto** ou **Saúde da Equipe** ficarem abaixo de 40, abrindo o debriefing final.

### 3.3 Métricas e fim de jogo

| Métrica | Início | Regra crítica |
| :--- | :---: | :--- |
| **Capacidade de Entrega** | 100 | < 40 → fim de jogo |
| **Qualidade do Produto** | 100 | < 40 → fim de jogo |
| **Saúde da Equipe** | 100 | < 40 → fim de jogo |
| **Conhecimento Organizacional** | 50 | < 20 → dobra perdas de Capacidade de Entrega |

---

## 04. Cronograma da Aula (100 min)

| Etapa | Tempo | Professor | Alunos |
| :--- | :---: | :--- | :--- |
| **Abertura** | 15 min | Retoma o Domínio de Recursos (PMBOK 8) e apresenta a dinâmica. | Formam equipes de 2 ou 3 alunos e acompanham as orientações. |
| **Preparação** | 10 min | Orienta acesso ao link e regras básicas. | Acessam o jogo, cadastram os jogadores e o jogo sorteia os papéis. |
| **Partida** | 45 min | Circula entre as equipes e provoca reflexão (Seção 09). | Analisam dilemas, debatem e decidem. |
| **Reflexão** | 25 min | Conduz o roteiro da Seção 05. | Compartilham decisões, consequências e conceitos. |
| **Fechamento** | 5 min | Retoma os principais aprendizados e, se for usar o memorial, explica a atividade da segunda aula. | Sistematizam os aprendizados. |

*Aula de 60 min: reserve 30 min para a partida e 15 min para a reflexão. Se o tempo acabar antes do fim da partida, encerre na revisão de ciclo mais recente e use as decisões tomadas até ali na reflexão.*

---

## 05. Roteiro de Reflexão Pós-Partida (25 min)

| Tempo | Pergunta | Condução |
| :---: | :--- | :--- |
| **6 min** | **Alguma equipe atingiu fim de jogo? O que levou a isso?** | Identificar a métrica crítica e as decisões que causaram a queda. |
| **6 min** | **Alguma decisão inicial gerou consequência rodadas depois?** | Citar um exemplo e discutir se o impacto era previsível. |
| **6 min** | **Como os papéis contribuíram para as decisões?** | Ouvir Gerentes de Projetos, Líderes Técnicos e Líderes de Design e Telas sobre conflitos de prioridade. |
| **5 min** | **Como a adaptação dos processos afetou os resultados?** | Relacionar ao *Tailoring*: quando simplificar ajuda ou gera risco. |
| **2 min** | **O que fariam diferente se jogassem novamente?** | Conectar as escolhas ao Domínio de Recursos do PMBOK 8. |

> **Se houver silêncio:** cite uma escolha observada ("vi a equipe X escolher B no dilema Y — por quê?").

---

> **Parte B — Material de consulta:** alinhamento ao PMBOK 8, glossário, intervenções, memorial opcional, FAQ e adaptações.

## 06. Objetivos de Aprendizagem

| Nível (Bloom) | O aluno será capaz de... | Onde aparece no jogo |
| :--- | :--- | :--- |
| **Lembrar** | Identificar conceitos do Domínio de Recursos (*Team Charter*, liderança servidora, estimativas, Teoria das Restrições, *Lean / Muda*, RAM e *Blameless Post-Mortem*). | Dilemas e lições |
| **Compreender** | Explicar a relação entre as 4 métricas e a alocação sustentável de pessoas, ambientes e ferramentas. | Painel de métricas |
| **Aplicar** | Argumentar no debate defendendo um papel (GP, Líder Técnico, Líder de Design e Telas). | Apuração & Debate |
| **Analisar** | Identificar como decisões de curto prazo geram consequências futuras. | Consequências |

---

## 07. Relação com o PMBOK 8 - Domínio de Recursos

### 7.1 Estrutura e classificação dos recursos

| Categoria | Definição (PMBOK 8) | Representação no Jogo |
| :--- | :--- | :--- |
| **Recursos Humanos** | Pessoas com papéis e responsabilidades pelo objetivo comum. | Desenvolvedores, designers de interface, analistas de testes e lideranças. |
| **Recursos Físicos e Virtuais** | Equipamentos, nuvem, servidores, licenças, dados e ferramentas. | Servidores locais, nuvem elástica, ambientes de testes e licenças de software. |

### 7.2 Os 5 Processos do Domínio de Recursos

| Processo | Definição no PMBOK 8 | No Jogo |
| :--- | :--- | :--- |
| **Planejar** | Define *Tailoring*, *Team Charter* e estratégia de escassez. | Dimensionamento, acordos entre equipes e equilíbrio de documentação. |
| **Estimar** | Calcula esforço e recursos (*Bottom-Up*, paramétrica, análoga). | Escolha entre estimativa detalhada ou rápida por analogia. |
| **Adquirir** | Aloca pessoas e ambientes por negociação matricial e alternativas. | Negociação por desenvolvedores, nuvem temporária e apoio externo. |
| **Liderar a Equipe** | Liderança servidora, clima seguro (*Blameless Post-Mortem*) e prevenção ao *burnout*. | Gestão de conflitos, capacitação e proteção contra sobrecarga. |
| **Monitorar e Controlar** | Acompanha uso real, subordina gargalos (TOC) e reduz *Lean / Muda*. | Controle de licenças ociosas, remoção de gargalos e testes. |

### 7.3 Os 7 Resultados Esperados do PMBOK 8 e as 4 Métricas do Jogo

| Resultado PMBOK 8 | Definição | Métrica Conectada |
| :--- | :--- | :--- |
| **R1. Propriedade Compartilhada** | Visão comum e responsabilidade coletiva, sem silos. | **Conhecimento Organizacional** |
| **R2. Equipe de Alto Desempenho** | Confiança, segurança psicológica e prevenção ao *burnout*. | **Saúde da Equipe** |
| **R3. Utilização Eficaz** | Consumo de recursos compatível com o planejado. | **Capacidade de Entrega** |
| **R4. Inatividade Aceitável** | Redução de esperas, bloqueios e ociosidade. | **Capacidade de Entrega** |
| **R5. Equipe Produtiva** | Ritmo de entrega sustentável à capacidade instalada. | **Capacidade de Entrega** |
| **R6. Gestão Eficiente** | Baixo retrabalho e desperdício (*Lean/Muda*). | **Qualidade do Produto** |
| **R7. Gestão de Aquisição** | Recursos obtidos conforme regras operacionais e orçamentárias. | Sem métrica exclusiva: o jogo não simula orçamento, fornecedores nem prazos de entrega. Os dilemas de Adquirir os Recursos alteram as quatro métricas. |

### 7.4 Módulos Temáticos (50 Dilemas)

| Módulo (10 dilemas cada) | Processo Principal | Foco Prático |
| :--- | :--- | :--- |
| **1. Liderança e Clima Seguro** | Liderar a Equipe | *Blameless Post-Mortem*, liderança servidora, proteção contra *burnout*. |
| **2. Infraestrutura e Ambientes Virtuais** | Monitorar / Adquirir | Servidores locais vs. nuvem elástica, testes simulados e licenças. |
| **3. Planejamento Adaptado e Tailoring** | Planejar / Estimar | *Lean*, *Team Charter*, estimativa *Bottom-Up* vs. análoga. |
| **4. Gestão de Demandas e Aquisições** | Adquirir / Planejar | Negociação matricial, urgências, equipes externas e mudanças. |
| **5. Eficiência e Otimização de Fluxo** | Monitorar e Controlar | Teoria das Restrições (gargalos), retrabalho e fechamento de ciclos. |

---

## 08. Glossário e Conceitos Formais

| Termo no Jogo | Conceito no PMBOK 8 | Aplicação Prática |
| :--- | :--- | :--- |
| **Conhecimento Organizacional** | Propriedade Compartilhada (R1) | Transferência de saberes e documentação contra silos e dependência de pessoas-chave. |
| **Ecos Diferidos** | Impactos de Médio e Longo Prazo | Atalhos improvisados cobram um preço rodadas à frente. |
| **Ciclo de Entregas** | Período Operacional Planejado | Janela de 3 dilemas encerrada com revisão de decisões e ameaças pendentes. |
| **Desempate pelo Gerente de Projetos** | Prerrogativa Decisória em Empates | Na segunda votação (aberta), o GP não pode se abster e seu voto desempata. |

### 8.1 Conceitos Formais Ensinados no Jogo

| Conceito (PMBOK 8) | Definição | Processo |
| :--- | :--- | :--- |
| **Team Charter** | Acordo colaborativo de regras e normas da equipe. | Liderar |
| **Liderança Servidora** | Remove obstáculos e apoia os especialistas. | Liderar |
| **Blameless Post-Mortem** | Análise de falhas sem culpar indivíduos. | Liderar |
| **Estimativa Bottom-Up** | Soma detalhada do esforço de cada componente. | Estimar |
| **Análoga e Paramétrica** | Estimativas rápidas por histórico ou relação estatística. | Estimar |
| **Teoria das Restrições** | Subordina o fluxo ao gargalo do processo. | Monitorar |
| **Lean / Muda** | Eliminação de retrabalho e esforço sem valor. | Monitorar |
| **Matriz RAM** | Define quem executa, aprova e apoia cada entrega. | Planejar |
| **Recursos Alternativos** | Soluções temporárias com riscos reconhecidos. | Adquirir |
| **Tailoring** | Adaptação das práticas à realidade do projeto. | Planejar |

---

## 09. Papel do Professor Durante a Partida

### 9.1 Quando intervir
* Equipe decide em menos de 30s sem debate → provoque.
* Um integrante domina as falas → direcione a pergunta a outro papel.
* Dúvida sobre regra → esclareça a mecânica, sem sugerir opção.

### 9.2 Frases de intervenção reflexiva
* "Qual métrica vocês estão dispostos a sacrificar aqui, e por quê?"
* "Se essa escolha gerar consequência daqui a 3 rodadas, vão lembrar o motivo?"
* "Líder Técnico e Líder de Design e Telas, vocês concordam com o encaminhamento do GP?"

> **Limite:** nunca revele a opção "certa"; peça sempre justificativa.

---

## 10. Memorial de Decisões — Atividade opcional (segunda aula)

> **Princípio formativo:** nunca avalie pela pontuação do jogo; avalie a capacidade de justificar causas e consequências das decisões.

Para avaliar em uma **segunda aula**, aplique o Memorial (individual ou por equipe) sobre 3 dos 6 dilemas, sob a ótica dos papéis (GP, Líder Técnico e Líder de Design e Telas), com rubrica de 10,0 pontos:

| Critério | Nota | O que observar |
| :--- | :---: | :--- |
| **1. Profundidade da Análise dos Dilemas** | 4,0 pts | Descreveu os 3 dilemas e fundamentou com o raciocínio de cada papel (GP, Líder Técnico, Líder de Design e Telas)? |
| **2. Articulação com o PMBOK 8** | 3,0 pts | Aplicou corretamente conceitos do Domínio de Recursos (Teoria das Restrições, *Team Charter*, liderança servidora, estimativas)? |
| **3. Diagnóstico Crítico e Consequências** | 3,0 pts | Conectou consequências diferidas às escolhas iniciais com autoavaliação honesta? |

### 10.1 Template (1 página)

| Campo | O que preencher |
| :--- | :--- |
| **Dilema escolhido (3 dos 6 dilemas da partida)** | Nome/resumo do dilema |
| **Opção escolhida** | A, B ou C |
| **Justificativa (PMBOK 8)** | Conceito do Domínio de Recursos (Seção 07) |
| **Impacto observado** | Métricas afetadas e consequências |
| **O que faria diferente** | Reflexão crítica de 2-3 linhas |

> **Exemplo preenchido:** **Dilema:** "Problema próximo ao prazo" · **Opção:** B (solução rápida) · **Justificativa:** priorizamos Capacidade de Entrega com risco à Qualidade · **Impacto:** +5 Capacidade, −10 Qualidade; consequência futura · **Reflexão:** "Deveríamos ter feito uma verificação extra."

---

## 11. Dificuldades Comuns e FAQ

| Situação | O que fazer |
| :--- | :--- |
| **Equipe empata e o GP está ausente** | O jogo sempre sorteia um GP entre os presentes. Se o GP sair no meio da partida, um colega assume sua vez na tela (na 2ª votação, o GP não se abstém e desempata). |
| **Aluno faltante em equipe de 3** | A equipe joga com dois jogadores; o jogo sorteia os papéis entre os presentes. |
| **Dispositivo trava ou perde bateria** | O progresso fica salvo apenas no navegador atual; ao trocar de aparelho, a partida recomeça. |
| **Equipe termina antes das outras** | Peça que anotem as duas decisões que mais afetaram as métricas, para a reflexão pós-partida. |
| **Wi-Fi cai durante a partida** | O progresso da partida fica salvo no navegador; quando a conexão voltar, recarregue a página. Se possível, tenha uma rede alternativa (ponto de acesso do celular). |

---

## 12. Adaptações da Atividade

| Cenário | Ajuste |
| :--- | :--- |
| **Menos de 15 alunos** | Forme equipes de 2 alunos; o jogo sorteia os papéis entre os dois. |
| **Mais de 40 alunos** | Divida em duas sessões paralelas com monitores ou em duas aulas. |
| **Aula de 60 minutos** | Ver nota da Seção 04: 30 min de partida + 15 min de reflexão, encerrando na revisão de ciclo mais recente. |
| **Sem laboratório** | Use notebook, tablet ou celular de um integrante por equipe. |

---

## 13. Apêndice Teórico-Científico

* **MEEGA+:** avalia usabilidade e experiência do jogador (motivação, imersão e aprendizagem percebida).
* **Kirkpatrick Nível 1 (Reação):** questionário de satisfação pós-jogo.
* **Kirkpatrick Nível 2 (Aprendizagem):** pré-teste/pós-teste e Memorial de Decisões opcional.
