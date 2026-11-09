# Notas de Design — RPG Mitos v1.0.0

> Arquivo **interno** (não faz parte do livro do jogador). Aqui ficam o racional por trás de decisões de regra e as diferenciações entre habilidades parecidas — informação útil para quem mantém o sistema, mas que polui o produto final.

## Racional de regras

### Espaçamento dos níveis de magia
Os slots de magia são adquiridos nos níveis **2, 4, 6, 11, 16, 20** (mais os flex de **14** e **18**), enquanto as Escolhas vêm em **1, 3, 7, 10, 15, 20**. Esse descompasso é proposital: evita que o jogador tenha que tomar várias decisões pesadas (escolher magia *e* habilidade) no mesmo nível.

> No catálogo de cada deus, o número à esquerda de cada magia é o **nível mínimo** dela, não o nível em que se ganha o slot.

## Diferenciação entre habilidades parecidas

Notas que existiam dentro do livro e foram movidas para cá (o livro mantém só o efeito de cada habilidade):

- **Hades — Visão do Sepulcro (magia 5)** vs **Comando dos Mortos (herança 13):** a magia mostra as 24h *antes* da morte (investigação histórica); a herança foca no *momento* da morte.
- **Atena — Manto de Atena (magia 3)** vs **Tecelagem Mística (herança 5):** o Manto dá vantagem em teste de Inteligência; a Tecelagem dá proteção elemental.
- **Atena — Companheira Coruja (magia 13)** vs **Conselho de Atena (escolha 15):** a Companheira é uma coruja invocada que luta/espia; o Conselho é uma pergunta direta à deusa.
- **Apolo — Canção de Inspiração (magia 3)** vs **Inspiração Solar (escolha 1):** a Canção é buff de Carisma em grupo; a Inspiração Solar é buff individual de rolagem.
- **Hefesto — Lâmina Ardente (escolha 3)** vs **Explosão Direcionada (magia 3):** a Lâmina encanta a arma corpo a corpo; a Explosão é projétil em área.
- **Dionísio — Banquete Báquico Menor (magia 1)** vs **Conjurar Vinho (escolha 1):** o Banquete cria comida sem álcool; Conjurar Vinho cria bebida com cura.
- **Dionísio — Loucura Sagrada (magia 13)** vs **Loucura em Massa (herança 20):** a Sagrada causa paralisia (visões); a em Massa causa confusão.
- **Demeter — Invocar Karpoi de Tempestade (escolha 7)** vs **Karpos Leal (Vínculo, pego como Aprimoramento)** vs **Invocação de Karpoi Maior (magia 13):** a de Tempestade é dano em área (3 turnos); o Karpos Leal é **um** espírito fiel, que o jogador escolhe ter (o Mestre só ajuda a encaixá-lo na história), invocado por 10 min — não é companheiro permanente; a Maior é o enxame de combate.

## Decisões de projeto

- **Caçadoras de Ártemis — gênero:** abertas a personagens femininas, **incluindo mulheres trans** (leitura contemporânea inclusiva).
- **Belona — 9 Escolhas:** uma a mais que os pares guerreiros (Ares/Marte), por causa da inclusão de "Doação da Pretora". Intencional.
- **Hipnos — magias de sono:** têm recarga + restrições temáticas (sono não funciona em barulho/sol) deliberadamente, para conter o poder de "desligar" inimigos.

## Balanceamento (auditoria de 2026-06)

