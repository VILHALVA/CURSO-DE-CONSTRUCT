# CRIANDO UM OBJETO A PARTIR DE OUTRO
No Construct 3, você pode criar objetos durante a execução do jogo usando a ação "Spawn object" (Gerar objeto). Isso permite que você crie dinamicamente instâncias de objetos em resposta a eventos específicos ou ações do jogador. Aqui estão os passos para criar um objeto a partir de outro durante o jogo:

**Passo 1: Crie o Objeto a Ser Gerado:**

Antes de poder invocar um objeto, certifique-se de que você tenha criado o objeto que será gerado. Isso pode ser qualquer objeto que você tenha adicionado ao projeto, como inimigos, itens ou elementos interativos.

**Passo 2: Configurar o Evento para Gerar o Objeto:**

Agora, crie um evento que acionará a geração do objeto. Isso pode ser desencadeado por uma ação do jogador, um evento específico no jogo ou qualquer outra condição relevante. Vamos criar um evento simples como exemplo:

1. Na janela de eventos, clique com o botão direito na área de eventos e escolha "Add Event" (Adicionar Evento).

2. Escolha a condição que acionará a geração do objeto. Por exemplo, você pode escolher "On button clicked" (No clique de um botão) para acionar a geração de um objeto quando um botão é clicado.

**Passo 3: Adicionar Ação para Gerar o Objeto:**

Agora, adicione a ação para gerar o objeto:

1. No mesmo evento, clique com o botão direito na ação e escolha "Add action" (Adicionar ação).

2. Escolha o objeto que gerará o novo objeto. Você pode selecionar o objeto em que o evento está ocorrendo, ou outro objeto se a lógica assim o exigir.

3. Escolha a ação "Spawn another object" (Gerar outro objeto) ou similar, dependendo das opções disponíveis no Construct 3.

4. Configure a ação para especificar o objeto que será gerado e a posição onde ele será criado. Você pode definir a posição exata, as coordenadas X e Y ou em relação a outro objeto, conforme necessário.

**Passo 4: Teste o Jogo:**

Clique no botão "Preview" (Visualizar) para testar o jogo e ver se o objeto é gerado conforme o esperado quando o evento é acionado.

A capacidade de gerar objetos dinamicamente é útil para criar elementos de jogabilidade dinâmicos, como inimigos que aparecem quando um botão é pressionado, ou itens que são criados em resposta a eventos específicos. Personalize os eventos e as ações de acordo com as necessidades do seu jogo. Lembre-se de que você também pode adicionar eventos adicionais para controlar o comportamento dos objetos gerados.