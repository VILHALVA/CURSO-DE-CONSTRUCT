# CRIAMOS UM ITEM PARA SER COLETADO
Para criar moedas ou itens colecionáveis que podem ser coletados no Construct 3, você precisará usar eventos para detectar quando um personagem ou objeto colide com o item e, em seguida, aplicar a lógica para coletá-lo. Aqui estão os passos para criar moedas ou itens colecionáveis em seu jogo:

**Passo 1: Criar o Item Colecionável (Moeda):**

1. No Construct 3, adicione um novo objeto sprite que representará sua moeda ou item colecionável. Certifique-se de importar uma imagem apropriada para o objeto.

2. Posicione o objeto no layout onde você deseja que a moeda apareça.

**Passo 2: Configurar Comportamento do Item:**

1. Selecione o objeto da moeda na janela de edição.

2. Na janela de propriedades, vá para a seção "Behaviors" (Comportamentos).

3. Adicione o comportamento "Solid" (Sólido) ao objeto da moeda. Isso permite que o objeto colida com outros objetos.

**Passo 3: Criar Eventos para Coletar o Item:**

Agora, você precisa criar eventos para detectar quando o personagem ou objeto do jogador entra em contato com a moeda e coleta-a.

1. Na janela de eventos, clique com o botão direito na área de eventos e selecione "Add Event" (Adicionar Evento).

2. Escolha o gatilho apropriado para detectar a colisão com a moeda. Você pode usar "On collision with another object" (Na colisão com outro objeto) e escolher o objeto do jogador como o objeto de colisão.

3. Adicione a ação "Destroy" (Destruir) para a moeda. Isso fará com que a moeda seja removida do jogo quando for coletada.

4. Se desejar, você pode adicionar ação para aumentar a pontuação do jogador ou atualizar a contagem de moedas coletadas.

**Passo 4: Teste a Coleta de Moedas:**

Clique no botão "Preview" (Visualizar) para testar o jogo e ver se o personagem pode coletar as moedas. Certifique-se de que a moeda desapareça quando colidida e que sua pontuação ou contador de moedas seja atualizado conforme necessário.

**Passo 5: Ajustes e Polimentos:**

Ajuste a posição das moedas e adicione mais moedas em diferentes partes do jogo, se necessário. Você também pode adicionar efeitos visuais ou sons para tornar a coleta de moedas mais gratificante.

A criação de itens colecionáveis, como moedas, é comum em muitos jogos e pode adicionar um elemento de desafio e recompensa à sua experiência de jogo. Certifique-se de personalizar a lógica de coleta de acordo com as necessidades específicas do seu jogo e de testar minuciosamente para garantir que funcione como o esperado.