- **PM de Poseidon = For e Hermes = Des** (não mais Char). Motivo: o atributo de PM tem que ser o que a herança fortalece, senão o caster fica com pool fraco e "dump-stat". Para Poseidon isso também corrige o cânone — Percy é um manipulador de água S-tier, então a magia dele escala com a força/natureza divina (For), não com um atributo mental que ele não usa. Convenção "PM = Char/Int" deixa de ser universal: agora cada deus usa o atributo coerente com seu kit.
- **PM de Hades (Int) e Apolo (Car) — revisados e MANTIDOS.** Ambos sobem mais Destreza, mas o PM segue Int (morte/sombra/necromancia) e Car (cura/música). Diferente do Poseidon antigo, aqui não há atributo-lixo: Int e Car são usados pelo kit e pela Resistência Forte, e a tensão furtivo/arqueiro × caster é uma escolha de build legítima. Não é dump-stat.
- **Atena com 4d6 PV (2º maior do jogo) — revisado e MANTIDO.** Atena é o caster tático/buff/defesa com pouco dano bruto; a Hécate é o canhão de vidro (2d6) de dano alto. A diferença de resistência é o trade-off entre os dois arquétipos, não um desbalanço.
- **Paridade Ímpeto (guerreiro) × PM (caster) — mantida de propósito.** Guerreiros regeneram Ímpeto em combate (sustain); casters têm pool grande mas recarregam em descanso (burst). O descanso curto já devolve 50% do PM entre lutas, então a assimetria não starva o caster. É a fantasia de cada arquétipo (gladiador que não cansa × mago que explode e raciona) — não unificar.
- **Coroa Vermelha (Ares/Marte):** mantida a invulnerabilidade total (momento épico), mas movida para 1×/dia e custo 40 Ímpeto, para não ofuscar os avatares dos Big Three (que não dão invuln total).
- **Onda de Morte (Hades):** ganhou piso — só mata alvos com PV ≤ 50%. Evita deletar um boss cheio num único teste de área; continua sendo a foice do deus da morte contra os já feridos.

## Balanceamento (auditoria de 2026-07 — passe "fora do eixo Destreza")

Primeira leva de ajustes de uma revisão geral de armas/armaduras/atributos. Foco: coerência e "cada opção interessante de usar", **sem** ainda mexer no eixo Des×For (que fica para um passe dedicado seguinte).

- **Alcances de arremesso — escada coerente.** Antes eram incoerentes (adaga, lança e tridente todos a 6 m; lança de arremesso a 20 m). Nova lógica por *quão dedicada ao arremesso* é a arma: adaga **9 m**; lança/tridente/machadinha **12 m** (haste ou arma de mão jogada, não dedicada); lança de arremesso **20 m** (dedicada, segue rainha); funda 30 m. Veles ainda soma +3 m.
- **Xifos ganhou identidade.** Espada curta e gládio eram idênticos (1d6/leve), mas só o gládio tinha propriedade ("formação"), deixando o xifos estritamente dominado. Xifos agora tem **ágil** (ataca mesmo após Correr) = a lâmina móvel do escaramuçador, contraste com o gládio de linha.
- **Armas de fogo trazidas ao patamar dos arcos.** Eram dado duplo (2d6–2d10), ofuscando o arco. Agora single-die faixa-arco: pistola **1d8** (oculta, 1 mão), rifle **1d12**, espingarda **2d6** cone, SMG **1d8**/tiro, fuzil **1d10**/tiro. Identidade passa a ser cadência/capacidade/ocultação + freio da munição (balas de bronze 5×), não dano bruto.
- **Estilo novo: Pistoleiro — Fogo e Pólvora.** Preenche o vazio de estilo para armas de fogo (Sagittarius cobre arco/besta). Arquétipo oposto ao Sagittarius: móvel e de perto (recarga livre, saque rápido +1d6 em movimento, akimbo, descarga em 3 alvos no Mestre) vs. o arqueiro parado que mira longe. **Único estilo sem ancestral afim** — pólvora não corre no sangue, só se aprende no mundo mortal (background/treino). Reforço temático deliberado.
- **Demeter/Ceres: +2 Int, +1 Des** (era +1/+1). Corrige o único chassi fraco dos dois lados (só +2 de atributo *e* 3d6 de PV). Sobe ao nível das pares 3d6 (Hefesto/Dionísio/Afrodite = +3 total) reforçando o que ela é: conjuradora/suporte de Int, sem inflar PV.

## Balanceamento (auditoria de 2026-07 — eixo Destreza × Força)

Segundo passe. Diagnóstico refinado: a ofensa **já** estava razoável (arremesso = Força pelo braço; tiro = Destreza pela mira — divisão que já existia de fato, só não estava dita). O que inflava a Destreza estava **fora da ofensa**: AC e iniciativa. Consertando esses dois, o eixo se equilibra sem reescrever armas nem magias.

