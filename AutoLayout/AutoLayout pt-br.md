AutoLayout

 Quando criamos uma View em um certo tamanho de tela, ao emular em outros dispositivos, veremos que nossos elementos estarão fora de ordem, e isso se dá por que os smartphones tem tamanhos de telas diferentes.
 O AutoLayout serve justamente para evitar esse problema. Construindo uma tela em um tamanho específico, conseguimos manter a proporcionalidade em diferentes tamanhos de tela.  Ele funciona utilizando Constraints, que são "regras" que ajudam manter a proporcionalidade dos elementos.
- Na parte inferior direito, ainda na área de desenvolvimento,  é onde definimos as Constraints do elemento. Após selecionar o elemento desejado, primeiro item da esquerda para a direita, atualiza o elemento para o local original onde ele irá ficar disposto, e o segundo item podemos definir Constraints de Alinhamento, que servem para 'fixar' na vertical ou horizontal um elemento.
- Os Constraints só aparecem para os Elementos selecionados, e cada forma dos Constraints são o inverso da posição que eles definem.
- Para deletar uma Constraint, selecione ela com o mouse(espere aparecer ela mais clara para então clicar) e pressione BackSpace, que funciona como o botão apagar.
- O terceiro item da esquerda para a direita na área inferior direita do ambiente de desenvolvimento, ele é onde conseguimos criar nossas Constraints. Ao selecionar um elemento, abrimos o ambiente de criar Constraints e, ao selecionar a linha da Constraint desejada, ela ficara vermelha e então podemos adicionar o valor e adiciona-la ao elemento.
- No ambiente de desenvolvimento, não é recomendado utilizar toda a tela do dispositivo, temos uma margem superior e inferior para começar a desenvolver, essa margem é chamada de 'Safe Area', que é onde o dispositivo exibe hora, conexão com internet, bateria e etc...
- Ao clicar em um elemento e clicar em uma Constraint, na área de propriedades na direita, podemos alterar seus valores.
- Caso não utilizemos Constraints, o documento View irá avisar que está faltando colocar Constraints no elemento específico, e apresentará erro.
- Linhas - Caso o Elemento tenha um texto muito grande, você pode mudar a propriedade dele de linhas para aparecer mais o texto, e um ponto muito importante é que, se colocar o numero de linhas como '0', o próprio software fará as tratativas para definir a quantidade de linhas necessárias para aparecer todo o texto.
- Para copiar um elemento, podemos usar tanto command(cntrl) + C e command(cntrl) + V, ou segurar o botão optional(Alt), clicar no elemento e arrastar.
 
Dicas: Durante o uso do simulador, nao feche ele para voltar para o desenvolvimento, minimize e aperte o botão de pause ao lado esquerdo do botão de Buildar.
 Outra dica é utilizar o atalho: Command + R para começar a emulação.

 Podemos concluir que para manter um elemento em uma determinada posiçao, podemos misturar tanto os Constrants de tamanho quanto os Constraints de Alinhamento, facilitando construir nossa View.
