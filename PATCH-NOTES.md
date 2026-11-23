# Patch notes — da R66 até a R139

Todas as mudanças desde a **R66 (v1.0.111-snapshot.66)**, a última versão publicada aqui, até a **R139 (v1.0.184-snapshot.139)**. Da mais nova para a mais antiga. Cada versão inclui tudo o que veio antes.

## R139 — 1.0.184-snapshot.139
- **Mapa da Ilha (`club-island-r72.js`):** todo toque primário descarta ponteiros antigos guardados, evitando uma pinça falsa que fazia o mapa pular ao dar zoom.
- **Tapete (`balanced-table-r128.css`):** pokébola do adversário (posição 107%) e a sua (-4,6%) centralizadas no Ativo.
- **Escolher deck (`index-otevawBu.css`):** título fixo, lista rolável com folga, linhas compactas e fundo branco.
- **Atualizador (`app-update.js`):** versão interna R139.

## R138 — 1.0.183-snapshot.138
- **Arrastar do Banco (`match-tfSzEL_l.js`):** a carta arrastada fica ~0,95 largura acima do dedo; alvo de soltar calculado no mesmo ponto.
- **Avisos (`index-otevawBu.css`):** mensagens acima do botão Informações (z-index 30).
- **Troca Relâmpago (`club-island-r72.js`):** raridade por extenso (carta Comum/Incomum/Rara).
- **Muk (`ai-rules.js`):** marca de Toxic Gas só em Pokémon com habilidade (Pokémon Power).
- **Decks (`decks-BKo9xSNp.js`):** aba Deck Gen 2 só aparece com Johto alcançado.
- **Escolher deck (`download-BiFiwrDT.js`, `index-otevawBu.css`):** seletor em lista vertical, como o cartão Seu deck.
- **Atualizador (`app-update.js`):** versão interna R138.

## R137 — 1.0.182-snapshot.137
- **IA (`ai-worker-BI9LqZXq.js`):** depois de escolher um ataque cujo dano depende de moeda, a IA confere os ataques fixos disponíveis e troca para o fixo se ele nocauteia com certeza ou dá pelo menos o dano médio do ataque de moeda (antes o Nidorino insistia no Double Kick em vez do Horn Drill).

## R136 — 1.0.181-snapshot.136
- **Barraca da feira (`fair-design-r132.css`):** cartões em 3 colunas; a barraca cabe inteira sem rolagem.
- **Aviso do duelo (`index-otevawBu.css`, `match-tfSzEL_l.js`):** a caixa cresce na altura para mostrar o texto inteiro (fonte 13px); o aviso "Arraste um Pokémon do Banco" quebra linha e fica dentro da tela.
- **Lata de booster (`booster-can-r112.css`):** removido o retângulo de brilho fixo que ficava atrás da lata 3D.
- **Mesa (`mesa-r100.css`):** contador do deck do adversário no lado direito, como o do jogador.

## R135 — 1.0.180-snapshot.135
- **Moeda do adversário (`index-D85to97h.js`):** líderes e pupilos de ginásio (Kanto e Johto) usam a moeda do líder; pupilos e mestres de clube usam a moeda do mestre; Rocket usa a GR. Antes o preset padrão já vinha com a Chansey e a troca nunca acontecia.

