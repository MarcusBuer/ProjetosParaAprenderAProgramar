# Projetos para aprender a programar

Uma pequena coletânea de ideias de projetos para aprender a programar páginas web de forma prática, aprendendo conceitos que são solicitados pelo mercado. 
Caso queira incluir uma ideia mande um issue, seguindo o mesmo formato utilizado para as outras ideias, se possível com exemplos e extras.


## Nível Iniciante

### 🕗 Timers 
Uma página com timer ajustável, podendo ser utilizado em dois modos: incremental ou countdown, utilizando funções nativas da linguagem (não utilizar bibliotecas).
Exemplos de uso: tempo para iniciar uma livestream, tempo até o lançamento de um filme, organizador de tempo tipo pomodoro.

Extras:

- [ ]  Manter evento salvo entre sessões
- [ ]  Receber um alerta quando o evento encerrar
- [ ]  Definir múltiplos eventos

### 📄 Bloco de Notas
Um página para gerenciar anotações, onde se possa criar, editar, deletar e salvar as notas.

Extras:

- [ ]  Utilizar Markdown e converter para HTML para exibição
- [ ]  Manter histórico de quando as notas foram criadas

### 🍵 Receitas
Uma página com uma sequência lógica para chegar em um resultado, podendo ser utilizados recursos multimídia para exemplificar as etapas.
Exemplos de uso: receitas culinárias, instruções técnicas, guias de montagem de produtos, manuais.

Extras:

- [ ]  Salvar receitas em um banco de dados
- [ ]  Utilizar busca para procurar receitas cadastradas

### ✏️ Questionário / Quiz
Uma página com um questionário (não existem respostas corretas) ou Quiz (existem respostas corretas).

Exemplos de uso: Questionário para verificar preferências dos usuários, Quiz para testar habilidades em programação.

Extras:

- [ ]  Poder criar um usuário com registro de todos os questionários e quizzes criados por ele, e as respostas que recebeu, assim como as respostas que forneceu para quizzes de outros usuários.
- [ ]  Utilizar busca para procurar outros quizzes

### 💰 Organizador de Finanças Pessoais
Uma página que permita o lançamento de gastos e receitas mensais para efetuar o balanço financeiro e crie gráficos e relatórios para melhorar a visualização dos gastos.

Extras:

- [ ]  Permitir a categorização dos gastos e receitas, e visualização por categoria.
- [ ]  Permitir a importação de arquivo CSV contendo os dados.
- [ ]  Permitir a exportação dos dados em formato CSV e PDF com layout de impressão.

### 📺 Criador de Painéis para Twitch
Uma página para criar painéis para uso na Twitch, onde o usuário crie um layout e ao final exporte um arquivo de imagem para fazer upload na Twitch.

Extras:

- [ ]  Permitir salvar as configurações em um arquivo Json e carregar elas novamente.

### 📹 Criador de Frame de Câmera para Twitch
Uma página você selecione efeitos e tamanhos para montar bordas para usar ao redor da câmera ou outras partes do layout.

Extras:

- [ ]  Permitir salvar as configurações em um arquivo Json e carregar elas novamente.
- [ ]  Criar animações para que o frame possa variar de cor com o tempo.


## Nível Intermediário

### 📕 Aplicativo de desenho
Uma página com uma tela virtual onde o usuário possa fazer desenhos com o mouse, mudando a cor, o tamanho da ferramenta e apagar a tela.
Exemplos de uso: jogo de adivinhação, jogo de pintura, anotações rápidas.

Extras:

- [ ]  Usuário pode exportar o desenho como imagem
- [ ]  Usuário pode inserir figuras (retângulo, elipse, estrela, etc)
- [ ]  Usuário pode compartilhar o resultado em mídias sociais

### 📱 Loja Online
Uma página uma lista de produtos que o usuário possa buscar, verificar informações, adicionar ao carrinho e finalizar a compra com uma lista de items (não é necessário implementar um método de pagamento, que é mais avançado e necessita aprender sobre segurança para lidar com os dados de clientes).
Exemplos de uso: Loja de bijuterias, loja de jogos, loja de merch, etc.

