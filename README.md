# Jogo-da-velha <img src="https://user-images.githubusercontent.com/53665910/204693283-63d40418-46d0-477f-be0c-5fa72fe0c154.png" width="40" height="40"/>

Projeto final da disciplina de Arquitetura de Software - Demo jogo da velha em **HTML** <img src="https://cdn-icons-png.flaticon.com/512/5968/5968267.png" width="20" height="20"/> + **CSS** <img src="https://cdn-icons-png.flaticon.com/512/5968/5968242.png" width="20" height="20"/> + **REACT**   <img src="https://user-images.githubusercontent.com/53665910/204693043-fc33a4d1-a897-4561-8782-372241cd2b40.png" width="20" height="20"/>


# Jogo da velha encontrado no tutorial da documentação do React
**Tutorial:** https://pt-br.reactjs.org/tutorial/tutorial.html


# Autores
Danny Sullivan e Deisilani Nunes

# Conceitos
O React é uma biblioteca JavaScript <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="20" height="20"/>  declarativa, eficiente e flexível para criar interfaces com o usuário. 

Ele permite compor UIs complexas a partir de pequenos e isolados códigos chamados “componentes”.

possibilita aos desenvolvedores criarem aplicações web, tendo a facilidade de alterar elementos ou os dados exibidos, sem recarregar a página. Por exemplo, o número de likes de uma rede social pode aumentar ou diminuir sem a necessidade de realizar o refresh na página.

# Arquitetura 
O React trabalha com o modelo de arquitetura mvc (model, view controller).

MODEL: classes que armazenam os dados manipulados pela aplicação e que têm a ver com o domínio do sistema em construção. 

View: classes responsáveis pela apresentação da interface gráfica do sistema, incluindo janelas, botões, menus, barras de rolagem, etc.

controller: classes que tratam e interpretam eventos gerados por dispositivos de entrada, como mouse e teclado.

# Objetivos
O diferencial do React é ser rápida, escalável e simples, podendo ser usada com outras bibliotecas ou frameworks de JavaScript, como o Angular JS. 

Essa amplitude de funcionalidades e sua forma descomplicada de realizar processos são os responsáveis pela ferramenta ser tão buscada pelos programadores.

# Elementos

**Props:** Um componente recebe parâmetros, chamados props (abreviação de propriedades), e retorna uma hierarquia de elementos para exibir através do método render.

**RENDER:** o método render retorna uma descrição do que você deseja ver na tela. React recebe a descrição e exibe o resultado. Em particular, render retorna um elemento React, que é uma descrição simplificada do que renderizar.



# Funcionalidades do Jogo:

- Um jogador ganha reivindicando 3 células que caem em uma linha horizontal, vertical ou diagonal.
- Os jogadores empatam se não houver mais movimentos possíveis (ou seja, todas as células são reivindicadas).
- Botão de reiniciar a partida.
- Ao clicar no botão de reiniciar, exibe uma caixa de diálogo perguntando ao usuário se ele tem certeza, se clicar no "OK", reinicia a partida, se clicar em cancelar, a caixa de diálogo é fechada e o jogo atual é retomado.
- Quando o jogo termina, exibe uma caixa de diálogo indicando o vencedor ou o empate, juntamente com um botão de iniciar uma nova partida.
- O aplicativo guarda as vitórias de cada jogador, mesmo após o aplicativo ser fechado, o resultado ainda é mantido.

# **Prints do Jogo**

**Inicio do Jogo**
![image](https://user-images.githubusercontent.com/53665910/205099800-81baedb3-d52d-47b3-940b-fcea769a0670.png)


**Jogador ganhou** 
![image](https://user-images.githubusercontent.com/53665910/205099978-76b578aa-a0fd-4462-94c9-25dcad47832a.png)


**Empate** 
![image](https://user-images.githubusercontent.com/53665910/205100200-7f080db0-a126-46a8-b892-af84f4239a8a.png)


# Instalando

- clone https://github.com/Deisilani/Jogo-da-velha.git
- cd Jogo-da-velha
- npm install
- npm start 


# Licença
Licenciado nos termos da licença MIT.