- **Escada de armadura desinvertida.** Antes, um Des alto de armadura leve chegava a AC 18, ≥ placa (17), sem penalidade — a armadura mais pesada dava *menos* retorno. Correção em três eixos combinados (só o teto ou só o bônus não resolvia):
  1. **Teto de Destreza por categoria:** Leve conta até +3, Média até +2, Pesada não conta.
  2. **Bônus retrabalhados por faixa** (sem sobreposição): Leve +1..+3, Média +4..+5, Pesada +7..+8 (placa/panóplia completa subiu a +8).
  3. **Preço por categoria:** Média e Pesada dão **desvantagem em Espreita** (barulhentas); Pesada ainda −1,5 m. A Leve não custa nada — é o que a salva de virar lixo (o furtivo veste leve de propósito).
  - Resultado (item topo de cada faixa): teto de AC **Leve 16 / Média 17 / Pesada 18**. A maior AC volta a ser do tanque, e é a **única** rota de AC alta para quem tem Des baixa (a Média com Des baixa dá 13–15). Cada faixa serve um build distinto por *nível de Destreza*, não só pelo teto.
  - **Nomes retematizados** (fora do registro D&D): panóplia hoplita, peitoral de bronze, lorica hamata/segmentata, linotórax, pele de fera, couro tacheado — bronze celestial/ouro imperial reservados ao topo de cada faixa.
- **Iniciativa deixa de ser monopólio da Destreza — via Instinto.** Quem é **treinado na Habilidade Instinto** pode usar Int no lugar de Des na iniciativa. Gate por investimento (custa um slot de Habilidade) e temático (ler a briga chegando, não reflexo puro). Não cai no colo de todo caster; o Des-build segue rápido como sempre. Descartado o "Des ou Int sempre" (o autor achou que não fazia sentido dar de graça).
- **Panteão mantido temático.** O viés de Des (Hermes +3, Hades/Apolo +2...) reflete identidade, não desbalanço — com AC e iniciativa consertadas, o build de Força já fica atraente para Ares/Poseidon/Hefesto. Não se reabriu a Parte I/III dos Poderes.

> **Ainda fora do escopo, por escolha do autor:** retoques em armas pesadas (machado/maça) e a revisão da Coroa Vermelha (invulnerabilidade do Ares).

## Limpeza de armas exóticas (2026-07)

Corte das armas que destoavam do cenário greco-romano:

- **Removidas:** **Sai** e **Taitai** (leves, de origem okinawana/incerta); **Tonfa** (especial, okinawana); **Cimitarra** (pesada, persa/oriental — além de **redundante** com o kopis, a espada curva grega que o sistema já tem).
- **Renomeada:** "Bastão de combate (bo)" → **Bordão** (o objeto é universal; só o nome "bo" era japonês). O "Bastão" curto de 1 mão foi mantido — são armas distintas (baton × bordão de duas mãos).
- **Ripples ajustados:** o estilo **Dimachaerus** deixou de listar sai/taitai (usa adaga/gládio/xifos); no Bestiário, as "cimitarras" da **Campe** viraram **kopis** (lâminas curvas gêmeas), incluindo o drop.
- **Mantidas por opção do autor:** as medievais-europeias (espada longa, espada de duas mãos, martelo de guerra, morning star, machado de batalha) — anacrônicas, mas staples de fantasia aceitos. Se um dia quiser purismo total, é o próximo alvo natural.

## Estrutura do turno — reskin temático + Rompante (2026-07)

Objetivo do autor: o turno não podia **ler** como D&D (ação/reação/movimento), mas **sem** perder a rigidez cíclica (que é gramática tática universal, não marca de D&D — tirar viraria "festa"). Solução em duas camadas:

- **Reskin de vocabulário** (mesma mecânica, nome do universo): ação principal → **Feito**; movimento → **Deslocamento**; reação → **Reflexo**; ataque de oportunidade → **Bote**; ações livres → **Gestos**; rodada → **assalto**. Para não reescrever todas as magias/estilos/monstros (que dizem "1 ação", "reação"), o Livro do Jogador 8.2 traz uma **nota de equivalência** ("onde disser 'ação', leia Feito", etc.). Propagar os termos por todo o corpo do texto fica como tarefa futura opcional.
- **Rompante** (elemento estrutural novo, a "cara de PJ"): 1 por turno, grátis, o instinto de batalha do semideus (TDAH-como-superpoder, canônico no Rick). Menu: Improvisar / Provocar / Firmar-se / Rompante de Domínio. **Nunca é um segundo ataque** — é textura heroica, contida, sem recurso acumulável, para não desestabilizar o balanço de dano nem os estilos. O autor notou que estruturalmente ele "rima" com a ação-bônus do 5e (shape inevitável de um beat grátis por turno); aceito como solução provisória — **fica aberto para trocar** se surgir algo mais autoral.

