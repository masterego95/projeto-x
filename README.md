# projeto-x
museu.
#include <stdio.h>
#include <locale.h>

struct vendas{
int cod;
char nome[100];
int idade;
float preco;
char tipopgto[50];
};

int qtde=0;
struct vendas vd[1000];
int ttinteira=0, ttmeia=0, ttisento=0;

 main() {

    setlocale(LC_ALL, "Portuguese");
    int contagem = 0;
    char entrada;
    char codigo;

    do {
            system("cls");

    printf("-------------------------------------------------------------------------------------\n");
    printf("seja bem vindo ao museu da ong thunder web\n");
    printf("----------------------------------------------------------------\n");
    printf("nosso museu terra dino onde voces adiquire o maior conhecimento\nsobre os queridos animais extintos mais perigosos ja exitentes\n");
    printf("----------------------------------------------------------------\n");
    printf("voce seria um visitante ou um administrador? \n");
    printf("-------------------------------------------------------------------------------------\n");
    scanf(" %c", &codigo);

    if(codigo == 'v' || codigo =='V'){
        system("cls");

        printf("-------------------------------------------------------------------------------------\n");
        printf("Voce esta no hall de entrada escolha para onde deseja ir\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("Pressione 'e' para se locomover para sala principal\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("'q' para sair do museu ou\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("'x' para sair e exibir a contagem de vezes que voce voltou para o salao principal: ");
        printf("\n-------------------------------------------------------------------------------------\n");
        scanf(" %c", &entrada);

        if (entrada == 'e' || entrada == 'E') {
            contagem++;

            system("cls");
            printf("Voce indicou salao principal. Total de vezes que voce ingressou ao salao principal: %d\n\n", contagem);

        int salao,especie;

        printf("-------------------------------------------------------------------------------------\n");
        printf("seja bem vindo ao nosso salao principal onde voce tem um resumo das obras que serao vistas em nosso museu\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("somos dividos por 4 areas cada uma especializada em algumas classes de dinossauros \n-------------------------------------------------------------------------------------\n1- Carnivoros\n-------------------------\n2- Herbivoros\n-------------------------\n3- Aereos\n-------------------------\n4- Aquaticos\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("Teria interesse em visitar qual salao pimeiro? (digite o numero de sua escolha)");
        printf("\n-------------------------------------------------------------------------------------\n");
        scanf("%d", &salao);
            switch (salao) {
        case 1:
            system("cls");

            printf("-------------------------------------------------------------------------------------\n");
            printf ("Bem vindo a ala dos carnivoros\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("1- Tiranossauro rex.\n-------------------------\n2- Espinossauro\n-------------------------\n3- Oxalaia\n-------------------------\n4- Giganotossauro\n-------------------------\n5- Carcharodontosaurus\n-------------------------\n6- Tiranotitan\n-------------------------\n7- sair da Ala dos Carnivoros\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("esses sao nossos queridos carnivoros disponiveis , teria interesse em saber mais alguma inforaçao sobre nossos queridos fosseis ? (digite o numero de sua escolha)\n");
            printf("-------------------------------------------------------------------------------------\n");
            scanf("%d", &especie);

                    switch (especie) {
                            case 1:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("1- Tiranossauro rex.\n-------------------------------------------------------------------------------------\nO tiranossauro rex é um animal que viveu entre 90 e 66 milhões de anos atrás.\nOs tiranossauros possuíam cerca de 12 metros de comprimento e 3,65 metros de altura e podiam pesar oito toneladas.\nPossuía um olfato bastante desenvolvido.\nProvavelmente, caçava suas presas mas também se alimentava de carniça.\nConhecido como “rei lagarto tirano”, esse gigante possuía cerca de 60 dentes enormes, atingindo até mais de 20 centímetros.\nSe seu dente já era grande, imagine seu comprimento.\nEsse animal chegava a 12 metros de comprimento.\nSó a cabeça dele atingia mais de 1,5 metro,e sua altura poderia atingir até 3,65 metros.\nEstudos sugerem que as fêmeas eram relativamente maiores que os machos.\nEsse animal pesava entre cinco e oito toneladas.\nMuito se discute também sobre a capacidade de correr desses animais.\nAlguns pesquisadores sugerem que eles atingiam até 50 km/h.\nAtualmente, considera-se que esses animais atingiam apenas 19 km/h.\nSegundo um estudo publicado em 2021 e intitulado “Natural Frequency Method: estimating the preferred walking speed of Tyrannosaurus rex based on tail natural frequency”,\no tiranossauro rex, provavelmente, tinha como velocidade preferida de sua caminhada algo em torno de 4,8 km/h, um valor bem semelhante ao de humanos.\nesses animais eram capazes de localizar a sua presa em longas distâncias.\nEm relação à visão, alguns pesquisadores acreditam que o tiranossauro apresentava uma visão tão eficiente quanto a das atuais aves de rapina.\nO T. rex já foi descrito há mais de um século, e ainda hoje existem diversas dúvidas sobre seu modo de vida. Apesar de seus dentes grandes e seu tamanho exagerado,\nde que seus pequenos braços poderiam dificultar que esse animal se levantasse após uma queda durante um ataque, por exemplo.\nAlém disso, o formato dos dentes e o sentido do olfato bem desenvolvido indicam que ele poderia sim ser um animal que se alimentava de carniça.\nEntretanto, o T. rex também possuía características que o tornavam um bom caçador. Sua mordida, por exemplo, é a mais forte que de qualquer outro animal no planeta.\nPesquisadores descobriram que cada dente do animal era capaz de exercer uma pressão de seis toneladas. Para se alimentar, o tiranossauro lançava a sua presa no ar\ne a engolia inteira. Vale salientar ainda que já foram encontrados fósseis de animais com marcas de mordida do T. rex,\no que indica que, se esse animal não caçava, pelo menos, ele tentava realizar essa tarefa. Diante disso, atualmente, considera-se que o tiranossauro agia como necrófago,\nou seja, se alimentava de animais mortos mas também caçava.\n");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 2:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("2- Espinossauro\n-------------------------------------------------------------------------------------\nEsse dinossauro viveu durante o período Cretáceo, entre 112 e 97 milhões de anos atrás, nos pântanos da África do Norte. Além do mais, ele pertenceu ao reino Animalia, \n ao filo Chordata e a classe Reptilia, Contudo,  mesmo tendo vivido há milhões de anos, o o espinossauro ainda é considerado o maior dinossauro carnívoro que já existiu. \nTanto é que ele consegue ser maior que o Tiranossauro Rex e o Giganotossauro. Basicamente, seu tamanho variava entre 12,6 metros a 18 metros. \n Aliás, ele era também considerado o mais comprido da espécie terópode de dinossauro. Além do seu tamanho, ele também era bem pesado. \nEstima-se que o espinossauro tinha cerca de 8 toneladas, embora, espécie variasse de 6,35 a 20,87 toneladas. Ou seja, ele era 450 kg mais pesado que o Giganotossauro, e 900 kg a mais que o Tiranossauro. \n Primeiramente, vale destacar que o nome espinossauro, significa “lagarto espinha”. \n Aliás, o nome é bem condizente com a aparência do animal , já que ele possuía um prolongamento de vértebras nas costas. \n Suas inúmeras espinhas, aliás, era compridas e já foram chamadas de “velas” (como as dos barcos) algumas vezes por pesquisadores. \n Além do mais, essas espinhas tinham cerca de 1,65 metros de comprimento, e eram conectadas por uma pele. Sobretudo, essas protuberâncias auxiliavam na captação de calor, \n quando eram expostas à luz do sol. Aliás, elas faziam com que eles conseguissem ser mais ágeis que grande parte dos dinossauros de grande porte. \n E para melhorar, essas velas serviam ainda como um adorno de beleza. Ou seja, serviam para atrair mais fêmeas. Ou então, para se mostrar, \n aparentar ser maiores e mais agressivos que outros dinossauros. \n Basicamente, o espinossauro, assim como os demais predadores terrestres, também contava com características tradicionais. Como por exemplo, pernas fortes, boca e dentes enormes. \n Porém, os seus dentes eram retos, serrilhados e não curvados. O que indica que, provavelmente, ele vivia de peixes e carcaças. \nJá, o seu crânio, era estreito e comprido, similar com o dos crocodilos. \n Além dessas características, como já mencionamos, ele era relativamente rápido para seu tamanho. Aliás, ele conseguia alcançar uma velocidade entre 19 km/h e 24 km/h. \n Como seus braços também eram comprimidos, a forma como ele caminhava, contudo, ainda não é um consenso. Basicamente, \n seria possível que ele caminhasse usando suas pernas musculosas, ou então, de quatro. Ainda sobre os ossos do espinossauro, vale destacar que, em 2011, na Austrália, \n foi descoberto uma vértebra do pescoço de um dinossauro com um focinho parecido com o de um crocodilo. Basicamente, para a Ciência, \nisso mostrou que o espinossauro vivia em uma região muito maior que a História acreditava até então. \n");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 3:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("3- Oxalaia\n-------------------------------------------------------------------------------------\nÉ um dinossauro terópode que viveu há 95 milhões de anos, no fim do Cretáceo, É o maior terópode conhecido que andou em território brasileiro, \n com 12 a 14 m de comprimento e 5 a 7 toneladas. \nO Oxalaia deveria ser o predador dominante no nordeste do Brasil em sua época. \n  Faz parte de um grupo de dinossauros que desperta grande interesse por suas características peculiares, os espinossaurídeos, \n entre os quais só perde em tamanho para o espinossauro. Espinossaurídeos tinham crânio longo e estreito, \n alimentavam-se de peixes e pequenos animais e muitos possuíam uma espécie de vela nas costas. Outros dois já haviam sido descobertos no Brasil: Angaturama e Irritator. \n A espécie foi identificada a partir de um conjunto de fósseis, com partes do maxilar e dentes, encontrado em 1999, \n na Ilha do Cajual, Maranhão. Sua nomeação e divulgação só ocorreu, entretanto, em 2011. O nome específico, Oxalaia quilombensis, \nlembra dos assentamentos quilombolas construídos na região na época da escravidão e de sua população ser constituída por descendentes de escravos. \n Esta foi a oitava espécie oficialmente nomeada de terópode brasileiro. \n");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 4:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("4- Giganotossauro\n-------------------------------------------------------------------------------------\nO Giganotossauro cujo nome significa “Lagarto Gigante do Sul” viveu há aproximadamente 67 milhões de anos atrás durante o período Cretáceo na Patagônia Argentina, \nmas provavelmente dava seus passeios em territórios brasileiros, ultrapassou o tamanho do maior Tiranossauro rex conhecido e dos Carcharodontossauros e Espinossauros, \n sendo sem dúvida um dos maiores carnívoros terrestres conhecidos e com esse tamanho todo poderiam caçar até enormes saurópodes que quase não tinham inimigos naturais, \n provavelmente os Giganotossauro (Giganotosaurus) eram territoriais, e como eram enormes deveriam precisar de enormes quantidades de comida, e seus territórios então seriam enormes. \nSuas mandíbulas eram também enormes e seu crânio um dos maiores, mais de 1,6 metros de comprimento, \nseus dentes podiam medir 15 centímetros de comprimento, sendo curvos e afiados o que é um indicio de que eles eram utilizados para morder algo vivo, \nque ao se debater e tentar escapar acabaria indo mais para dentro da boca do predador, mas certamente o Giganotossauro (Giganotosaurus) não negaria uma refeição já morta em putrefação, \n agindo também como carniceiro.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 5:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("5- Carcharodontosaurus\n-------------------------------------------------------------------------------------\nCarcharodontosaurus (em português Carcarodontossauro do latim 'lagarto com dente de tubarão') foi um gênero de dinossauro terópode que viveu durante o período Cretáceo no Nordeste da África. \nAtualmente só temos duas espécies conhecidas, a espécie-tipo C. saharicus e a espécie C. iguinensis. O seu nome foi inspirado no gênero científico Carcharodon, mesmo gênero que inclui o tubarão-branco. \nCarcharodontosaurus é um dos maiores dinossauros terópodes conhecidos, com C. saharicus atingindo 12–12,5 metros de comprimento e aproximadamente 6–6,2 toneladas de massa corporal. \nTinha um crânio grande e de construção leve com uma tribuna triangular. Suas mandíbulas eram revestidas com dentes afiados, \nrecurvados e serrilhados que guardam semelhanças impressionantes com os do grande tubarão branco, inspiração para o nome. Embora gigante, seu crânio ficou mais leve por fossas e fenestras muito expandidas, \nmas também o tornou mais frágil que o dos tiranossaurídeos. Os membros anteriores eram minúsculos, enquanto os membros posteriores eram robustos e musculosos. Como a maioria dos outros terópodes, tinha uma cauda alongada para se equilibrar. \nO Carcharodontosaurus viveu na África, em locais onde hoje estão a Argélia (local da descoberta dos primeiros fósseis, em 1927), o Egito e a Tunísia, por exemplo. Existem sinais da presença de carcarodontossaurideos também na América do Sul, \ncorroborando a teoria que os atuais continentes África e América do Sul tenham sido um único espaço em parte da era Mesozóica, o Gondwana, e que começaram sua separação há cerca de 135 milhões de anos. \nMuitos terópodes gigantescos são conhecidos no Norte da África durante este período, incluindo ambas as espécies de Carcharodontosaurus, bem como o espinossaurídeo Spinosaurus e o ceratossauro Deltadromeus. \n Isto sugere que houve divisão de nicho entre os diferentes grupos, com o Spinosaurus sendo piscívoro, enquanto o Carcharodontosaurus consumiria dinossauros saurópodes, agindo como o predador alfa em seu pale o ambiente. \n");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 6:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("6- Tiranotitan\n-------------------------------------------------------------------------------------\nTyrannotitan (titã tirânico) é um gênero de dinossauros terópode carnívoro que, apesar do nome similar, não eram relacionados aos tiranossaurídeos, sendo pertencente à família dos carcarodontossaurídeos. \nA única espécie descrita na literatura é o T. chubutensis, descoberto por paleontólogos da Argentina na região de Chubut em 2005. Trata-se de uma espécie de grandes proporções que viveu na América do Sul, no período Cretáceo. \n Seus dentes chegavam a cerca de 25 cm de comprimento. O Tyrannotitan era um dinossauro carnívoro predador de grandes proporções. Este dinossauro viveu há 100 milhões de anos e podia chegar a ter 12 metros de comprimento e 4 metros de altura. \n Este dinossauro enorme poderia pesar até 7 toneladas sendo parte da tribo Giganotosaurini, sendo portanto um parente muito próximo do Giganotosaurus. \n Acredita-se que eles tenham sido do Membro Cerro Castaño, da Formação Cerro Barcino (estágio Aptiano) entre 112,2 à 121 milhões de anos atrás. \nO comprimento desses animais foi estimado em até 11,4 até 12,2 metros. Em 2010, Gregory S. Paul deu estimativas mais altas de 13 metros. Seu peso foi estimado entre 4,9 e 7 toneladas. Outros autores deram uma massa corporal de 4,8 a 5,4 toneladas, \n com intervalos de 3,6 a 6,7 toneladas. \n");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 7:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Que pena tente conhecer melhor alguma especie da proxima vez\n\nClique qualque tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            default:
                                system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Numero invalido, estou te encaminhando para o salao principal, Ate logo.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                getch();
                                break;
                     }
        break;
        case 2:
            system("cls");
            printf("-------------------------------------------------------------------------------------\n");
            printf ("Bem vindo a ala dos herbivoros\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("1- Braquiossauro\n-------------------------\n2- Diplodoco \n-------------------------\n3- Estegossauro \n-------------------------\n4- sair da Ala dos herbivoros\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("esses sao nossos queridos herbivoros disponiveis , teria interesse em saber mais alguma inforaçao sobre nossos queridos fosseis ? (digite o numero de sua escolha)\n");
            printf("-------------------------------------------------------------------------------------\n");
            scanf("%d", &especie);

                    switch (especie) {
                            case 1:
                            system("cls");
                            printf("-------------------------------------------------------------------------------------\n");
                                printf("1- Braquiossauro\n-------------------------------------------------------------------------------------\nO Braquiossauro tinha duas características marcantes em seu corpo. A primeira delas eram as longas patas dianteiras, bem maiores do que as traseiras. \nOs paleontólogos acreditam que eles não conseguiam se elevar sobre os membros inferiores. Além disso, o seu pescoço era gigantesco, fazendo com que ele tivesse uma incrível semelhança com a girafa. \nO paleontólogo Heinrich Mallison argumentou em um artigo publicado na 'Biologia dos Dinossauros Saurópodes' que essa espécie tinha muito menos energia do que as outras por causa dessas características. \nOutra coisa muito interessante sobre os braquiossauros é a temperatura de seu corpo. Pesquisadores calcularam, em 2011, através da medição dos índices de isótopos, que esses bichos tinham cerca de 45º C em seus corpos. \nPor isso, foram classificados como um animal de sangue quente, bem como outros saurópodes. \nAcredita-se que a espécie tinha cerca de 25 metros de comprimento, embora ele pudesse ser ainda maior, já que os fósseis analisados vieram a partir de amostrar de animais que não estavam totalmente desenvolvidos. \n Os pesquisadores não conseguiram, então, chegar a uma altura exata de um braquiossauro adulto. \nMuitas pesquisas foram feitas e, de acordo com um estudo publicado na revista PLOS Biology, em 2014, o animal dessa espécie poderia pesar entre 56 a 62 toneladas aproximadamente, \nlevando-se em consideração a altura e todas as características obtidas até então sobre os braquiossauros e todo o seu estilo de vida. \n");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 2:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("2- Diplodoco \n-------------------------------------------------------------------------------------\nEra um gigante rabo-de-chicote de pescoço comprido, medindo cerca de 90 pés (27 m) de comprimento com um 26 pés (8 m) de comprimento do pescoço e um de 45 pés (14 m) de comprimento da cauda, \nmas sua cabeça estava a menos de 2 pés grandes.Ele estava entre os maiores animais terrestres de todos os tempos.Suas narinas estavam no topo de sua cabeça e tinha dentes peg-like, \nmas apenas na parte da frente dos maxilares.Suas patas dianteiras eram mais curtos do que suas pernas traseiras, e todos tinham elefante-like, pés de cinco dedos.\nUm dedo do pé em cada pé tinha uma garra polegar, provavelmente para proteção. A impressão de pele fossilizada Diplodoco (Diplodocus) revela que ele tinha uma fileira de espinhos executando as suas costas.\nDiplodoco (Diplodocus) era um herbívoro (ele comia somente plantas). Ele deve ter comido uma quantidade enorme de material vegetal a cada dia para se sustentar.\nEle engoliu as folhas inteiras, sem mastigar-los, e pode ter ingerido gastroliths (pedras que permaneceram em seu estômago) para ajudar a digerir este material planta resistente.\nEle tinha dentes sem corte, úteis para descascar folhagem.Sua principal comida era provavelmente coníferas, que eram a planta dominante quando os grandes saurópodes viveram. Alimentos fontes secundárias podem ter incluído gingkos, samambaias de sementes, cicas, bennettitaleans,\nsamambaias, musgos clube, e cavalinhas.Diplodoco (Diplodocus) viveu no final do período jurássico, 155-145 milhões de anos atrás.\nO primeiro fóssil Diplodoco (Diplodocus) foi encontrado por Earl Douglass e Samuel W. Williston em 1877 e\nfoi nomeado pelo paleontólogo Othniel C. Marsh em 1878.Muitos fósseis foram encontrados Diplodoco (Diplodocus) nas Montanhas Rochosas do oeste dos EUA (em Colorado, Montana, Utah, e Wyoming).\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 3:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("3- Estegossauro\n-------------------------------------------------------------------------------------\nO Estegossauro era um dinossauro de porte médio a grande, que viveu no final do período Jurássico (de 155 a 145 milhões de anos atrás).Os Estegossauros eram herbívoros, ou seja, alimentavam-se de vegetais.\n Os principais vegetais que faziam parte da alimentação deste dinossauro eram: samambaias, musgos, cicadáceas e cavalinhas. Comiam também frutas, sendo a principal o abacaxi.\nPossuíam dupla fileira de placas ósseas nas costas, que atingiam cerca de 80 centímetros de altura. Estas placas tinham como objetivo principal\n fazer a regulação da temperatura corporal do estegossauro. Quando este dinossauro precisava aquecer o corpo, bastava ficar ao sol que estas placas absorviam o calor. Já na sombra, tinha o efeito contrário.Viveram na região centro-oeste da América do Norte.\n Eram quadrúpedes, ou seja, se apoiavam em quatro patas, possuíam cabeça pequena e alongada, possuíam dentes pequenos no formato triangular. \nAs principais espécies são: Stegosaurus armatus, Stenops Stegosaurus e Longispinus Stegosaurus.Seu comprimento era a cerca de 9 metros. \nSua altura era a cerca de 4 metros (animal adulto). Peso de 2 a 4 toneladas (animal adulto). Cor verde ou marrom, \nsendo que as placas nas costas podiam ser da mesma cor do animal ou de cor forte (vermelha, amarela ou laranja). Sua Velocidade era de 5 a 15 km/h");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 4:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Que pena tente conhecer melhor alguma especie da proxima vez\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Clique qualque tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            default:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Numero invalido, estou te encaminhando para o salao principal, Ate logo.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;
                    }
            break;

            case 3:
            system("cls");

            printf("-------------------------------------------------------------------------------------\n");
            printf ("Bem vindo a ala dos dinossauros aereos\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("1- Pteranodon\n-------------------------\n2- Pterodáctilo \n-------------------------\n3- Quetzalcoatlus \n-------------------------\n4- Aerotitan \n-------------------------\n5- Haopterus\n-------------------------\n6- sair da Ala dos aerios\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("esses sao nossos queridos aereos disponiveis , teria interesse em saber mais alguma inforaçao sobre nossos queridos fosseis ? (digite o numero de sua escolha)");
            printf("\n-------------------------------------------------------------------------------------\n");
            scanf("%d", &especie);

                    switch (especie) {
                            case 1:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("1- Pteranodon\n-------------------------------------------------------------------------------------\nfoi um réptil pré-histórico voador da ordem Pterosauria, que viveu no fim do período Cretáceo, na região da atual América do Norte. Foi um dos maiores pterossauros que existiram, com cerca de 7,5 m de envergadura. A descoberta de peixes fossilizados no estômago de um pterodonte mostra que eram piscívoros e provavelmente habitantes das zonas oceânicas. O tamanho das suas asas sugere que o pterodonte, em vez de bater as asas frequentemente, voasse por deslizamento aproveitando as plumas térmicas, como os albatrozes atuais. Uma das características mais marcantes dos pterodontes é a crista que tinham na cabeça. As diferentes espécies do gênero Pteranodon distinguem-se pela forma e tamanho da mesma. As funções desta estrutura são desconhecidas, mas foram sugeridas duas hipóteses: para uso tipo ultimoro ou em rituais de acasalamento. Mais espécimes fósseis de Pteranodon foram encontrados do que qualquer outro pterossauro, com cerca de 1.200 espécimes conhecidos pela ciência, muitos deles bem preservados com crânios quase completos e esqueletos articulados. Era uma parte importante da comunidade animal no Mar Interior Ocidental.\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 2:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("2- Pterodáctilo\n-------------------------------------------------------------------------------------\né um gênero extinto de pterossauro pterodactilóide, cujos membros são conhecidos como pterodáctilos. Eles viveram durante o período Jurássico Superior, cerca de 150,8 a 148,5 milhões de anos atrás. O Pterodáctilo era um pequeno pterossauro comparado a outros gêneros famosos, como Pteranodon e Quetzalcoatlus, e também viveu antes desses dois gêneros, durante o período Jurássico Superior. Como todos os pterossauros, o Pterodáctilo possuía asas formadas por pele e uma membrana muscular se estendendo do quarto dedo até os membros posteriores, sustentada internamente por fibras de colágeno e externamente por cristas queratinosas. Acredita-se que o Pterodáctilo era um carnívoro que provavelmente se alimentava de peixes, bem como de outros pequenos animais. Restos fósseis de Pterodáctilo foram encontrados principalmente no depósito de Solnhofen da Baviera, Alemanha. Muitos estudosconcluem que o Pterodáctilo era um carnívoro que provavelmente se alimentava de peixes, bem como de outros pequenos animais. ");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 3:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("3- Quetzalcoatlus\n-------------------------------------------------------------------------------------\nfoi um réptil pré-histórico voador da ordem Pterosauria, que viveu durante o Cretáceo Superior na América do Norte. Com uma envergadura de cerca de 12 metros, é considerado um dos maiores animais voadores conhecidos. O quetzalcoatlus pertencia à família Azhdarchidae, de pterossauros sem dentes, e provavelmente era um predador. Os primeiros fósseis de quetzalcoatlus foram descobertos no Texas por Douglas A. Lawson, em formações cretácicas. Até então, o recorde de envergadura para um animal alado pertencia ao Pteranodonte, outro pterossauro, com cerca de 10 metros. O quetzalcoatlus veio aumentar este valo. Outros fósseis encontrados, do mesmo gênero, sugerem envergaduras ainda maiores, na ordem dos 18 metros, mas estes não se encontram bem preservados e a comunidade científica permanece cética quanto a estes valores.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 4:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("4- Aerotitan\n-------------------------------------------------------------------------------------\né um gênero de pterossauro azdárquido conhecido do período Cretáceo Superior (estágio Maastrichtiano) do que é agora a Formação Allen da Bacia Neuquén, no norte da Patagônia, Argentina. O Aerotitan sudamericanus é a única espécie conhecida do gênero. O holótipo, MPCN-PV 0054, foi recuperado perto do local de Bajo de Arriagada, na Patagônia, de uma camada da Formação Allen superior. Consiste, de acordo com a descrição original, em um rostro parcial com um comprimento preservado de 264 milímetros (10,4 pol.). Este focinho é alongado e transversalmente comprimido e as mandíbulas são desprovidas de dentes. A envergadura foi estimada em pelo menos 5 metros (16 pés).");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 5:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("5- Haopterus\n-------------------------------------------------------------------------------------\né um gênero de pterossauro azdárquido que viveu durante o período Cretáceo Superior, cerca de 124,6 milhões de anos atrás. O holótipo, MPCN-PV 0054, foi recuperado perto do local de Bajo de Arriagada, na Patagônia, Argentina. O Haopterus sudamericanus é a única espécie conhecida do gênero. O focinho deste pterossauro é alongado e transversalmente comprimido e as mandíbulas são desprovidas de dentes. A envergadura foi estimada em pelo menos 5 metros (16 pés).");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 6:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Que pena tente conhecer melhor alguma especie da proxima vez\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Clique qualque tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            default:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Numero invalido, estou te encaminhando para o salao principal, Ate logo.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;
                    }
            break;

            case 4:
            system("cls");
            printf("-------------------------------------------------------------------------------------\n");
            printf ("Bem vindo a ala dos Aquaticos\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("1- Mosassauro\n-------------------------\n2- Ictiossauro  \n-------------------------\n3- Plesiossauro  \n-------------------------\n4- Platecarpus\n-------------------------\n5- Halisaurus\n-------------------------\n6- sair da Ala dos Aquaticos\n");
            printf("-------------------------------------------------------------------------------------\n");
            printf("esses sao nossos queridos maritimos disponiveis , teria interesse em saber mais alguma inforaçao sobre nossos queridos fosseis ? (digite o numero de sua escolha)\n");
            printf("-------------------------------------------------------------------------------------\n");
            scanf("%d", &especie);

                    switch (especie) {
                            case 1:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("1- O Mosassauro\n-------------------------------------------------------------------------------------\né um gênero de lagartos marinhos mosassaurideos que viveram em torno de 90 milhões de anos atrás no oceano Atlântico, e tem um certo parentesco com os atuais varanídeos. O nome é devido a seus primeiros fósseis, encontrados em 1770 por George Cuvier, terem sido encontrados no vale do rio Mosa, na Holanda. Os mosassauros tinham um corpo fusiforme, dotado de dois pares de nadadeiras laterais, perfeitamente adaptado a vida em mares pouco profundos. Eram carnívoros, sendo que o menor exemplar conhecido media cerca de 3,5 metros de comprimento e o maior 17 metros, Mosasaurus hoffmannii. Chegaram a pesar até 6 toneladas. O crânio do mosassauro era equipado com mandíbulas robustas capazes de balançar para frente e para trás e músculos fortes capazes de mordidas poderosas usando dezenas de dentes grandes adaptados para cortar presas. Seus quatro membros eram moldados em pás robustas para guiar o animal debaixo d’água. Sua cauda era longa e terminava em uma curva para baixo e uma pata em forma de remo. O mosassauro era um predador com excelente visão para compensar seu mau olfato e uma alta taxa metabólica sugerindo que era endotérmico ('sangue quente'), uma adaptação encontrada apenas em mosassauros entre os escamados. Ainda existem muitas controvérsias sobre as afinidades exatas do Mosassauro como escamado e se seus parentes vivos mais próximos são lagartos ou cobras.\n");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 2:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("2- Os ictiossauros\n-------------------------------------------------------------------------------------\neram uma ordem de répteis marinhos extintos que teriam surgido no início do Triássico Inferior (paleotriássico) e se extinguiram um pouco antes da extinção dos dinossauros, no início do Cretácico superior (neocretássico). Eles eram animais carnívoros e alimentavam-se preferencialmente de cefalópodes mesozóicos como as belemnites e amonites. O primeiro esqueleto completo de um ictiossauro foi descoberto em 1811 no sul de Inglaterra por Mary Anning. Os ictiossauros mediam entre 2 a 3 metros de comprimento (ainda assim podendo atingir 15 m), tinham um focinho longo e afilado e barbatanas caudais e dorsais tal como os peixes e golfinhos. Apesar disto, estes animais eram répteis, e as semelhanças resultam, de acordo com a teoria da evolução, de evolução convergente de estruturas análogas. O estudo da anatomia do olho destes animais sugere que alguns géneros de ictiossauro, nomeadamente o Ophthalmosaurus, possam ter sido mergulhadores de profundidade, como o cachalote hoje em dia. O peso do ictiossauro é incerto, mas alguns espécimes podem ter pesado até 1,7 toneladas.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 3:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("3- Os plesiossauros\n-------------------------------------------------------------------------------------\neram uma ordem de répteis marinhos que surgiram no início do Jurássico Inferior e se extinguiram no final do Cretáceo Médio. Eles eram animais carnívoros e alimentavam-se de peixes, lulas e outros animais marinhos. Os plesiossauros eram répteis gigantes e carnívoros do Mesozoico, mas não estavam relacionados com os dinossauros, que formavam um grupo à parte. Existem dois tipos ecológicos de Plesiosauria: um composto por animais de pescoço longo e cabeça pequena, enquanto o outro continha animais de pescoço curto e cabeça alongada. Ambos possuíam o tronco rígido e pesado, membros que funcionavam como remos e as narinas localizadas no alto da cabeça, imediatamente em frente aos olhos. A hiperfalangia aumentava o tamanho dos remos e alguns espécimens apresentavam até 17 falanges por dígito. Junto com os mosassauros, os plesiossauros estavam no topo da cadeia alimentar dos oceanos. O Plesiossauro foi um dos primeiros fósseis a ser descoberto e gerou grande interesse na Era vitoriana. O peso do plesiossauro é incerto, mas alguns espécimes podem ter pesado até 2 toneladas. Já a altura do plesiossauro é difícil de ser determinada, pois o tamanho do pescoço e do corpo variava muito entre as espécies. O comprimento total do corpo de um plesiossauro podia variar de 3 a 14 metros.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 4:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("4- Platecarpus\n-------------------------------------------------------------------------------------\né um gênero extinto de lagartos aquáticos pertencentes à família Mosasauridae, que viveram durante o período Cretáceo, cerca de 84-81 milhões de anos atrás. Fósseis foram encontrados nos Estados Unidos, Bélgica e África . Platecarpus era um réptil aquático gigante que crescia até 5,67 metros de comprimento. Eles eram predadores ferozes e se alimentavam de peixes, lulas e outros animais marinhos. Platecarpus tinha um corpo fusiforme com dois pares de nadadeiras laterais e uma cauda longa e curvada com um grande lobo dorsal. A estrutura do crânio de Platecarpus é única entre os mosassauros, com uma cabeça curta e menos dentes do que qualquer outro mosassauro. Um espécime bem preservado de Platecarpus mostra que ele se alimentava de peixes de tamanho moderado e pode ter se alimentado também de lulas e amonites. Platecarpus não nadava como uma enguia, mas sim como um tubarão moderno, com poderosas nadadeiras caudais. O peso do Platecarpus é incerto, mas alguns espécimes podem ter pesado até 2 toneladas.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 5:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("5- Halisaurus\n-------------------------------------------------------------------------------------\né um gênero extinto de réptil marinho pertencente à família Mosasauridae, que viveu durante o período Cretáceo, cerca de 86-66 milhões de anos atrás. Halisaurus era um mosassauro relativamente pequeno, com cerca de 3-4 metros de comprimento. Eles eram predadores ferozes e se alimentavam de peixes, lulas e outros animais marinhos. Halisaurus tinha um corpo fusiforme com duas nadadeiras laterais e uma cauda longa e curvada com um grande lobo dorsal. A estrutura do crânio de Halisaurus é única entre os mosassauros, com uma cabeça curta e menos dentes do que qualquer outro mosassauro. Halisaurus apareceu relativamente cedo na história evolutiva dos mosassauros, durante o Santoniano. Como tal, o gênero retém muitas características primitivas, assim como a subfamília Halisaurinae em geral.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            case 6:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Que pena tente conhecer melhor alguma especie da proxima vez");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;

                            default:
                            system("cls");
                                printf("-------------------------------------------------------------------------------------\n");
                                printf("Numero invalido, estou te encaminhando para o salao principal, Ate logo.");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                printf("clique qualquer tecla para retornar");
                                printf("\n-------------------------------------------------------------------------------------\n");
                                getch();
                                break;
                    }
            break;


            default:
                printf("erro");
                break;
            }
            } else if (entrada == 'q' || entrada == 'Q') {
            printf("Voce indicou saida.\n");
        } else if (entrada == 'x' || entrada == 'X') {
            printf("Saindo. Total de pessoas interessadas em entrar: %d\n", contagem);
            break;
        } else {
            printf("Opcao invalida. Tente novamente.\n");
            break;
        }
    }else if (codigo == 'a' || codigo =='A'){

    int senha = 912;
    system("cls");
    printf("-------------------------------------------------------------------------------------\n");
    printf("Bem vindo Administrador\n");
    printf("-------------------------------------------------------------------------------------\n");
    printf("Para assesar seu sistema de vendas Digite a senha:\n");
    printf("-------------------------------------------------------------------------------------\n");
    scanf("%d", &senha);

    if(senha==912){
        char escolha;
    do{
        system("cls");
        printf("-------------------------------------------------------------------------------------\n");
        printf("Escolha\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("1-Nova Venda\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("2-Listar Vendas\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("3-Relatorios de Vendas\n");
        printf("-------------------------------------------------------------------------------------\n");
        printf("4-Sair\n");
        printf("-------------------------------------------------------------------------------------\n");
        scanf(" %c", &escolha);

        switch(escolha){
        case '1':
            system("cls");

            printf("-------------------------------------------------------------------------------------\n");
            printf("Digite cod: ");
            scanf("%d", &vd[qtde].cod);
            printf("-------------------------------------------------------------------------------------\n");
            printf("Digite nome: ");
            scanf("%s", &vd[qtde].nome);
            printf("-------------------------------------------------------------------------------------\n");
            printf("Digite idade: ");
            scanf("%d", &vd[qtde].idade);
            printf("-------------------------------------------------------------------------------------\n");
            printf("Digite tipopgto: ");
            scanf("%s", &vd[qtde].tipopgto);
            printf("-------------------------------------------------------------------------------------\n");
            if (vd[qtde].idade<16){
                vd[qtde].preco=10.00;
                ttmeia++;
            }
            else if(vd[qtde].idade>=60){
                vd[qtde].preco=0.00;
                ttisento++;
            }
            else{
                vd[qtde].preco=20.00;
                ttinteira++;
            }
            qtde++;

            getch();
            break;
        case '2':
            system("cls");

            int cont;
            for(cont=0; cont<qtde; cont++){
                printf("-------------------------------------------------------------------------------------\n");
                printf("Cod = %d\n", vd[cont].cod);
                printf("==========================\n");
                printf("Nome = %s\n", vd[cont].nome);
                printf("==========================\n");
                printf("Idade = %d\n", vd[cont].idade);
                printf("==========================\n");
                printf("Preco = %.2f\n", vd[cont].preco);
                printf("==========================\n");
                printf("Tipo Pgto = %s\n\n", vd[cont].tipopgto);
                printf("-------------------------------------------------------------------------------------\n");

            }

            getch();
            break;
        case '3':
            system("cls");

            printf("-------------------------------------\n");
            printf("Total de vendas: %d\n", qtde);
            printf("Valor total das vendas: %.2f\n\n", ttinteira*20.00+ttmeia*10.00);
            printf("-------------------------------------\n");
            printf("Total de inteiras: %d\n", ttinteira);
            printf("Valor total de inteiras: %.2f\n\n", ttinteira*20.00);
            printf("-------------------------------------\n");
            printf("Total de meia: %d\n", ttmeia);
            printf("Valor total de meia: %.2f\n\n", ttmeia*10.00);
            printf("-------------------------------------\n");
            printf("Total de isento: %d\n", ttisento);
            printf("-------------------------------------\n");
            getch();
            break;

        case '4':
            system("cls");
            printf("-------------------------------------------------------------------------------------\n");
            printf("Encerrando......\n");
            printf("-------------------------------------------------------------------------------------\n");
            //codigo='z';
            getch();
            break;
        default:
            system("cls");
            printf("-------------------------------------------------------------------------------------\n");
            printf("Opcao invalida\n");
            printf("-------------------------------------------------------------------------------------\n");
            getch();
            break;
        }

    }while(escolha!='4');

    }else{
        printf("Senha invalida, obrigado.");
    }


        }else{
            printf("salve");
        }

    }while(codigo != '0');


}

