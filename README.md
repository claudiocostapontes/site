/* reset do css */
* {
    margem :  0 ;
    preenchimento :  0 ;
    box-sizing : border-box;
  }
  html {
    comportamento de rolagem : suave;
  }
  corpo {
    exibição : flexível;
    flex-direction : coluna;
    min-altura :  100 vh ;
    font-family :  'Montserrat' , sem serifa;
    tamanho da fonte :  16 px ;
    cor de fundo :  # fff ;
    cor :  # 000 ;
  }
  . título {
    tamanho da fonte :  2 em ;
    text-align : centro;
  }
  de lado {
    exibição : flexível;
    text-align : centro;
    fundo :  # 7F7FD5 ;  /* fallback para navegadores antigos */
    background :  -webkit-linear-gradient (para baixo ,  # 91EAE4 ,  # 86A8E7 ,  # 7F7FD5 );  /* Chrome 10-25, Safari 5.1-6 */
    background :  gradiente linear (para baixo ,  # 91EAE4 ,  # 86A8E7 ,  # 7F7FD5 ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */  
    imagem de fundo :  url ( './../img/hermes-rivera-baRdxMkxv4M-unsplash.jpg' );
    background-repeat : sem repetição;
    posição de fundo : centro;
    tamanho do fundo : capa;
    /*fundo: #7F7FD5; /* fallback para navegadores antigos */
    /*fundo: -webkit-linear-gradient(para baixo, #91EAE4, #86A8E7, #7F7FD5); /* Chrome 10-25, Safari 5.1-6 */
    /*fundo: linear-gradient(para baixo, #91EAE4, #86A8E7, #7F7FD5); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */  
  }
  
  artigo {
  @@ -48,6 +52,14 @@ artigo {
    exibição : nenhum;
  }
  
  . texto-logo {
    font-family :  'Dancing Script' , cursiva;
    tamanho da fonte :  3 em ;
    exibição : bloco;
    altura da linha :  100 % ;
    transformar :  girar ( 336,5 graus )
  }
  
  navegação {
    largura :  100 vw ;
    /* margem superior: 2em; */
  @@ -96,8 +108,8 @@ nav a:hover {
  }
  
  . sobre {
    cor de fundo :  # ebebf7 ;
    imagem de fundo :  url ("data:image/svg+xml,%3Csvg largura='84' altura='84' viewBox='0 0 84 84' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%237f7fd5' fill-opacity='0.16'%3E%3Cpath d='M84 23c-4.417 0-8-3.584-8-7.998V8h -7.002C64.58 8 61 4.42 61 0H23C0 4.417-3.584 8-7.998 8H8V7.002C8 19.42 4.42 23 0 23V38C4.417 0 8 3.584 8 7.998V76H7.002C19.42 76 23 79.58 23 84.98-8-8.417 3.584-8. 7.002C76 64.58 79.58 61 84 61V23ZM59.95c5.054-.5 9-9.764 9-9.948v52h5.002c5.18 0 9.95-9h83v16.05c-5.054.5-9 4.764-9 9.948v74h-5.002 c-5.18 0-9.446 3.947-9.95 9zm-34.1 0H41V66.95c-5.053-.502-9-4.768-9-9.948V52h-5.002c-5.184 0-9.447-3.946-9.975-9H1v16.85c5.053. 9.948V74h5.002c5.184 0 9.447 3.946 9.95 9zm0-82H41v16.05c-5.054.5-9 4.764-9 9.948V32H-5.002C-5.18 0-9.446 3.947-9.95c5.054-.5 9-4.764 9-9.948v10h5.002c5.18 0 9.946-9.947 0H43V16.05C5.053.502 9 4.768 9 9.948v32h5 .002c5.184 0 9.447 3.946 9.95c-5.053-.502-9-4.768-9-9-4.768-9-9-4.768-9-9.94.768-9-9-4.768-9-9.94.768-9-9.94.768-9-9-9.447-3.946-9.95-3.946-9.95-9.946-9.95-9.946-9.95-9zm50 50v7.002C50 61.42 46.42 65 42 65C-4.417 0 -8-3.584-8-7.998v50h-7002C22.58 50 19 46.42 19 42C0-4.417 3.584-8 7.998-8H34V-7002C34 22.58 37.58 19 42 19C4.417 0 8 3.584 8 7.998v34h7.002C61.42 34 65 37.58 65 42c0 4,417-3,584 8-7,998 8H50z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E"998V50H-7002C22.58 50 19 46.42 19 42C0-4.417 3.584-8 7.998-8h34v-7.998-8h34v-7002C34 22.58 37.58 19 42 19C4.417 0 8 3.584 8 7.998v34h7.002c61.42 34 65 37.58 65 42C0 4.417-3.584 8-7.998 8H50z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E"998V50H-7002C22.58 50 19 46.42 19 42C0-4.417 3.584-8 7.998-8h34v-7.998-8h34v-7002C34 22.58 37.58 19 42 19C4.417 0 8 3.584 8 7.998v34h7.002c61.42 34 65 37.58 65 42C0 4.417-3.584 8-7.998 8H50z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
    cor de fundo :  # fff ;
    /* imagem de fundo: url("data:image/svg+xml,%3Csvg largura='84' altura='84' viewBox='0 0 84 84' xmlns='http://www.w3.org/ 2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%237f7fd5' fill-opacity='0.16'%3E%3Cpath d='M84 23c-4.417 0- 8-3.584-8-7-7.998v8h-7.002C64.58 8 61 4.42 61 0H23C0 4,417-3.584 8-7.998 8H8V7.002C8 19.42 4.42 23 0 23V38C4.417 0 8 3.584 8 79.98V76H7.002C19.42 76 23 79.58 23 84H38C0- 4.417 3.584-8 7.998-8h76v-7002c76 64.58 79.58 61 84 61v23zm59.95c5.054-.5 9-4.764 9-9.948v52h5.002c5.18 0 9.95-9.947 9.95-9h83v16.05c-5.054.5- 9 4.764-9 9.948V74h-5.002c-5.18 0-9.446 3.947-9.95 9zm-34.1 0H41V66.95c-5.053-.502-9-4.768-9-9.948V52h-5.002c-5.184 0-9.447-3.768-9-9.948V52h-5.002c-5.184 9H1v16.05c5.053.502 9 4.768 9 9.948V74h5.002c5.184 0 9.447 3.946 9.95 9zm0-82H41v16.05c-5.054.5-9 4.764-9 9.948V32h-5.002c-5.18 0-9.446 3.947-9.95 9H1V24.95c5.054-.5 9-4.764 9-9.948V10h5.002c5.18 0 9.446-3.947 0 9.446-3.947 1 0H43v16.05c5.053.502 9 4,768 9 9,447 3,946 0 9.948V32h5.002c5.184 9,95 9H83V24.95c-5,053-.502-9-4.768-9-9.948V10h-5.002c-5,184 0-9.447-3.946-9.95-9zM50 50V7.002C50 61,42 46,42 65 42 65C-4.417 0-8-3.584-8-7-3.98.58 50 19 46.42 19 42C0-4.417 3.584-4.417 3.584-8 7.998-8H34V-7.998-8H34V-7.962C34 22.58 37.58 19 42 19C4.417 0 8 3,584 8 7,998V34h7,002C61,42 34 65 37,58 65 42c0 4,417-3,584 8-7,998 8H50z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E"); */95-9ZM50 50V7.002C50 61.42 46.42 65 42 65c-4,417 0-8-3.584-8-7.998V50H-7.002C22.58 50 19 46.42 19 42C0-4.417 3.584-4.417 3.584-8 7.998-8H34V-7.998-8H34V-7.962C34 22.58 37.58 19 42 19C4. 417 0 8 3,584 8 7,998V34h7,002C61,42 34 65 37,58 65 42c0 4,417-3,584 8-7,998 8H50z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E"); */95-9ZM50 50V7.002C50 61.42 46.42 65 42 65c-4,417 0-8-3.584-8-7.998V50H-7.002C22.58 50 19 46.42 19 42C0-4.417 3.584-4.417 3.584-8 7.998-8H34V-7.998-8H34V-7.962C34 22.58 37.58 19 42 19C4. 417 0 8 3,584 8 7,998V34h7,002C61,42 34 65 37,58 65 42c0 4,417-3,584 8-7,998 8H50z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E"); */
  }
  
  . avatar {
  @@ -180,8 +192,8 @@ nav a:hover {
  . embrulho {
    cor de fundo :  # fff ;
    preenchimento :  2 rem ;
    raio da borda :  10 px ;
    box-shadow :  0  0  10 px  # bbb ;
    /* raio da borda: 10px; */
    /* box-shadow: 0 0 10px #bbb; */
  }
  
  @media ( largura mínima :  800 px ) {
   BIN +1,66 MB img/hermes-rivera-baRdxMkxv4M-unsplash.jpg 
   12 index.html 
  @@ -1,21 +1,25 @@
  <!DOCTYPEhtml >
  < html  lang =" pt-br " >
  < cabeça >
    < meta  charset =" UTF-8 " >
    < meta  name =" viewport " content =" largura=largura do dispositivo, escala inicial=1.0 " >
    < title > Célia Croche </ title >
    < link  rel =" ícone de atalho " href =" favicon.ico " type =" imagem/x-icon " >
    < link  rel =" icon " href =" favicon.ico " type =" imagem/x-icon " >
    < link  href =" https://fonts.googleapis.com/css2?family=Montserrat&display=swap " rel =" folha de estilo " >
    < link  href =" https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat&display=swap "
      rel =" folha de estilo " >
    < link  rel =" folha de estilo " href =" css/estilo.css " >
  </ cabeça >
  
  < corpo >
    < à parte >
      < classe de figura  =" fundo-logo " >
        < img  class =" logo " src =" img/logo.jpg " alt =" Conjunto de crochê para banheiro " >
      </ figura >
      < div  class =" fundo-logo " >
        < p  class =" texto-logo " > Célia Croche </ p >
      </ div >
      <!-- <figure class="fundo-logo"> -->
        <!-- <img class="logo" src="img/logo.jpg" alt="Conjunto de croche para banheiro"> -->
      <!-- </figura> -->
      < navegação >
        < ul >
          < li >
            < a  href =" #sobre " > Sobre </ a >
          </ li >
          < li >
            < a  href =" #contato " > Contato </ a >
          </ li >
          < li >
            < a  href =" #meus-trabalhos " > Meus Trabalhos </ a >
          </ li >
        </ ul >
      </ nav >
    </ ao lado >
    < section  class =" principal " >
      < article  id =" sobre " class =" sobre " >
        < div  class =" wrap-about " >
          < h1  class =" title text-uppercase " > Sobre </ h1 >
          < figura >
            < img  class =" avatar " src =" img/me.jpg " alt =" Célia Croche " >
          </ figura >
          < p > Olá, eu sou Célia. Conheci o crochê aos 12 anos de idade, desde então faço meus trabalhos. começando fazendo
            como uma distração, as pessoas foram gostando e fazendo encomendas. Estou semper novos modelos, e
            me atualizando, faço sob encomenda, de acordo com o gosto do cliente. Trabalho com produtos de primeira linha
            e confecciono com barbante, linha, fio de malha e etc... </ p >
        </ div >
      </ artigo >
      <!-- <article id="redes-sociais" class="redes-sociais">
        <h1 class="title">Redes Sociais</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, et repellendus eum omnis odio praesentium neque delectus? Repelendus reprehenderit inventore minus cum porro nobis, neque, et esse, est quos tempore.</p>
      </article> -->
      < article  id =" contato " class =" contato " >
        < h1  class =" title text-uppercase " > Contato </ h1 >
        < div  class =" itens " >
          < a  href =" https://web.facebook.com/C%C3%A9lia-Croch%C3%AA-102256941324383 " target =" _blank " >
            < figura >
              < img  src =" img/face.svg " alt =" Facebook " >
            </ figura >
          </a> _ _
          < a  href =" https://wa.me/5511963662377> " target =" _blank " >
            < figura >
              < img  src =" img/whats.svg " alt =" Facebook " >
            </ figura >
          </a> _ _
        </ div >
      </ artigo >
      < article  id =" meus-trabalhos " class =" meus-trabalhos " >
        < h1  class =" title text-uppercase " > Meus Trabalhos </ h1 >
        < h2 > Conheça alguns dos meus trabalhos. </ h2 >
        < div  class =" itens " >
          < classe div  =" cartão " >
            < figura >
              < img  src =" img/coruja(1).jpg " alt =" Jogo de Coruja " >
            </ figura >
            < div >
              < h3 >
                Jogo da Coruja
              </ h3 >
              < p >
                Jogo de Coruja para o banheiro com 3 peças.
              </ p >
            </ div >
          </ div >
          < classe div  =" cartão " >
            < figura >
              < img  src =" img/jogocozinha.jpg " alt =" Jogo de Cozinha " >
            </ figura >
            < div >
              < h3 >
                Jogo de Cozinha
              </ h3 >
              < p >
                Jogo de Cozinha com 3 peças, detalhe flor.
              </ p >
            </ div >
          </ div >
          < classe div  =" cartão " >
            < figura >
              < img  src =" img/mesa.jpg " alt =" Toalha de Mesa " >
            </ figura >
            < div >
              < h3 >
                Toalha para Mesa
              </ h3 >
              < p >
                Toalha para mesa redonda.
              </ p >
            </ div >
          </ div >
          < classe div  =" cartão " >
            < figura >
              < img  src =" img/passadeira.jpg " alt =" Tapete tipo Passadeira " >
            </ figura >
            < div >
              < h3 >
                Passadeira
              </ h3 >
              < p >
                Tapete tipo Passadeira com flor.
              </ p >
            </ div >
          </ div >
          < classe div  =" cartão " >
            < figura >
              < img  src =" img/tapete.jpg " alt =" Tapete Pequeno " >
            </ figura >
            < div >
              < h3 >
                Tapete
              </ h3 >
              < p >
                Tapete Pequeno.
              </ p >
            </ div >
          </ div >
        </ div >
      </ artigo >
    </ seção >
  </ corpo >
  </ html >