## Rompante de Domínio por deus + Afrodite + espingarda (2026-07)

- **Rompante de Domínio por ancestral.** Evolução do Rompante genérico: cada deus tem um Rompante-assinatura que ocupa a vaga da antiga "Faísca do Domínio". Tabela dos 11 gregos **+ os menores/romanos exclusivos** (Hécate, Hipnos, Íris, Tique/Fortuna, Eros/Cupido, Terminus, Belona) no Livro do Jogador 8.2.1; romanos herdam o par grego; Sangue Plural/Bênção/mortais definem com o Mestre. **Guardrail deliberado:** todos são efeitos pequenos (±1, nudge, utilidade), grátis, 1/turno, nunca um ataque a mais. É o que dá "cara de PJ" ao turno sem inflar dano nem economia de ação.

## Revisão geral (2026-07)

Passe de conferência de tudo que a auditoria de 2026-07 mexeu. Achados e o que foi feito:

- **[CORRIGIDO] Provocar eclipsava os Rompantes de Domínio.** O Provocar genérico dava Abalado (desvantagem) — muito acima dos ±1 por deus, então ninguém usaria o do próprio deus — e ainda estava com "teste de Carisma" sem DC. Rebaixado para **−1 no próximo ataque do alvo contra você** (sem rolagem, mesmo patamar dos de Domínio). Agora Provocar é a opção "banter" universal e os de Domínio são as versões temáticas — todos no mesmo nível.
- **[CORRIGIDO] Nota de equivalência ampliada** para cobrir "ação livre/grátis → Gesto" (usada pelo estilo Pistoleiro e por fichas de monstro).
- **[CORRIGIDO] Ficha de personagem** atualizada: iniciativa "(ou Int, se treinado em Instinto)" e um lembrete de **Turno** (Feito/Deslocamento/Rompante/Reflexo) nos Lembretes de mesa.
- **[CORRIGIDO] Empilhamento de "2× por turno".** Havia várias fontes de ataque dobrado (Ares Frenesi, Hermes Velocidade dos Deuses, Afrodite Dança da Lâmina, estilo Dimachaerus) sem regra de acúmulo — pela leitura crua, dois multiplicadores passivos viravam 4 golpes/turno de graça (Dança + Dimachaerus a partir de ~nv15). Diagnóstico: **não escala com o nível** (ataque extra só vem de features destravadas, não de progressão embutida); o problema era só a **multiplicação** de multiplicadores. Regra adicionada em 8.2 ("Ataques extras não se multiplicam"): **vale o maior** — nunca soma nem produto. Gatilhos pontuais dos estilos (1×/rodada, ao derrubar) valem por cima; Feitos-inteiros-a-mais do Hermes (Velocidade dos Deuses/Mercurial) são a exceção proposital, mas os ataques dentro de cada Feito seguem a mesma regra. Optou-se por "vale o maior" (e não "+1 por fonte") para evitar builds absurdas.
- **[CIENTE — intencional] Rompante é buff só dos heróis.** Monstros não têm Rompante; um grupo de 4 ganha um ±1 coletivo por rodada. É de propósito (heróis são especiais), e o efeito é minúsculo — o Mestre aperta a dificuldade um tico se sentir. Sem mudança.
- **Verificado OK:** README sem referências velhas; teto de AC da pesada (placa +8 + escudo) sobe só +1 vs. o que já existia; Vênus herda as Escolhas novas de Afrodite; nenhuma referência órfã às armas removidas nem à antiga "Faísca do Domínio".
- **Afrodite — fim do eixo-chicote, charmspeak como identidade.** O kit marcial afunilava no chicote (3 de 7 Escolhas) e era fora do cânone (Piper luta de adaga + charmspeak, não de chicote). Trocas: `Perícia com Chicotes` (nv1) → **Voz Encantada (Charmspeak)**; `Chicote Relâmpago` (nv10) → **Dança da Lâmina** (adaga finesse 2×/turno). `Chicote de Espinhos` (nv3) fica como a opção-chicote de sabor. **Afinidade de estilo removida** (era Retiarius): a arma de Afrodite é a voz, não uma escola de gladiador — ela aprende estilos só por treino, sem o de graça na criação.
  - **Coerência da charmspeak (alerta do autor):** a Voz Encantada é só o **canal** (entregar charme/medo/comando pela voz, à distância; alvo precisa ouvir e entender), **sem conceder vantagem**. Assim ela *habilita* o resto do kit em vez de anular Língua do Amor / Beleza Inescapável / Criar Simpatia (que dão a vantagem) ou os efeitos de toque/beijo (Beijo que Cura continua toque). Vênus herda tudo pelo "idêntico a Afrodite".