Extras:

- [ ]  Página para verificar os produtos atualmente na lista, sendo que para chegar nesta página existe um ícone em todas as páginas mostrando a quantidade de produtos atualmente no carrinho.
- [ ]  Usuário recebe uma confirmação quando o produto é adicionado ao carrinho, ou quando o produto atualmente selecionado já está no carrinho.
- [ ]  Mostrar outros produtos relacionados a este produto, e um botão para voltar a categoria.
- [ ]  Usuário pode, na página do carrinho, atualizar detalhes do produto (cor, tamanho ou modelo) e quantidade para compra, assim como remover produtos do carrinho.
- [ ]  Usuário pode verificar na página do carrinho a soma total do valor de todas as unidades atualmente no carrinho.
- [ ]  Usuário pode clicar em um botão para finalizar a compra, que levaria a uma página mostrando o resultado, ou em um botão para cancelar a compra, o que limpa o carrinho e leva o usuário para a página inicial.
- [ ]  Usuário recebe uma mensagem de erro caso a quantidade solicitada de um item seja maior que a quantidade em estoque.
- [ ]  Especificar método de pagamento e frete na página de finalização (com dados não reais).
- [ ]  Usuário pode simular o valor do frete.
- [ ]  Usuário pode verificar o valor dos impostos incluídos no valor do produto.
- [ ]  Extra-Extra: criação uma página com acesso somente para pessoas autorizadas, com acompanhamento do envio (simulado), alerta de atrasos, inventário de produtos e registro de compras, registrados em banco de dados.

### 📭 Aplicativo de Chat
Uma página com uma tela para incluir o nome do usuário, que ao ser preenchida é levado para uma sala de chat, onde pode enviar e receber mensagem de múltiplos usuários.
Exemplos de uso: Chat para comentários durante uma transmissão de conteúdo, suporte em tempo real para empresas, linhas de auxílio e prevenção a doenças.

Extras:

- [ ]  As mensagens são enviadas a todos os usuários conectados utilizando webSockets
- [ ]  Quando um novo usuário entrar no chat, todos os usuários conectados recebem uma mensagem informando da conexão.
- [ ]  As mensagens ficam salvas em um banco de dados.
- [ ]  Usuários podem mandar imagens, vídeos e links.
- [ ]  Usuário pode selecionar e enviar emojis.
- [ ]  Usuários podem enviar mensagens privadas para outros usuários.
- [ ]  Usuários podem escolher em quais canais querem entrar.

### 🐞 Bug Tracker
Um sistema onde usuários (operadores, setores e gerência) possam criar chamados para setores específicos de acordo com o tipo de chamado. 
O usuário consegue verificar o status de todos os chamados efetuados por ele.
Os setores conseguem verificar chamados efetuados para aquele setor em específico.
A gerência consegue verificar os chamados de todos os setores.

Extras:

- [ ]  Habilitar a visualização apenas para chamados em aberto, apenas chamados em fechado ou todos os chamados.

### 📝 Blog
Um sistema de blog onde autores possam criar, editar e publicar seus conteúdos, e visitantes possam visualizar o conteúdo e efetuar comentários.

Extras:

- [ ]  Separar o conteúdo em categorias/tags e permitir visualizar o conteúdo de categorias/tags específicas.
- [ ]  Criar um sistema de busca para achar posts que contenham uma palavra chave ou expressão.
- [ ]  Utilizar Rich Text para criar e editar os posts, através de um editor WYSIWYG.


## Nível Avançado

### :octocat: Visualizador de Atividade do GitHub
Uma página onde se preencha o usuário do Github e a página apresente em forma de timeline os dados dos repositórios públicos.
Exemplos de uso: jogo de adivinhação, jogo de pintura, anotações rápidas.

Extras:

- [ ]  Usuários podem verificar um resumo da atividade por período  de tempo.
