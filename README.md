

<h2>Bootstrap</h2>

<p><strong>btn-block</strong></p>
<p>A classe btn block ajustou os dois botões, de forma que esses tivessem a mesma largura dentro da div. Por serem palavras diferentes os botões ficavam com tamanhos diferentes.</p>

<h2>Css</h2>
<p><strong>style="display: flex;justify-content: center;align-items: center;flex-direction: column;</strong></p>
<p>Código Css para deixar as imagens centralizadas dentro de uma tabela do <emph>Bootstrap</emph></p>


<h2>Angular - PrimeNG</h2>

<p><strong> 
&lt;p-calendar [(ngModel)]="date" appendTo="body"&gt; &lt;/p-calendar></strong>
= aqui ênfase na propriedade appendTo. Ess propriedade permite controlar onde o calendário será renderizado no DOM. Neste exemplo está sendo instruído o PrimeNG renderizar o calendário como um elemento filho direto no 'body'. Técnica útil para evitar que o calendário seja afetado por estilos ou elementos pai que possam limitar sua exibição.</p>

<img src="https://github.com/diogopaza/Estudos-Exemplos-Css-Bootstrap-e-Angular/blob/main/imagens/calendario-errado.png" width="200px" />
<p>Calendário exibido de forma incorreta dentro de uma tabela antes da aplicação da propriedade appenTo="body"</p>

<img src="https://github.com/diogopaza/Estudos-Exemplos-Css-Bootstrap-e-Angular/blob/main/imagens/calendario-correta-new.png" width="200px" />
<p>Calendário exibido corretamente dentro de uma tabela após a aplicação da propriedade appenTo="body"</p>

<h2>Javascript</h2>
<p><strong>const divBotoes = botao.closest('.esconder') as HTMLElement;</strong> === método <strong>closest</strong> busca o elemento pai através da classe passada como parâmetro no método.</p>
<p>No exemplo da imagem um evento é acionado (click no botao), este evento é guardado em uma variável chamada botao, logo após é chamado o método <strong>closest</strong> para guardar na varável divBotoes o elemento acima com contendo a classe esconder. Para finalizar é setado como display = none a variável divBotoes, ou seja, essa div é escondida não aparece na tela para o usuário.</p>
<img src="https://github.com/diogopaza/Estudos-Exemplos-Css-Bootstrap-e-Angular/blob/main/imagens/closest.png" width="400px"/>

<hr width="50%">