- **Espingarda.** Era a única arma de fogo a dar dano **cheio** a vários (2d6 × 3 alvos), pisando no AoE das magias. Agora: **alvo principal 2d6; até 2 vizinhos no cone levam metade (1d6)** — identidade de dispersão preservada, sem o abuso.

## Desambiguação de descrições de poderes (2026-07)

Passe de redação sobre **todas** as habilidades usadas pelo jogador (Livro dos Poderes inteiro + Estilos/armas do Jogador). Objetivo do autor: descrições **certeiras**, sem interpretação aberta. Nada de mecânica nova de balanceamento — só tornar explícito o que estava implícito. Três convenções, aplicadas de ponta a ponta:

1. **Condição solta → termo canônico da 6.5 + glosa curta.** "Perde a próxima ação" vira "fica **Atordoado** (perde o próximo Feito)"; "prende" vira "**Restrito** (escapa gastando 1 Feito)"; etc. A glosa evita obrigar consulta constante ao quadro de Condições.
2. **Custo de ação em toda habilidade ativa.** Prefixo **Feito** / **Reflexo** / **Gesto** na célula de efeito (magias de ritual/crafting recebem "(fora de combate)", que já implica não ser Feito de turno). Tira a inferência "isso deve custar uma ação".
3. **"Bloqueia 1 ataque" definido.** Ataque defensivo pontual (Controle Parcial Ventos/Água) = **Reflexo** que anula 1 ataque. **Escudos sustentados** (concentração `[C]` ou construídos — Escudo Aéreo, Redemoinho Defensor, Escudo Vulcaniano, Barreira Mágica de Terminus) anulam **1 ataque por rodada automaticamente** (a concentração/construção já pagou o custo). Racional do autor: a maioria deve gastar Reflexo, mas escudo que fica girando/de pé anula sozinho.

Sub-regras da mesma lógica: **"perde N turnos" = Atordoado por N turnos** (não trava total — Paralisado/Inconsciente ficam para travas de verdade); **"paralisado" usado para admiração/visão/medo** virou Atordoado ou Fascinado (Paralisado real dá crít-automático no corpo a corpo, punição grande demais para esses efeitos); **"invulnerável" = imune a dano**; **"vulnerável" = próximo ataque contra ele é crítico automático**.

**Lacunas fechadas** (efeitos que cobravam custo sem dizer o que faziam): empurrão padrão = 3 m; Convocação de Tempestades (Zeus) 8d6/raio 30 m; Anjo do Olimpo "se rende" = não ataca por 3 turnos; Flecha de Doenças (Apolo) ganhou 4 níveis com efeito mecânico; Aquecer Metal (Hefesto) 2d6 fogo/turno + −2 AC; Domínio Elemental Avançado (Hécate) alcance/duração; Profundezas Despertas (Poseidon) = 1d6 criaturas hostis aos inimigos (stats por 7.6). **Correções de força que já eram exageros:** Soco de Expulsão (knockback 30 m→6 m), Lâmina e Toque do Estígio (paralisia 1-7 turnos sem teste → save + Paralisado 1d4), Charme Múltiplo (ganhou teste de resistência). **Reconciliações:** Toque Ardente e Manto Perolado marcados `[C]` (a 7.3 já os citava como exemplos de concentração); flecha **Sônica** deixou de redefinir "atordoado" ao contrário da 6.5.

