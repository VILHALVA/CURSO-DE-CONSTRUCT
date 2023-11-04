# CRIANDO LÓGICAS PARA A ANIMAÇÃO
Para criar lógicas que controlam a animação de um objeto no Construct 3, você usará eventos para determinar quando e como as animações devem ser reproduzidas. Vou orientá-lo sobre como criar lógica para animar objetos no Construct 3:

**Passo 1: Crie uma Animação:**

Antes de começar a criar lógica, certifique-se de que você já criou uma ou mais animações para o objeto que deseja animar. Você pode criar animações na guia "Animations" (Animações) da janela de propriedades do objeto.

**Passo 2: Crie Eventos de Controle de Animação:**

1. Na janela de eventos, clique com o botão direito na área de eventos e selecione "Add Event" (Adicionar Evento).

2. Escolha o gatilho que acionará a animação. Por exemplo, você pode usar "On start of layout" (No início do layout) para acionar uma animação assim que o layout for carregado.

3. Adicione a ação "Set animation" (Definir animação) para selecionar a animação que deseja reproduzir. Escolha o objeto e a animação apropriada nas opções da ação.

**Passo 3: Crie Condições para a Animação:**

Você pode adicionar condições para controlar quando a animação deve ser reproduzida. Por exemplo, você pode criar uma condição que verifica se o personagem está se movendo antes de ativar a animação de corrida.

1. Em um evento, clique com o botão direito na ação de definição da animação e selecione "Add condition" (Adicionar condição).

2. Escolha a condição apropriada para seu cenário. Por exemplo, você pode usar "Is moving" (Está se movendo) para verificar se o objeto está em movimento.

3. Em seguida, defina a ação de "Set animation" para a animação desejada quando a condição for atendida.

**Passo 4: Controle de Loop e Outras Configurações:**

Você pode definir se a animação deve ser reproduzida em loop ou apenas uma vez, bem como outras configurações de animação.

1. Após a ação "Set animation", você pode adicionar uma ação para definir a propriedade "Loop" para "Yes" (Sim) ou "No", dependendo se deseja que a animação seja reproduzida continuamente.

2. Configure outras opções de animação, como velocidade de reprodução, se necessário.

**Passo 5: Teste e Depure sua Lógica:**

Antes de testar o jogo, revise seus eventos e condições para garantir que a lógica de animação esteja configurada corretamente.

**Passo 6: Execute o Jogo:**

Clique no botão "Preview" (Visualizar) para testar o jogo e verificar se a lógica de animação está funcionando conforme o esperado.

Lembre-se de que a lógica de animação pode variar dependendo das necessidades específicas do seu jogo. Você pode adicionar eventos adicionais para controlar as transições entre animações, reproduzir animações em resposta a ações do jogador e muito mais. A prática e a experimentação são essenciais para se tornar proficiente na criação de lógica de animação no Construct 3.