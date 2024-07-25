# MANUAL
## ACESSANDO O CONSTRUCT:
1. **Acesse o Site do Construct 3**:
   - Abra o navegador e vá para o site oficial do Construct 3: [Construct 3](https://www.construct.net).

2. **Crie uma Conta ou Faça Login**:
   - Se você não tiver uma conta, clique em "Sign Up" e crie uma conta.
   - Se você já tem uma conta, clique em "Login" e insira suas credenciais.

## CRIANDO UM JOGO DE PLATAFORMA:
1. **Criar um Novo Projeto**:
   - Após o login, clique em "Start New Project".
   - Dê um nome ao seu projeto e escolha as configurações iniciais (você pode manter as configurações padrão para começar).

2. **Adicionar Layout e Event Sheet**:
   - O Construct 3 cria automaticamente um Layout e uma Event Sheet para você.
   - O Layout é onde você desenha o seu jogo.
   - A Event Sheet é onde você define a lógica do seu jogo.

3. **Adicionar Objetos**:
   - **Player**: Clique com o botão direito no Layout, selecione "Insert New Object", escolha "Sprite" e desenhe seu personagem.
   - **Plataformas**: Repita o processo para criar as plataformas onde o personagem irá pular.
   - **Configurar Comportamentos**: Selecione o sprite do Player, vá para a aba "Behaviors" e adicione os comportamentos "Platform" e "Scroll To". Adicione o comportamento "Solid" às plataformas.

4. **Adicionar Controles**:
   - Vá para a Event Sheet e adicione eventos para controlar o movimento do Player. Por exemplo, adicionar eventos para "On Left Arrow Pressed" para mover o Player para a esquerda.

## EXPORTANDO O JOGO:
1. **Preparar para Exportação**:
   - Quando estiver satisfeito com seu jogo, vá para o menu superior e clique em "Menu > Project > Export".

2. **Escolher o Formato de Exportação**:
   - Escolha um formato de exportação adequado, como "HTML5 (Web)", para rodar no navegador ou "NW.js" para rodar como aplicativo nativo no seu PC.

3. **Configurar Exportação**:
   - Siga as instruções do assistente de exportação. Para HTML5, você só precisa escolher a pasta de destino. Para NW.js, você pode escolher opções adicionais como plataforma alvo (Windows, Mac, Linux).

4. **Exportar o Jogo**:
   - Clique em "Export" e aguarde enquanto o Construct 3 prepara os arquivos.

## IMPORTANDO E EXECUTANDO O JOGO:
1. **Para HTML5 (Web)**:
   - Abra a pasta onde você exportou o jogo.
   - Abra o arquivo `index.html` em um navegador para jogar.

2. **Para NW.js (Aplicativo Nativo)**:
   - Abra a pasta onde você exportou o jogo.
   - Execute o arquivo do aplicativo NW.js (por exemplo, `nw.exe` no Windows) para jogar.