Duas regras nasceram deste passe (fechavam buracos, não inflam poder):
- **Avaria de armadura (Jogador 8.5.7).** Efeitos que danificam/derretem armadura, cerco, ou crítico (opção narrativa) dão **−1 no bônus de AC** por avaria (acumula; 0 = inutilizada). Conserto: **Soldar Brecha** (Hefesto) 1d8 em combate, ou ferreiro fora de combate; néctar/ambrosia não consertam metal; escudo e AC de magia não sofrem avaria gradual. Motivo: o Soldar Brecha citava "AC perdida" sem que existisse regra de perder AC — ficava órfão. Agora dá nicho a Hefesto ("consertar sob fogo").
- **Reflexo da sorte (Tique).** Os poderes reativos da Tique (reroll, crítico forçado, trocar sortes, esquiva) usam Reflexo, mas **não gastam o Reflexo normal da rodada** (1/rodada à parte, respeitando custos/limites). Sem isso, a fantasia de "mexer no acaso o tempo todo" morreria consumindo a única reação da personagem.

## Revisão completa + cânone (2026-11)

Leitura de ponta a ponta dos três livros, ficha e aventura. Decisões do autor nesta rodada:

- **Cânone corrigido:** Bianca di Angelo não usava pistola (era Caçadora, de arco) — nota de armas de fogo reescrita (o Pistoleiro é licença do sistema); Frank é descendente distante de Poseidon (Periclímeno), não neto; as lâminas-anel são as **sicas da Meg McCaffrey** (Deméter), não "espadas de Nova Roma"; Reyna vira Caçadora em *A Tumba do Tirano*; Empousai têm perna de **jumento**; Festus é autômato do chalé de Hefesto; Tifão caiu quando Poseidon se juntou aos Olimpianos (Hades não é Olimpiano); profecias de missão são em 2ª pessoa; verso quebrado da Profecia dos Sete consertado. **Mantido por decisão do autor:** Belona sem par grego (dito no cânone); a ave de Afrodite é **só a pomba**.
- **Bronze celestial não fere mortais** (atravessa); **ouro imperial fere todos**.
- **Origens raras (Jogador 4):** filhos dos **Três Grandes** só com aval do Mestre, máx. 1 por grupo, com *Faro de Poder*; **Filho do Fogo** (imunidade total a fogo, à la Leo) só por concessão ou 1 no 1d100 — a herança nv 13 de Hefesto virou *Pele de Forja* (imune só a fogo comum).
- **Hera/Juno** aceitam heróis de qualquer gênero e linhagem (Percy, Jason); só **relutam com filhos de Zeus/Júpiter** (Termo mais duro). **Minerva** só tem rancor de Roma antes da devolução da Atena Partenos. **Netuno** mantém o kit naval, mas é mau agouro em Roma.
- **Hades × Plutão separados:** riquezas e gemas amaldiçoadas (Hazel) foram para Plutão; Hades ganhou morte/sombra (Sentir a Morte, Legião de Ossos, Chamar as Fúrias, Ouvir os Mortos, Salvo-conduto de Caronte).
- **Apolo:** sai "o futuro escapa pela boca" (quem profetiza é o Oráculo); entra a **Maldição em Versos** (Escolha nv 3), com efeito mecânico e de interpretação.
- **Hipnos:** o Avatar não ressuscita mais (morte é de Tânatos) — virou *Irmão da Morte* (puxa para o sono quem falharia o 3º Teste das Moiras).
- **Estilos afins:** Hades/Plutão → **Veles** (Nico luta com uma espada só); Deméter/Ceres → **Dimachaerus** (Meg).
- **Magia com dois modos (Jogador 7.8):** **ataque mágico** (d20 + mod PM + BDP vs. AC) para raios/projéteis/toques; **resistência** (alvo vs. DC de magia, metade do dano em área) para áreas e controle. Falha de magia (7.5) só no d20 do conjurador. **Armas conjuradas** contam como dominadas.
- **CDs fixas eliminadas:** 104 CDs numéricas dos Poderes viraram "(DC de magia)"; poderes especialmente difíceis usarão "DC de magia +2". Armas e estilos usam **DC marcial** (10 + mod da arma + ½ BDP).
- **Monstros ganharam bônus por Tier** (ataque +4/+6/+8/+10; resistência +2/+3/+4/+5 somado ao mod). Antes não havia regra nenhuma para monstro atacar ou resistir.
- **Recursos:** descanso curto **até 2 por dia**; refeição cura 1× por descanso longo; truques que davam Ímpeto ilimitado viraram 1× por descanso longo.
- **Lacunas fechadas (Jogador 6.3.1/6.5/7.1/7.4):** duas armas, agarrar, cobertura, flanquear, tiro adjacente, alcance longo, dano desarmado, requisito de For, condições Invisível/Vulnerável/Imobilizado/Petrificado, durações em rodadas, "encontro = combate", tipos de bônus, stats de invocação (com ataque e "invocação maior").
- **Balanceamento:** controles sem teste ganharam teste (Flecha Cômica, Voz do Trovão, Forjar Algema, Invocação de Vinhas, Domínio das Rosas, Grito de Guerra); Dança da Lâmina virou ativação 1×/combate; Frenesi Compartilhado limitado a 2 aliados; Flechas Múltiplas a 4 alvos distintos; Lança Dado = d20 + nível; Canção Hipnótica +1 alvo por 5 PM (máx. 4); Exército de Zumbis = horda como 1 invocação; custos alinhados (Cura Profunda 15, Manto Perolado 25, Escudo Sombrio 20); magias fracas de nível alto reforçadas (Invocação de Raio 6d10, Inverno Eterno 4d6, Tsunami/Convocação 10d6). **Chassis:** Poseidon +2 For/+1 Des, Belona +2 For/+1 Des, Hipnos +2 Int/+1 Car, Tique +2 Car/+1 Des, Terminus +3 Int.

