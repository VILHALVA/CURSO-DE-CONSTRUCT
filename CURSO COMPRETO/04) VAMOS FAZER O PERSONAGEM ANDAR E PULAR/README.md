# VAMOS FAZER O PERSONAGEM ANDAR E PULAR!
Andar e pular com um personagem no Construct 3 envolve o uso de eventos e ações para controlar o movimento do personagem. Vou guiá-lo pelos passos básicos para criar um personagem que possa andar e pular em seu jogo:

**Passo 1: Criar o Personagem**

1. Abra o Construct 3 e carregue seu projeto.

2. No layout em que deseja que o personagem apareça, adicione um objeto de personagem. Isso pode ser um sprite que represente o personagem.

**Passo 2: Configurar Controles de Movimento**

1. Crie um novo evento para controlar o movimento do personagem.

2. Use os gatilhos de teclado para detectar as teclas pressionadas. Por exemplo, você pode usar "On key pressed" para detectar quando a tecla de seta para a direita é pressionada.

3. Associe a ação "Set character X" ao evento para mover o personagem para a direita. Defina a quantidade pela qual o personagem se moverá quando a tecla for pressionada.

4. Repita o processo para adicionar lógica para mover o personagem para a esquerda, usando a tecla de seta para a esquerda.

5. Adicione eventos para lidar com o movimento vertical (pular). Por exemplo, quando a tecla de seta para cima é pressionada, você pode aplicar uma ação para que o personagem pule.

**Passo 3: Lidar com a Gravidade e Colisões**

1. Para criar uma sensação realista de gravidade, você pode usar eventos para aplicar uma força descendente constante no personagem. Isso fará com que o personagem caia quando não estiver pulando.

2. Use colisões para detectar se o personagem está no chão. Se o personagem estiver no chão, permita o salto. Se não, impeça que ele pule novamente até que aterrissar.

**Passo 4: Teste o Movimento do Personagem**

1. Clique no botão "Preview" (Visualizar) no topo para testar o movimento do personagem no layout.

2. Certifique-se de que o personagem possa andar para a direita, para a esquerda e pular com base nas configurações de eventos que você definiu.

3. Faça ajustes conforme necessário para afinar o movimento e o salto do personagem.

Este é um guia básico para criar um personagem que possa andar e pular no Construct 3. A lógica exata e os eventos variarão dependendo dos detalhes do seu jogo e dos comportamentos desejados para o personagem. À medida que você ganha mais experiência com o Construct 3, pode adicionar elementos como animações de personagens, controles mais avançados e mecânicas de jogo adicionais para criar um jogo mais envolvente.