
P6 - Mapa da Morte
===========================
### Por Nikolas Thorun

#### Resumo:

Esta visualização apresenta as taxas de homicídio a cada 100 mil habitantes no Brasil, registradas entre 1996 e 2015.
Os dados foram retirados do 'Atlas da Violência' no site do IPEA, o Instituto de Pesquisa Econômica Aplicada (http://www.ipea.gov.br/atlasviolencia/series).
A animação começa mostrando um mapa coroplético do Brasil, no qual a intensidade da cor indica o valor da taxa de homicídio, iterando entre os anos a cada meio segundo.
Após o término da animação, um menu aparece com as opções de ver a animação para diferentes gêneros ou detalhar algum ano específico.
Se uma nova animação for selecionada, um botão de 'pular animação' é mostrado.

#### Design:

Para representar o 'mapa da morte' foi escolhido um mapa coroplético, no qual a escala de cores varia de branco a vermelho e depois a preto.
A ideia é que estados sem homicidios ficassem brancos, estados com mais de 100 homicídios por 100 mil habitantes focassem pretos e o restante dos estados variassem entre rosa claro e vermelho escuro.
Após os feedbacks, o título foi alterado de 'Mapa da Violência' para 'Mapa da Morte (Homicídios)', para não passar a ideia de que o mapa representava outros tipos de violência.

#### Feedback:

Várias pessoas assistiram e interagiram com a visualização, a maioria delas disse que não tinha pontos de melhorias a indicar.

Quatro feedbacks foram dados:

1 - Meu irmão Peter, o primeiro a quem mostrei a visualização, reclamou que a animação estava muito lenta e que ninguém tem este tempo para assistí-la hoje em dia.
O feedback foi aceito e implementado. Os próximos feedbacks foram dados após essa modificação.

2 - Minha namorada Natália reclamou que a animação estava muito rápida e que o título confunde e passa uma ideia errada.
O feedback do título foi aceito e implementado. O feedback do tempo de animação não foi aceito, pois as outras pessoas não concordaram.

3 - Meu chefe Thiago, que é um baita analista de dados, disse que a visualização já mostra dos os dados que ele quer ver, mas seria interessante abrir um gráfico de linha mostrando a evolução da taxa no tempo quando clicássemos em algum estado.
O feedback foi aceito, mas não foi implementado por entender que daria muito trabalho para mostrar dados que o mapa já mostra, porém de outra forma. Mas a ideia é boa será implementada em um segundo momento.

4 - Meu amigo André falou que seria interessante ter um botão de 'pular animação' para que não fossemos obrigados a assistir as animações todas as vezes que clicássemos nos botões de gênero.
O feedback foi aceito e implementado.

#### Recursos:

Para ajudar na construção da visualização, foram pesquisadas as seguintes fontes:

Tooltip:
http://bl.ocks.org/Caged/6476579

Exemplo de mapa coroplético:
https://bl.ocks.org/mbostock/4060606

Legenda:
https://www.visualcinnamon.com/2016/05/smooth-color-legend-d3-svg-gradient.html
http://bl.ocks.org/darrenjaworski/5397362