## Progressão, cardápios e centralização (2026-11)

- **Progressão sem níveis vazios:** BDP sobe a cada 4 níveis (+2 a +6); níveis 8, 12 e 19 dão **Aprimoramento**. Aprimoramento e flex usam **um cardápio só** (Jogador 5.3): Escolha, Habilidade, atributo, Estilo novo ou o **Vínculo** do deus.
- **Rituais (Jogador 7.9):** magias só de fora de combate não ocupam slot — o herói conhece todas as do seu deus. Assim utilidade não disputa vaga com combate.
- **Truques:** os 3 de nv 1 vêm de graça no nv 1 (são sabor).
- **Meta de cardápio:** todo deus tem **≥9 Escolhas** (o jogador pega 6 + Aprimoramentos, então há escolha de verdade) e **≥10 magias de combate**, com opção no nv 1 e no nv 20. Antes, a maioria tinha 7 Escolhas para 6 vagas, e Íris tinha 6 (zero escolha).
- **Reformas de identidade:** Hermes = ladrão, estrada e movimento (sem sono, que é de Hipnos — não emprestar arquétipos); Hipnos = sono 1×/combate sem restrição de barulho/sol + **exaustão como arma** (some no fim do combate, máx. 3) + Lete; Íris = luz, suporte e **Juramento do Estige** (mitologia, não exceção do cânone); Hefesto = tabela de **Forja mágica** + autômatos com stats + Colosso de Bronze genérico (não o Talos). Deméter ganhou **Terra Viva** (cria a vegetação de que depende). Guerreiros entram em combate com Ímpeto ≥ nível + mod For.
- **Guerreiros e estilo afim:** Ares/Marte/Belona têm 2 estilos, mas só **um** é afim (o jogador escolhe na criação). Descartados: os dois acelerados (forte demais — o patamar Mestre é o maior salto de dano) e nenhum acelerado (deixaria o guerreiro atrás dos outros deuses).
- **Karpos Leal é Vínculo, não Escolha:** opção de Aprimoramento, decisão do jogador; o Mestre só ajuda a encaixá-lo na narrativa. Invocação de 10 min, não companheiro permanente.
- **Centralização (pedido do autor):** cada assunto num lugar só. Origens raras (Três Grandes, Filho do Fogo, Sangue Plural) reunidas na seção 4; progressão inteira na tabela 5.2 + 5.3; DC marcial junto das propriedades de arma (8.4.2-b). Ao criar regra nova, expandir a seção que já trata do tema.

---

> O registro completo das decisões de balanceamento/consolidação até a v1.0.0 (atributos, PM, Sangue Plural, Bênção, a rodada de refino de 2026-06, etc.) está na memória do projeto, fora do repositório.
