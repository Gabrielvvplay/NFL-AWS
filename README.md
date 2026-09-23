A ideia principal: "O Relógio do Pocket"
Um painel de narração construído em torno dos três momentos reais de uma jogada na transmissão, não em torno de uma métrica.

Momento 1 — Pré-snap (a janela de ~8 a 15 segundos) O narrador vê: tempo de pocket esperado para esta jogada e o duelo da jogada.

"Atenção: Wirfs contra Garrett. Bolso esperado: 2,3 segundos. Brady precisa de 2,6."

Calculado com formação, personnelO/personnelD, defendersInBox, cobertura PFF e o histórico direto daquele par bloqueador × rusher.

Momento 2 — Durante a jogada (ao vivo) Um bolso que encolhe na tela: o polígono formado pelos bloqueadores ao redor do QB, quadro a quadro, com um cronômetro de tempo-até-pressão. É visual, é intuitivo, e qualquer leigo entende uma forma diminuindo.

"o bolso perdeu 60% da área em 1,8 segundo"

Momento 3 — Replay (a janela de ~15 segundos depois) Atribuição de culpa e crédito, com frase pronta.

"Foi um twist entre o defensive end e o tackle. O guard não passou o homem. 2,1 segundos e Brady no chão."

Esse terceiro momento é o mais valioso: detecção de stunt/twist. O narrador nunca explica isso porque é invisível na tela — dois rushers cruzando caminho. Dá para detectar cruzando as trajetórias do tracking com pff_blockType = SW (switch block).

Por que isso é diferente
A maioria vai entregar uma métrica + um dashboard. Vocês entregam um produto de narração: texto pronto, no momento certo, com o timing de quem está com o microfone na mão.
O ranking do que mostrar é por surpresa narrativa — quanto o real fugiu do esperado. Jogada previsível não vira frase; jogada surpreendente sobe no painel. Isso resolve o problema de sobrecarga de informação, que é o defeito real de painéis de dados em transmissão.
Narra os 5 jogadores que a transmissão ignora.
Em português, pensado para transmissão brasileira de NFL. Nenhum trabalho do Big Data Bowl foi feito nesse recorte.
Validação (o que dá credibilidade técnica)
Vocês têm rótulos reais para testar: pff_sack, pff_hit, pff_hurry, pff_sackAllowed. Então o modelo de "tempo até pressão" não é achismo — dá para medir acerto contra o que o PFF marcou. Isso separa o trabalho dos que só fazem visualização.


NOMES DE INTEGRANTES:
Gabriel Venâncio - 2025085865884
Samuel Dias - 202303841825
Brenno Matzke - 202502327641
Carlos Eduardo - 202503533644
