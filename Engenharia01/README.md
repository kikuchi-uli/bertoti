1. Comentário do Texto 1:
   
    Trabalhar com programação, um ofício ainda não regulado, me parece se assemelhar com a prática de um escritor. Não apenas no escrever literal que se faz do código, mas no sentido de que qualquer um pode fazê-lo. A literatura produzida, no entanto, vai depender de qualidades técnicas, da sensibilidade e criatividade da pessoa que a produz. 
A diferença principal, ao meu ver, se dá no intuito da escrita. Um "Escritor de Código" escreve manuais de instrução para um público que não irá reagir emocionalmente ao texto. No processo da escrita, a aplicação de um método de trabalho permite constante teste e revisão do texto (lê-se código), até que o leitor (máquina) entenda e cumpra o objetivo do escritor.
As grandes empresas de software (ou editoras?) acumulam talentos que produzem códigos de altíssima qualidade. A qualidade desse código, porém, não vem apenas do habilidade do programador. Ela está no sucesso do método usado por aquela empresa. Ideia, lógica, código, teste, revisão, e o ciclo segue. Quase como uma cozinha desenvolvendo um novo menu.
O produto, entretanto, está escondido no texto produzido (o código). Ele não está lá para ser lido pelo consumidor final, como seria com um livro ou um prato no restaurante. Ele pode ser uma ferramenta, um tipo de entretenimento, um jeito novo de fazer algo. Chega a ser abstrato. O "importante" ali é o que esse código irá trazer de dentro do mundo digital para o nosso mundo. E, uma vez no nosso mundo, ele está sujeito às infinitas variáveis do existir físico, se tornando, assim como nós, algo que precisará de constante atualização.
---

2. Comentário do Texto 2:

    Apesar de imaterial e, portanto, intangível, o código está sujeito às consequências do mundo material. Não que o mundo material afete imediatamente as linhas de código, mas sua aplicabilidade e escalabilidade estão sujeitas a, por exemplo, limitações físicas e à passagem do tempo - que carrega as inovações responsáveis por tornar certos códigos obsoletos.
A compreensão deste cenário é fundamental no repertório de qualquer pessoa que se aventure a escrever código. 
É essencial que sejam feitas escolhas - trade offs - que irão decidir onde serão feitos sacrifícios em nome da otimização e escalabillidade do código. São essas escolhas  que transformam o código em um reflexo da bagagem e cultura de quem o produz. Por consequência, ainda não há um consenso em um único jeito considerado ideal ou o melhor de fazê-lo.
---

3. Trade Offs:

    1) Velocidade de Entrega vs. Qualidade do Código
       Provavelmente um dos Tradeoffs mais universais entre as áreas do conhecimento de forma geral. Uma entrega bem feita costuma ser oposta a uma entrega feita às pressas. Mas, por definição, o tradeoff é um sacrifício em troca de um benefício. Portanto, se a prioridade é que algo seja entregue urgentemente, faz sentido que a qualidade - que implica revisão, detalhismo, cuidado, atenção e, portanto, tempo - seja sacrificada.
    2) Espaço-Tempo - Re-renderizar vs Armazenar
       Esse tradeoff (Espaço-Tempo) pode se manifestar de diversas formas. Nesse caso, re-renderizar a cada alteração implica na perda de tempo esperando o processamento da imagem e armazenar a imagem ocupa espaço na memória, mas funciona mais rápido. A escolha entre um e outro será diretamente relacionada à intenção do código, e essa talvez seja a melhor definição paralela de tradeoff: intenção.
    3) Consistência vs Disponibilidade
       Este caso traz uma escolha entre ter os dados sempre atualizados, mas temporariamente indisponíveis dada a necessidade de atualização, ou sempre disponíveis, porém temporariamente desatualizados. Se um sistema depende obrigatoriamente da disponibilidade de dados, a atualização desses se torna um evento que requer planejamento e cuidado. Agora, se o compromisso é para com dados precisos, é melhor que eles estejam temporariamente indisponíveis a divulgar ou utilizar dados falsos.
---

4. Minha Contribuição na API:

   Minha contribuição no PI foi dividida em frentes. Minha user story inicial era a de fazer com que o bot conseguisse pegar coordenadas dos endereços do CSV, buscá-las em um mapa e enviar essa localização usando a ferramenta nativa do Telegram de enviar localização. Além disso, participei ativamente das reuniões de discussão de escopo do projeto, lógica geral do código e quais escolhas seriam essenciais para nosso produto. Também fui responsável por integrar o código que extrai coordenadas (feita por um colega), resolver bugs de loop do localizador e das respostas do Bot.
---

5. O Que Aprendi na API:

   Além de entender como funciona a produção de um código com mais de uma pessoa envolvida, aprendi a usar pesquisar e entender novas bibliotecas (como o DSPy, o OpenStreetMaps, etc) entendi como testar e encontrar problemas (de grau relativamente simples) no código e também a verificar se sua lógica está fazendo sentido. Além do aprendizado coletivo de comunicação e colaboração, aprendi a confiar na minha capacidade de pesquisar e encontrar soluções para problemas que eu nem conhecia.
