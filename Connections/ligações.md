LIGAÇõES 

 Abrindo o Código do Storyboard - Primeiro clique sobre a área retangular em cima da tela do celular que está sendo desenvolvido, clique no botão 'ViewController' que fica na direita, vá na área de desenvolvimento no canto superior direito, a opção 'Adjust editor options', ao clicar nela, no menu suspenso vamos acessar a opção 'Assistant', e isso abrirá o código da nossa View, ao lado.
do Storyboard, possibilitando fazer configurações na interface de forma programática. (Se o Xcode não abrir, temos outra opção)
 2˚ Opção - Vá na árvore hierarca de arquivos, vá até o arquivo desejado que você quer abrir, segure o botão 'option' do teclado e clique no código desejado.

Dica: para saber onde a classe abre e fecha(ou outro item), clique na chave que vai marcar todo o corpo dela.

 Os IBoutlets são referencias de elementos de um Storyboard no código  para alterar as Características de um elemento.  Para criar um IBoutlet (uma ligação) de um elemento no código, clique com o cntrl em cima de um elemento, segura e arrasta para o código, e precisa ser dentro da classe da viewCntroller para funcionar, e dessa forma conseguimos ter a ligação no código e podemos programar suas características (Sempre colocar ligações IBoutlet em cima da função 'viewDidLoad()'. Para remover a ligação, clique com o botão direito no elemento e lá terá um 'x' para remover a ligação com o código, não basta apenas remover a linha no código que referencia a ligação.

!Dica de boa prática: Não configurar as características de um elemento pelo inspectors, o ideal é configurar o elemento de forma programática. Sempre manter as ligações IBoutlet em cima da 'viewDidLoad()'.

Obs: Quando ocorre o que está no StoryBoard e quando o que está no código? Ele vai fazer o que está no StoryBoard desde que aquele elemento não tenha uma ligação programática, ai a prioridade é do código. 

Com nossas ligações realizadas, dentro da função 'viewDidLoad()' podemos mudar as características dos nossos elementos. Sempre que fomos utilizar os IBoutlets e mudar as características de um elemento, fazemos isso dentro da função 'viewDidLoad()'.

 Já os IBactions  servem para modificar as ações dos elementos desejados. Para definir uma ligação IBactions, é igual ao IBoutlet mas a 'connection' é como 'action'. Para Ligações IBactions, sempre mantemos elas de baixo da função 'viewDidLoad()' como boa prática.

 Nomeando as ligações: Para nomear, independente do tipo de ligação que seja, utilizamos o camelCase normalmente, mas a ultima palavra do nome tem que representar o que ela é como exemplo: Label, TextField, Button, etc...
 Exemplo: Tenho uma TextField que quero chamar de 'password', então o nome da ligação seria 'passwordTextField'.


Dica: Use command+R para rebuildar o código, ou clique no botão ao lado do play que surge quando o código está rodando. Use command+B para iniciar o Build do código.

Abreviando tipos: Quando você está escrevendo um código e o compilador já sabe qual o tipo que será usado, podemos não escreve-lo para deixar o código mais limpo e conciso.

exemplo: 'view.backgroundColor = UIColor.purple', como nesse caso para um backgroundColor, o compilador espere uma UIColor como resposta, podemos apenas escrever da seguinte forma: 'view.backgroundColor = .purple'.