## R134 — 1.0.179-snapshot.134
- **Snorlax em Kanto (`snorlax-trade-r134.js`, `battles-Cn81xwEW.js`, `kanto-map-r74.js`):** dois pontos de troca especial depois do ginásio de Celadon. Estrada ao sul de Lavender: 1 Poké Flute pela moeda do Snorlax. Ponte da Cycling Road: 1 Poké Flute pela carta Hungry Snorlax. A rota e o ginásio de Fuchsia ficam bloqueados até fazer pelo menos uma; saves que já avançaram em Fuchsia não travam. Aviso de última cópia ou carta usada em deck, com confirmação.
- **Hungry Snorlax (`intro-gb-cards-r103.js`, `ai-rules.js`, `match-tfSzEL_l.js`, `food-counter.webp`):** GB Promo GB-143. Swallow Food coloca 1 Food counter (máx. 2); Full Belly Rollout remove todos e causa 20 + 30 por contador. Ícone de Food counter na mesa.
- **Marowak (`bone-counter.webp`):** novo ícone do Bone Counter (Rare Bone).
- **Cartas Dark GB (`intro-gb-cards-r103.js`, `ai-rules.js`, `gb-reserved/dark*.webp`):** Dark Haunter, Dark Gengar (Play Tricks), Dark Marowak, Dark Ninetales (Mislead: oponente pula a compra) e Dark Starmie (Rebirth). Entregues ao vencer o líder do Esconderijo Rocket de Celadon (também para quem já venceu).
- **Giovanni (`index-D85to97h.js`, `intro-gb-cards-r103.js`):** além de créditos e boosters, dá a moeda Nidoking e a carta Giovanni's Nidoking (GB-034; Command dá +10 aos Giovanni's Nidoran♂ e Nidorino; Rumble impede o recuo).
- **Limite por nome:** cartas GB com o mesmo nome de cartas de outras coleções (Dark Haunter, Dark Gengar, Giovanni's Nidoking) dividem o limite de 4 cópias.
- **Moedas (`index-D85to97h.js`, `coins-Bfxy3e5W.js`, `coins/*.png`):** Vileplume (Nikki), Nidoking (Giovanni), 8 moedas dos líderes de Johto, Persian, Jigglypuff; nova moeda GR da Equipe Rocket ao vencer o Chefe Rocket da primeira ilha (os Rockets também passam a usá-la). Moedas-surpresa do Sam removidas.
- **Atualizador (`app-update.js`):** versão interna R134.

## R133 — 1.0.178-snapshot.133
- **Feiras regionais (`fair-design-r132.js`, `fair-design-r132.css`, `fair-scenes-r132/*.png`, `fair-ui.js`, `fair-stalls-r129.js`, `index.html`):** Ilha, Celadon e Goldenrod com cenário e paleta próprios; banner sem ícone sobreposto; seis participantes e três bolinhas de exigência. **Negociar** abre troca 1:1 (sua carta à esquerda, a do NPC à direita, com escolha e filtros); **Barraquinha** abre só Comprar e Vender. Preços em ₽, cartas inteiras e ação em rodapé separado. Regras, economia e persistência preservadas. Integração feita pelo Gemini.
- **Atualizador (`app-update.js`):** versão interna R133.

## R132 — 1.0.177-snapshot.132
- **Tipo da semana (`index-D85to97h.js`, `events-mosaic-r98.js`):** na 5ª vitória o booster não entra mais sozinho; o card e a linha do evento mostram "Resgatar" e o botão "Resgatar booster". Semanas já concluídas antes não geram resgate extra.
- **Eventos (`events-mosaic-r98.js`):** a Aula do Professor Mason sai do rodapé e fica acima do cartão do dia.
- **Escolha de Energia (`match-tfSzEL_l.js`):** o descarte de Energia (golpe, Treinador, recuo) mostra a carta de Energia, com legenda do Pokémon, em vez de ícone e texto.
- **Mesa (`mesa-r100.css`, `match-tfSzEL_l.js`):** contador do deck do adversário colado ao canto do deck; o cabeçalho do adversário não mostra mais o nível e o turno.
- **Atualizador (`app-update.js`):** versão interna R132.

## R131 — 1.0.176-snapshot.131
- **Troca de posição (`match-tfSzEL_l.js`):** a carta que muda de lugar (banco para ativo, recuo, Switch, promoção) não aparece mais piscando no destino antes de deslizar; ela fica oculta até a animação começar.
- **IA (`ai-worker-BI9LqZXq.js`):** ao passar do limite de 7 cartas na mão, a IA descarta primeiro as cartas de menor valor (antes escolhia as de maior valor, como energia). O Professor Oak deixa de ser jogado com energia na mão ou com a mão cheia, quando a energia do turno ainda não foi ligada.
- **Atualizador (`app-update.js`):** versão interna R131.

## R130 — 1.0.175-snapshot.130
- **Gazeta por região (`gideon-r129.js`, `gideon-r129.webp`, `tanaka-r129.webp`):** Gideon (Gazeta de Kanto) anuncia Gym Heroes e Gym Challenge; Tanaka (Gazeta de Johto) anuncia Neo 1 a 4 e VS. A janela de fala mostra o nome e o retrato de quem fala.
- **Decks Gen 1 e Gen 2 (`deck-gen-r129.js`, `decks-BKo9xSNp.js`, `index-D85to97h.js`):** a aba Decks ganha Deck Gen 1, Deck Gen 2 e Modelos. Gen 1 não aceita cartas Neo/VS e não pode ser usado em Johto; Gen 2 aceita no máximo 15 cartas de outras regiões (energias básicas não contam) e vale em Johto, Kanto e na Ilha. A regra vale na montagem do deck.
- **Johto (`johto-deck-rule-r129.js`, `battles-Cn81xwEW.js`, `johto-ui-r127.js`):** os duelos de Johto só aceitam deck Gen 2 e o seletor esconde os Gen 1. No primeiro encontro sem deck Gen 2 válido, o Tanaka explica a regra e entrega um deck do Neo Genesis à escolha (Cold Fusion ou Hotfoot), uma única vez.

## R129 — 1.0.174-snapshot.129
- **Barraquinhas das feiras (`trade-engine-r129.js`, `fair-stalls-r129.js`, `fair-ui.js`):** cada NPC tem uma barraquinha que vende e compra cartas, com preços acima ou abaixo da Gazeta do dia; negociação com contrapropostas, troco opcional e paciência sorteada.
- **Feira aos sábados e domingos (`fair-engine.js`):** a janela da feira agora abre nos dois dias.
- **Gazeta noturna (`gazeta-night-r129.js`, `sam-pijama-r129.webp`):** opção nos Ajustes para a Gazeta fechar das 22h às 8h; Sam de pijama; Saldão da madrugada com 3 cartas e pacotes em promoção.
- **Trocas:** a tela antiga de Trocas não aparece mais ao fechar a Feira (a janela abre direto pelo mapa).
- **Side deck (`pocket-assets-r123.css`):** texto não vaza mais por trás do cabeçalho.
- **Coleção:** aba Receitas removida.
- **Duelo:** dano de confusão considera Fraqueza e Resistência; animação de troca corrigida; tabela balanceada.

## R128 — 1.0.173-snapshot.128
- **Desistir do duelo salvo (`index-D85to97h.js`, `battles-Cn81xwEW.js`):** o aviso "Há um duelo suspenso" (ao iniciar outro duelo) ganhou o botão **Desistir do duelo salvo**, que encerra o salvo como derrota sem nova confirmação e segue iniciando o duelo novo. Retomar e Cancelar continuam como antes.
- **Gazeta (`ui-v3-r121.css`):** a barra de abas principais é uma faixa própria, com borda, sombra e cantos arredondados; em **Avulsas** cada coleção é um cartão separado; a tela de **Pacotes** fica travada (sem rolagem) e o booster ficou um pouco maior.
- **Atualizador (`app-update.js`):** a versão interna do jogo passou a ser a R128 (antes ficava na R127 e a atualização era oferecida em loop).
- **Colecionador Viajante / Imakuni (`events-BBOmf8TN.js`, `portraits-hd-r96/imakuni-bust-r128.png`):** retrato de corpo inteiro trocado por um busto; textos e etiquetas da conversa legíveis no tema claro; falas e aviso do Sam sem "trem" (agora barco/cais, por causa do porto).

## R127 — 1.0.172-snapshot.127
- **Johto (`johto-*-r127.js`, `johto-r127.css`, `assets/johto-r127/`):** novo mapa com oito ginásios e 64 encontros de 60 cartas (24 rotas, 32 pupilos, 8 líderes, mais rotas extras); embarque por Kanto concluído; nenhuma aba de Johto aparece antes do requisito cumprido.
- **Neo Genesis, Discovery, Revelation e Destiny:** boosters liberados por etapa de Johto (Neo 1 na chegada, Neo 2 após 3 líderes, Neo 3 após 6, Neo 4 após o Retorno Rocket); decks temáticos Neo (550/600/650 créditos).
- **Cartas avulsas na Gazeta (`johto-content-r127.js`):** todas as cartas de Base, Jungle, Fossil, Rocket, Gym 1, Gym 2 e Neo 1–4 são vendidas conforme a coleção libera; Pokémon VS não é vendida avulsa; energia básica 2 créditos.
- **Valores individuais e prestígio (`market-base.js`, `neo-values-r127.js`):** cada carta Neo tem valor próprio; lista de prestígio aplicada a 202 cartas (Charizard, Lugia, Shining, lendários e iniciais sobem; valores inflados descem); teto 2.500. Versão da tabela `prestige-v1-r128`.
- **Retorno Rocket, Victory Road, Liga e Mark:** Mahogany; Victory Road com cinco duelos; Liga com Will, Janine, Bruno, Karen e Lance; Mark sozinho no cume do Mt. Silver, com apresentação e revanche.
- **Kanto:** Rockets de Celadon e da Silph Co.; Grande Salão na Ilha antes de Kanto.
- **Feiras de troca (`fair-regions-r94.js`, `fair-engine.js`, mapas):** três feiras com ícone próprio (Ilha: quatro coleções principais; Celadon e Goldenrod abrem sem precisar vencer Erika/Whitney); seis trocas por feira; nunca aparecem VS, Intro, GB, Vending nem Promo.
- **Eventos da Gazeta em abas (`events-mosaic-r98.js/.css`):** Hoje, Semana e Especiais, com ponto de aviso quando há prêmio; as regras dos eventos não mudaram.
- **Editor de baralhos (`index-D85to97h.js`):** Pokémon Shining e Miracle Energy limitados a 1 cópia; Unown a 4 cartas no total.
- **Prêmios:** primeira vitória e revanches revisadas (revanche só com boosters); moeda recebida com animação própria.

---

## R126 — 1.0.171-snapshot.126
- **Abertura da Vending Machine com lata 3D (`booster-can-r112.js`, `booster-can-r112.css`, `can-wrap.svg`):**
  - Tela temática própria, com a lata 3D em CSS e a logo; puxar a lata toca som, a lata abre com bolhas, some em fade e aparecem as cartas tiradas. Textura da lata sem emendas e sem metade mais clara; barra de botões sempre visível.
- **Máquina redesenhada (`scene-CiwHyPD9.js`):** corpo azul, latas com o mesmo rótulo da lata nova e faixas coloridas sobre o compartimento "RETIRE AQUI".
- **Bone Counter com arte própria (`bone-counter.webp`, `match-tfSzEL_l.js`, `ai-rules.js`):** ícone do osso na mesa; o ataque *Search for Bone* coloca um Bone Counter se o Pokémon não tiver nenhum.
- **Cartas GB corrigidas (`intro-gb-cards-r103.js`, `ronald-gb-eeveelutions.js`):** Pidgeot (Slicing Wind), Electrode (Sonicboom), Mew (Mystery Attack), Marowak (Wail), Ditto (PS 50) e Flareon (Rage, custo 3).
- **Promos auditadas** contra o texto das cartas verificadas: nenhuma divergência.
- **Pacotes:** a tela preenche o espaço vazio e as cartas passam de forma mais suave na abertura.

## R125 — 1.0.170-snapshot.125
- **Removidos:** animações de ataque estilo Game Boy e o interruptor em Ajustes; cruz amarela ao curar; flash amarelo ao receber golpe (`match-tfSzEL_l.js`, `system-DjmEcSme.js`, `index-otevawBu.css`).
- **Animações sempre ativas** (não seguem mais *Reduzir movimento* do sistema) nas telas de clube, Kanto, Hall e base Rocket.
- **Vending Machine:** Kadabra (Psy Panic, Energy Restore, Energy Shock), Alakazam, Arbok (Deadly Poison) e mais de 20 ataques revisados; 16 ataques que não faziam nada agora têm efeito; Pokémon Tower impede descartar para a mão (`vending-expansion-r112.js`, `ai-rules.js`).
- **Fiel ao texto, sem simplificações:** Caterpie/Tangela (bloqueio de troca), Weepinbell (devolve para o baralho), Boulder Smash/Water Bomb (dano no Banco por unidade).
- **Coleção VS auditada** contra o texto impresso (144 cartas, 176 ataques, 26 TMs): nenhuma divergência.
- Textos de destaque (`printedRuleTextPt`) corrigidos nas cartas alteradas.

---

## R124 — 1.0.169-snapshot.124
- **Animações de ataque estilo Game Boy (`gb-attack-fx-r123.js`, `gb-attack-fx.webp`, `match-tfSzEL_l.js`):**
  - 95 animações (571 quadros) da folha TCG2 GBC, ligadas a 819 ataques por tipo/nome; tocam sobre o Pokémon atingido quando o ataque causa dano (limite de 1,3 s por golpe).
  - Novo interruptor **Animações de ataque** em **Ajustes → Mesa e animações** (`system-DjmEcSme.js`, chave `pk.attackFx`); também respeita *Reduzir movimento* do sistema.
- **Brilhos na abertura de boosters (`booster-glow-r124.css`, `fx-pack-*.webp`):**
  - Raios e anel de luz ao rasgar o pacote; raios dourados girando atrás das cartas raras; halo arco-íris + raios brancos nas holo; brilhinhos piscando por cima. Só CSS, sem mudar sorteio.
- **Ícones Pocket na mesa e no dock (`ai-rules.js`, `match-tfSzEL_l.js`, `index-D85to97h.js`, `pocket-assets-r123.css`):**
  - Novas marcas de efeito: Defesa, Carga, Cura, Recuo +/−; 7 ícones de efeito redesenhados; estrela animada na fraqueza; selos de deck/descarte/ferramenta; ícones de navegação e setas voltar/avançar.
- **Coleções Neo 2–4 (escondidas até a campanha liberar):** Neo Discovery (75), Neo Revelation (66) e Neo Destiny (113, com Dark/Light/Shining/Unown), com regras de motor próprias.
- **Neo 100% e compatibilidade de atualização:** todos os efeitos Neo 1–4 que antes eram só texto agora funcionam (Deep Sleep, Miraculous Wind, Scare, Flash Touch, Chase, EXP.ALL, Legendary Body, travas de Mean Look/Jaw Clamp/Sticky Nectar e outros), mantendo compatibilidade com o `content_hash` de `pokemon-tcg-neo1-user-images@1.0.0` em saves das versões R121–R123.

## R123 — 1.0.168-snapshot.123
- **Holofoil 3D sem sobrepor quadro de evolução (`scenes-CtYWx7MK.js`):**
  - Calibrados os limites UV da janela de arte interna (`goArt` `FULL_PRINTING`: `{ u0: 0.112, v0: 0.492, u1: 0.888, v1: 0.873 }`, e `v0: 0.472` para Treinadores/Fósseis) e aplicado recorte elíptico `uHasEvo` / `evoCut` no shader `voGalaxy` para excluir o medalhão da pré-evolução em cartas Stage 1 e Stage 2.
- **Modo Escuro acessível e completo (`index-D85to97h.js`, `system-DjmEcSme.js`, `ui-v3-r121.css`):**
  - Adicionado interruptor reativo **Modo escuro** (com persistência em `localStorage`) no **Menu do Perfil** (avatar no topo esquerdo, junto de atalho **Ajustes**) e no topo de **Ajustes → Geral**.
  - Tema escuro estendido à barra `.tabs`, popover de perfil, modais, dock, telas de troca, Feira e botões secundários.
- **Repaginação das Telas de Troca (`club-island-r72.js`, `home-D6cY3P3a.js`, `ui-v3-r121.css`):**
  - Novos modais de **Troca Relâmpago** (Mesma raridade) e **Troca Especial** (Promo) com banner do treinador, pílula do tipo, timer em destaque, balão da fala, palco com etiquetas **`VOCÊ RECEBE`** / **`SUA · ×N`** / **`Você não tem`**, seta **`⇄`**, grid **Escolha a carta** (`.swap-grid`) alinhado e atualização visual de `/trades` e Feira de Trocas.

## R122 — 1.0.167-snapshot.122
- **Correção de Boot / Atualização sobre Save Existente (`IMPORT_INVALID`):**
  - Restaurado o `contentHash` original do pacote base (`base@5.9.8`) em `content/manifest.json` e `base-5.9.8-8b50182b5d6f.json` para manter compatibilidade total com bancos SQLite já instalados da R110–R120 sem apagar ou bloquear saves antigos.
  - Regras de desbloqueio (**Jungle** após **3 mestres**, **Fossil** após **6 mestres**) aplicadas em memória via `roadmapUnlockThresholds` dentro do pipeline de catálogo (`zl()`), preservando o hash em disco.
  - Inclui todo o pacote visual V3, correção da pausa no duelo, ajustes da Ilha/Porto/Feira, e ativos/ajustes recentes presentes no bundle web (VS/Neo base de regras).

## R121 — 1.0.166-snapshot.121
- **Redesign Visual V3 Unificado (`ui-v3-r121.css`):**
  - Novo visual Pocket com superfícies translúcidas em **Modo Claro e Modo Escuro**, banner Hero de Campanha atualizado, faixa larga de **Boosters** com os pacotes inteiros sem corte, remoção do card redundante de Trocas da Home, novo ícone de calendário no **Mural de Eventos** e ícones monocromáticos de linha no dock inferior.
  - Todos os menus, balões de fala/toasts, confirmações, modais do Pré-duelo (`Selecione seu deck` sem dica em texto verde do Sam), grade de decks (`Escolher deck` em **3 colunas** sem o rótulo `"60 cartas"`) e seletores de carta no duelo (apenas a carta, sem nome repetido) alinhados ao novo padrão.
- **Pausa Real no Duelo & Navegação Direta:**
  - Novo **Menu do duelo** centralizado com pausa real da sessão/IA enquanto aberto.
  - Botão **Jogar** no dock abre diretamente o mapa da Ilha dos Clubes (`S19`).
- **Ilha, Porto, Feira & Coleções:**
  - **Feira** posicionada na zona comercial superior esquerda próxima ao farol (`428, 205`), **Troca Relâmpago** e pino **`?` do Imakuni** concentrados no **Porto** mantendo os demais ícones do mapa intactos.
  - Desbloqueio rebalanceado: **Jungle** após **3 mestres** e **Fossil** após **6 mestres**.

## R120 — 1.0.165-snapshot.120
- **Holofoil Galaxy / Cosmos nos Detalhes da Carta 3D (`S08` / `scenes-CtYWx7MK.js`):**
  - Novo shader **Galaxy / Cosmos** aplicado exclusivamente nas cartas `HOLOGRAPHIC` dentro do inspecionador 3D, a **50% de intensidade** (`uIntensity = 0.5`), inspirado no padrão clássico WOTC / `simeydotme`.
  - Combina arco-íris diagonal em `color-dodge`, orbes Cosmos com paralaxe em 2 profundidades, estrelas de 4 pontas cintilantes, glitter fino e glare em `overlay` reagindo à inclinação da carta (com suporte a **Reduzir movimento** e brilho suave de repouso).
  - Máscara UV calibrada até a borda inferior real das artes escaneadas (`FULL_PRINTING`: Pokémon clássicas e Trainer/Fossil) e das cartas procedurais, sem afetar moldura, borda amarela, grade da Coleção, mesa de duelo nem cartas `NORMAL`.

## R119 — 1.0.164-snapshot.119
- **Tela Inicial & Menu do Perfil:**
  - Card **Online** renomeado para **Union Room** com o novo ícone orbital azul mantendo o Modo Online (`S63` / `1v1 · Trocas`) ativo.
  - Menu do perfil (`.app-header`) corrigido para abrir sempre acima dos cartões da Tela Inicial; removido retângulo quadrado atrás da barra inferior móvel e ampliado respiro da sombra abaixo do banner da **Campanha**.
- **Troca Relâmpago no Mapa & Nova Tela do Imakuni:**
  - Adicionados até `3` encontros simultâneos de **Troca Relâmpago** no mapa da ilha (pino azul-turquesa/roxo `⇄`, dourado quando promo) ao lado dos `3` duelos (`!`), totalizando até `6` encontros simultâneos com mesmo intervalo (`2–5 min` chegada, `6–10 min` estadia) e **10%** de chance de troca promo.
  - Tela de encontros do **Imakuni** repaginada (diálogo amplo com carta misteriosa, palco de troca e revelação).
- **Union Room / Troca Online (`S63`):**
  - Removida a caixa introdutória `"Trocas seguras..."` antes da sala de troca.
  - Filtros rápidos e modal **Filtros da coleção** exibem somente as coleções normais em que o jogador já possui cartas, com grade ordenada como no Editor de Decks (Pokédex por tipo ou nº da coleção).
  - Tela de conclusão de troca (`online-trade-done`) repaginada em faixas horizontais de 4 colunas acima da barra inferior.
  - Seletor de deck da Union Room unificado com o padrão visual do Pré-duelo.
- **Pré-duelo, Boosters, Batalha & Sam:**
  - Seletor de deck no Pré-duelo e Union Room agora exibe ícones de Energia reais ocultando `COLORLESS` (`Double Colorless` / fallback) para manter o foco nos tipos elementais do deck.
  - Tela **Pacotes / Boosters** compactada para caber sem rolagem vertical em `360px`.
  - Opção de sair da **Aula do Professor Mason (Gazeta)** sem contabilizar derrota (`ABANDONED`).
  - Corrigido sumiço momentâneo ao auto-promover o único Pokémon restante no Banco após nocaute.
  - **Explicação do Sam no Cassino:** ao derrotar 3 membros do Clube Elétrico e liberar o Cassino, o Sam agora apresenta um guia em 3 etapas (`1/3`, `2/3`, `3/3`) explicando o que é o Cassino (caça-níquel e prêmios), como funcionam os Tickets (`10 Créditos = 1 Ticket`, apostas e ganhos no caça-níquel) e como comprar cartas exclusivas na aba **Loja Intro Pack**.

## R118 — 1.0.163-snapshot.118
- **Sala de Troca Online modernizada (`S63` / aba Troca):**
  - Barra superior única compacta (`← Sair`, pílula escura/dourada copiável `SALA <CÓDIGO>` e indicador online do amigo).
  - **Mesa visual com 4 slots por lado:** mostra as cartas reais inteiras em miniatura nos slots (`Você envia` / `<Amigo> envia`), botão `×` para remover da sua oferta, toque em qualquer carta da mesa para abrir o modal de ampliação e contraste nítido entre **Travar Oferta** e **Confirmar Troca** (cinza até ambos travarem, verde quando pronto).
  - **Grade visual e filtros no padrão da Coleção:** exibe apenas cartas obtidas (`quantity > 0`) das **6 coleções normais** (`Base Set` a `Gym Challenge`), com lupa no canto inferior esquerdo, busca por nome, faixa rápida horizontal de coleções e modal **Filtros da coleção** (Coleção, Tipo de Pokémon, Raridade e Tipo de carta). Recibo final de troca atualizado com miniaturas.
- **Menu Decks e Tutorial do Sam:**
  - Botão amarelo **Jogar (`▶`)** no menu **Decks (`S11`)** corrigido para salvar o deck selecionado (`roadmapRememberDeck`) e abrir diretamente a **Campanha (`S19`)** em vez da antiga tela aposentada `S14`.
  - Tutorial guiado do **Sam** atualizado: fala do **Início (`S03`)** ajustada (Campanha, Boosters, Trocas, Mural de Eventos e Modo Online) e etapa antiga de **Jogo Rápido (`S54`)** substituída pela tela real do **Modo Online (`S63`)**.

## R117 — 1.0.162-snapshot.117
- **Modo Online via Cloudflare Workers + Durable Objects (`S63` `/online`):**
  - **Duelos Online (1v1):** criação e entrada em salas por código curto de `5` letras, escolha de `4` ou `6` prêmios, motor autoritativo no servidor com privacidade anti-trapaça (mão, deck e prêmios do adversário ocultos na rede), suporte a reconexão por código + token e **0 recompensas** (sem créditos, boosters ou cosméticos).
  - **Troca com Amigo (Online):** salas ao vivo com até `4` cartas por lado e trava dupla atômica (alterar qualquer carta destrava/desconfirma ambos os lados antes da confirmação final), aviso quando uma carta ofertada está em uso em deck salvo e atalho direto em **Trocas (`S55`)**.
  - **Escopo de coleções no Online:** aceita apenas decks e trocas das **6 coleções normais** (`Base Set`, `Jungle`, `Fossil`, `Team Rocket`, `Gym Heroes` e `Gym Challenge`), bloqueando `GB Promos`, `Vending Machine` e `Intro Pack`.
- **Tela Inicial, Gazeta & Side Deck:** card **Online** conectado com selo `1v1 · Trocas` e sprite oficial `Sleep_Linking_Cord.png`; leque de **Boosters** exibindo apenas coleções já destravadas; aba **Eventos** (`S53`) mantida dentro da Gazeta; cabeçalho sticky com botões **Voltar** e **Concluir** na tela de Side Deck.
- **Sync GitHub (Gist) & Motor Unificado:** corrigido erro `Failed to fetch` ao baixar saves > `1 MB` (`truncated: true` via `raw_url` sem headers bloqueados por CORS + fallback `CapacitorHttp` + compressão Gzip retrocompatível), e motor/IA consolidados em fonte única (`ai-rules.js`).

## R116 — 1.0.161-snapshot.116
- **Tela Inicial finalizada com ativos oficiais do jogo:**
  - **Continuar Campanha:** usa os mapas oficiais da campanha (`Ilha dos Clubes`, `Base Rocket`, `Kanto` e `Grande Salão`) conforme o ato atual.
  - **Gachamon:** usa render 3D oficial da máquina de cápsulas do jogo com badge `GIRO GRÁTIS` + contagem de giros grátis e vales.
  - **Mural de Eventos:** exibe mural de cortiça com calendário e aviso destacado acima da barra `Mural de Eventos`.
  - Inclui também o fundo claro com marca d'água sutil de Pokébola, remoção do botão Jogo Rápido na Home (encontros `!` mantidos), remoção da aba Eventos da Gazeta, economia de 1ª compra/recompra de decks, premiações reajustadas e as 16 novas artes do Intro Pack.

## R115 — 1.0.160-snapshot.115
- **Tela Inicial repaginada & Mural de Eventos:** fundo claro com marca d'água sutil de Pokébola e barra superior mais limpa; removido o botão Jogo Rápido (preservando os encontros `!`); novo card **Gachamon** com badge `GIRO GRÁTIS` + contagem de giros grátis e vales; card **Continuar Campanha** com arte ilustrada dinâmica por ato e selo de progresso; card **Mural de Eventos** com composição temática (troféu + carta holo + raio). A aba `Eventos` foi removida da Gazeta.
- **Economia de decks (1ª compra e recompra):** preços iniciais diferenciados (`500` Base Set, `550` Jungle/Fossil/Team Rocket, `600` Base Set — Reforço, `750` Gym Heroes, `800` Gym Challenge) e recompra baseada na soma das cartas avulsas do deck (sem Energias) com desconto de `25%` / `20%` / `15%`.
- **Premiações de batalha reajustadas:**
  - Membros de Clube: `100` créditos + `1` booster (1ª) / `100` créditos (revanche); Mestres: `250` + `2` boosters (1ª) / `1` booster (revanche).
  - Equipe Rocket: Soldados = `100` + `1` booster Team Rocket (1ª e vitória na revanche); Comandantes = `200` + `1` booster Team Rocket (1ª) / `1` booster Team Rocket (vitória na revanche).
  - Rotas `rt1–rt8`: `120` + `1` booster (1ª) / `50` créditos por prêmio + `1` booster ao vencer pegando todos (revanche).
  - Grande Salão: `750` + `1` booster de cada coleção liberada (1ª) / `240` créditos (revanche).
  - Ronald: `500` créditos ao vencer (ticket e revanche em Kanto); líderes de Kanto (`BOSS`/`FINAL`): `1` booster ao vencer na revanche; encontros aleatórios (`!`): `50` / `100` / `150` créditos.
- **Intro Pack:** atualizadas todas as 16 artes das cartas do conjunto Intro Pack.

## R114 — 1.0.159-snapshot.114
- **Save compartilhado na nuvem entre aparelhos (GitHub Gist secreto):** novo painel na tela **Saves e backups (`S31`)** para conectar um token clássico do GitHub (permissão `gist`), salvando o token apenas localmente no aparelho.
- **Auto-descoberta e sincronização em segundo plano:** o primeiro aparelho cria um **Gist secreto** (`ptcga-cloud-save-v1`) com o pacote oficial `.campaign-profile.zip`; novos aparelhos só precisam colar o mesmo token para restaurar o perfil automaticamente. Sincroniza ao abrir o jogo, ao progredir fora de duelo e ao sair/minimizar, exibindo modal comparativo caso dois aparelhos avancem offline.

## R113 — 1.0.158-snapshot.113
- **Versão consolidada para atualização automática:** inclui todas as novidades de **R112** e **R112-2** com `APP_BUILD = 113` e tag `v1.0.158-snapshot.113` para que versões R110–R112 puxem a atualização automaticamente pelo Sam.
- **Gacha & Booster Can:** pré-carregamento simultâneo dos modelos 3D no boot/Início para abrir direto em 3D sem piscar desenho 2D; `Booster Can` oculta da Gazeta até derrotar **3 Mestres da Ilha**, sem dicas de requisito quando acessada travada; botão do Cassino bloqueado no Clube Elétrico mostra apenas **`🔒 Cassino`** e `"O Cassino está em reforma. Volte depois!"`.

## R112 — 1.0.157-snapshot.112
- **Vending Machine (116 cartas) e Máquina Booster Can (`S62`):** nova aba na Gazeta (exibida somente após derrotar **3 Mestres da Ilha**, com aviso único do Sam), máquina 3D de latinhas em cor única por **200 Créditos**, entregando **5 cartas aleatórias sem distinção de raridade**, com som de abertura de latinha, revelação em tela cheia centralizada e resumo em `3 + 2`. Coleção disponível na Coleção (com símbolo Pokébola e logo próprios) e no Editor de Decks, fora dos baralhos aleatórios de NPC.
- **Cassino da Ilha, Cassino de Celadon e Tickets:** nova moeda **Tickets** exibida à esquerda dos Créditos (câmbio 10 Créditos = 1 Ticket), caça-níquel com rolos só de ícones e botões `PARAR 1/2/3`, aba `Cassino` no Clube Elétrico em reforma até a reabertura (anunciada pelo Sam), marcador do Cassino de Celadon em Kanto e **Loja Intro Pack** para adquirir as 16 cartas `intro`.
- **Autobuilder e Encontros (`!`):** checagem universal no Autobuilder para impedir mistura de pré-evoluções incompatíveis ou excesso em linhas evolutivas compartilhadas; placa dos encontros aleatórios não exibe mais dificuldade nem turno do oponente.

## R111 — 1.0.156-snapshot.111
- **Vitória dos Mestres:** a entrega da moeda do Mestre tem prioridade absoluta sobre avisos do Sam, selos e tutorial da Feira, com intervalo mínimo de 2 segundos entre mensagens e sem sobreposição.
- **Encontros aleatórios (`!`):** tocar no marcador abre o banner inferior; tocar em **Duelar** entra direto na partida com **4 prêmios** (sem passar pelo Jogo Rápido), e a dificuldade escala pelos Mestres vencidos (`0–3` Fácil, `4–6` Médio, `7–8` Difícil).
- **Decks por campanha e Autobuilder:** encontros seguem a etapa da campanha (Ilha: Base/Jungle/Fossil; pós-Rocket: +Team Rocket; Kanto: foco em Gym Heroes/Challenge; Johto: Neo 1–4), com geração em pirâmide, filtro de Treinadores sem alvo e Autobuilder do jogador respeitando o estoque real e decks parciais.

## R110 — 1.0.155-snapshot.110
- **Mesa virada:** o número do dano que o adversário sofre agora aparece de pé para você também no celular.
- **Defender e PlusPower** saem do Pokémon e voam até o descarte quando o efeito acaba (antes sumiam e apareciam no descarte).
- **Mestres bloqueados:** ao tocar, volta a aparecer a fala do Sam ou do Mestre; na lista continua só "Bloqueado".

## R109 — 1.0.154-snapshot.109
- Mestre de clube ainda não liberado aparece só como **Bloqueado** na lista.

## R108 — 1.0.153-snapshot.108
- A opção **Cartas do adversário** (De frente para mim / Viradas, como numa mesa) agora fica em **Aparência padrão › Mesa**, no menu do seu avatar.
- O menu do avatar voltou a ser como na R105 (sem os atalhos de Ajustes, Ajuda e Saves da R106).

## R107 — 1.0.152-snapshot.107
- **Mesa virada de verdade** (Cartas do adversário › "Viradas, como numa mesa"; na R108 a opção foi para a Aparência padrão): tudo do adversário fica virado para ele — cartas, Energias, PS, deck, descarte, prêmios, a mão e o tapete dele. Só o número do dano que ele sofre fica virado para você. O lado dele espelha como numa mesa real (prêmios à direita, deck e descarte à esquerda) e as cartas dele já se movem viradas. Em "De frente para mim", nada muda.
- **Seletor de velocidade da partida:** mudar a velocidade na pausa não tinha efeito para quem já tinha escolhido uma velocidade nos Ajustes. Agora funciona na hora.

## R106 — 1.0.151-snapshot.106
- Atalhos de **Ajustes**, **Ajuda** e **Saves e backups** no menu do avatar (retirados na R108).

## R105 — 1.0.150-snapshot.105
Junta a R104 com:
- **Clubes abertos para os membros:** dá para entrar em qualquer clube e enfrentar os cinco membros desde o início. A regra de liberação vale só para o **Mestre**, que aparece com cadeado. No mapa da ilha, nenhum clube aparece mais fechado.
- **Avatares:** num jogo novo, a escolha de avatar mostra só os avatares iniciais; os duelistas só aparecem depois de vencidos. Mark e Mint escolhidos ficam redondos.

## R104 — 1.0.149-snapshot.104
Junta a R103 com tudo o que foi feito depois dela.
- **Selos de Kanto**, com tapetes de duelo por local e um prêmio a cada cinco selos.
- **Ronald** com dois decks (um deles com as Eeveelutions do Game Boy), preparação própria e revanche depois dos quatro Grandes Mestres.
- **15 cartas GB Promos**, com efeitos próprios. A seção da coleção fica escondida até você ganhar a primeira; o nome e o logo aparecem na terceira troca. O Colecionador e o Sam passam a oferecer essas cartas.
- Arte nova do **ticket da Ilha para Kanto**, no diálogo do Mason e no porto.
- **Eventos:** o mosaico não tem mais blocos sobrepostos, e o Sam aparece maior.
- Nova arte da carta Articuno do Game Boy.

## R103 — 1.0.148-snapshot.103
- **Cartas do adversário viradas**, como numa mesa de verdade. É uma opção em Ajustes › Mesa.
- **Tocar e segurar** uma carta para ver os detalhes funciona também no turno do adversário.
- **PlusPower e Defender** ficam ligados ao Pokémon até o efeito acabar, e só então vão para o descarte. O Item Finder não pega mais essas cartas enquanto estão em jogo.
- O **PS** do Pokémon voltou a aparecer cheio e diminuindo com o dano.
- Tela de limite de mão só com as cartas, sem nomes encavalados e sem o botão de informações por cima.
- Retratos maiores nos diálogos. O Imakuni não aparece mais cortado.
- **Mapa da ilha:** o ícone da Feira só aparece aos sábados depois de ser liberada, e um clube travado fecha o banner que estava aberto. Nas batalhas aleatórias, o nível sai do cartão e o avatar fica maior.
- O Sam explica no tutorial o que são as **"!"** do mapa.
- **Tipo do deck** com os símbolos das Energias que o deck realmente usa.
- Círculo do Ativo maior, texto centralizado no aviso de turno e avatar do jogador maior.
- Em jogo novo, a aba do Grande Salão só aparece depois de liberada.

## R102 — 1.0.147-snapshot.102
- **Correção:** o PlusPower ficava preso ao novo Ativo do adversário quando o Pokémon recuava. Agora ele é descartado quando o Pokémon sai do Ativo.
- A **cura de condição ao evoluir** aparece depois da animação de evolução, sem travar.
- Energias ligadas aos Pokémon do Banco centralizadas.

## R101 — 1.0.146-snapshot.101
- O adversário **anuncia o ataque antes** de atacar, como se desse o comando ao Pokémon.
- Círculo redondo sob os Ativos.
- **Ferramentas e cartas ligadas** (PlusPower, Defender, Máquinas Técnicas) ganharam espaços próprios na mesa.
- Tocar numa carta da mão não abre mais o submenu.
- Botão de **Informações** de volta na mesa, explicando os símbolos (como os do Mr. Mime).
- Ícone do porto alinhado com os pontos da ilha.

## R100 — 1.0.145-snapshot.100
- **Mesa de duelo nova**, fiel à prévia aprovada: zonas, prêmios encavalados, emblemas, pilhas e contador de dano.
- Cartas da mão 10% menores e sem o atalho "Atacar". Os ataques continuam ao tocar no Ativo.
- Tapete padrão para o jogador e para adversários sem tema próprio.
- Avatares dos chefes restaurados. As artes HD ficam só nos banners.
- Recortes dos selos corrigidos.
- A tela de carregamento mostra a versão certa.

## R99 — 1.0.144-snapshot.99
- Primeira versão da mesa nova: banco do adversário no topo, Ativo centralizado, prêmios à esquerda, deck e descarte à direita e Estádio na linha do meio.
- Placa do adversário com foto e nome. Avisos "Seu turno" e "Vez do adversário".
- Mão maior, em leque, e bordas menos arredondadas.

## R98 — 1.0.143-snapshot.98
- **Eventos em mosaico:** Gazeta Open, Desafio do Sam, Relâmpago, Pacote surpresa, Tipo da semana e Caça à carta, com resumo do dia. Para jogador novo, só o Sam fica aceso.
- Primeira versão da mesa nova.
- Máquinas do Gachamon para as coleções futuras (Neo e VS), ainda travadas.

## R94 a R97 — artes, jornada e feiras
- **16 artes HD** de personagens. O Mason dá a aula inicial e entrega o ticket; o Sam cuida das demais falas.
- **Jornada até Kanto:** depois da Invasão Rocket, porto, duelo obrigatório com o **Ronald**, campeão da ilha, e embarque. Na derrota, o ticket fica guardado.
- **Feiras regionais:** a da Ilha e a de Celadon, com cotas próprias.
- Fundos transparentes em todos os retratos (sem quadrados pretos), identidades corrigidas (Gene, Isaac, Mitch e Steve) e Mason sem fundo preto nas falas.

## R93
- Correção: a cápsula do Gachamon atravessava a base da máquina.

## R92
- Abas da Gazeta (Pacotes, Avulsas, Gacha, Temáticos e Eventos) no mesmo estilo das telas novas.

## R91 — progressão dos clubes e selos
- Clubes liberados aos poucos: o Cassino depois do Rick, a Mansão depois de três Mestres, o Fogo com 300 cartas na coleção e a Planta depois de três trocas.
- História do acidente do Isaac no laboratório.
- **40 selos**, cinco por Mestre de clube, com objetivos próprios.
- Promoção a Gerente e ícone da Feira aos sábados.

## R89 e R90
- O zoom da ilha não afasta mais além do enquadramento normal. Mapa com cantos retos e ícone novo de reenquadrar.
- O aviso de prêmios pendentes passou para o avatar e para Recibos e notificações.

## R88 — economia
- **Prêmios maiores:**
  - Rocket: recruta 100, executivo 200 e chefe 400;
  - treinadores de rota de Kanto: 120;
  - pupilos de ginásio: 150;
  - líderes: 500 créditos e 3 boosters;
  - Grandes Mestres: 750 créditos e um booster de cada coleção.
- O Sam pede confirmação antes de compras de temáticos e cartas avulsas, e avisa quando a carta é repetida.

## R87
- O passeio do Sam no tutorial mostra as telas atuais (Jogo Rápido e Ilha dos Clubes) e não revela mais a Invasão Rocket antes da hora.
- Corrigido um erro de inicialização.

## R84 a R86 — painéis temáticos
- Painéis próprios para os **oito clubes**, os **oito líderes de Kanto** (com os 24 treinadores de rota), os **seis Rockets** e os **quatro Grandes Mestres**.
- Avatares próprios dos Rockets.

## R83
- **Ilha dos Clubes em 4K**, carregando os detalhes conforme o zoom.

## R79 a R82 — IA do Game Boy
- Os **12 mestres** (oito de clubes e quatro do Grande Salão) jogam com as prioridades dos decks do Pokémon TCG de Game Boy.
- Os chefes e depois todos os NPCs começam com uma mão inicial favorecida, como no Game Boy: pelo menos dois Pokémon Básicos e duas Energias.
- IA revisada: planos por deck, avaliação da mão e personalidades.

## R78 — o Grande Salão
- Arena dos **quatro Grandes Mestres**, com banners próprios.
- Avatares de combate dos Grandes Mestres preservados.

## R77 — base Rocket
- A Invasão Rocket virou uma **base secreta** com seis desafios: três recrutas, dois executivos (Devastation e Trouble) e o chefe.
- **Quatro avatares iniciais** para o jogador.
- Setas de navegação sem moldura.

## R75 e R76
- Pontos maiores em Kanto, com destaque nos líderes e os banners antigos ao selecionar.
- Ilha com mais detalhes e zoom liberado.
- Retratos corrigidos: nomes e rostos dos treinadores agora combinam.

## R74 — mapa de Kanto
- **Mapa ilustrado de Kanto** com 32 pontos: 24 treinadores de rota e oito ginásios. Tocar num ponto aproxima e mostra o cartão do adversário.

## R73
- Boosters de coleção ainda travada não chegam mais antes da hora. Os Team Rocket ganhos na Invasão ficam **apreendidos** e o Sam entrega todos ao final.
- **Encontros opcionais** na ilha: treinadores com "!" aparecem pelas ruas.

## R72 — Ilha dos Clubes
- **Ilha ilustrada e explorável** para a Batalha dos Clubes, com bairros, porto, Gazeta e a praça da Feira do Troca.
- Dá para arrastar, aproximar com dois dedos ou ver a ilha inteira.

## R70 e R71 — Desafio dos 8 ilustrado
- Oito cenários: Floresta de Viridian, Mt. Moon, Ponte Pepita, Túnel de Pedra, Ciclovia, Dojo de Karatê em Saffron, Ilhas Seafoam e Rota 22.
- Trilha no mapa, marcadores por região e cartões dos ginásios com o retrato do líder.

## R69 — Grande Salão
- O Grande Salão abre depois dos 8 líderes, com Courtney, Steve, Jack e Rod. Eles usam os decks e as cartas lendárias do Game Boy, no nível mais alto.
- Capas de booster sorteadas com chance igual entre as artes.

## R68
- Abas da campanha fixas no topo.
- Detalhe da carta abre direto em 3D.
- Lápis para editar o deck na seleção.
- Janine antes do Koga.

## R67
- **Batalha dos Clubes** com seis duelos por clube: cinco membros e depois o Mestre.
- **Desafio dos 8** como caminho, com três treinadores de rota antes de cada ginásio.
- **40 decks novos** de NPC.
- Avatar do jogador: foto própria ou o avatar de qualquer NPC derrotado.
- Efeitos novos na partida (Treinador, Energia, entrada e evolução) e descarte em grade.
- Troca Relâmpago a cada 30 minutos.
