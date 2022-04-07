<style>

  *{
    padding:0px;
    margin:0px;
  }

.title {
  position: relative;
  padding-left: 1.25rem;
  color:#2FB4FF;
  margin-bottom: 2.5rem;
}
.title::before {
  content: "";
  position: absolute;
  top: 8px;
  left: 0px;
  width: 3px;
  height: 20px;
  background-color:#4AC08F;
}
  main{
    background-color: #070D1F;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
  .container{
    max-width:1020px;
    padding:2rem; display: grid;
    place-items: cnter;
    gap:2rem;
    grid-template-columns: repeat(2, 1fr); 
  }
  .inspira{
     margin-top:5rem 
  }
  .perfil{
    border:3px solid #2FB4FF;
    border-radius: 1rem; 
    border-radius:5%;
    width:300px;
    margin: 0 auto;
  }
  .text-center{
    place-self:center;
  }

  @media screen and (max-width:768px){
    .clean{
      width:500px;
    }
    .container{
      grid-template-columns: 100%; 
    }
  
    
  }
  li{
    list-style:none
  }

  .social{
      display:grid;
      grid-template-columns: repeat(2, 1fr);
    }
    .social a {
      color:#fff;
      text-decoration:none;
      height:max-content;
      width:max-content;
      /* border:1px solid #4AC08F; */
      border-radius:.2rem;
      padding:1rem;
    }
    .social a:hover{
      color:#2FB4FF;
    }
  /* @media screen and (min-width:) */


.skills{
  width:100%;
  display:grid;
  grid-template-columns: repeat(4, 1fr);
  gap:.5rem;
}

.skills li{
  /* border:1px solid #4AC08F; */
  border-radius:.2rem;
  padding:.8rem;
  text-align:center;
}
.skills li:hover{
  color:#2FB4FF;
  cursor:pointer;
}

</style>

<main>

<div class="container">
  <img class="perfil" src="./.assets/porfile.jpeg">
  <div>
    <h1 style="color:#2FB4FF" class="title"><strong>Yazalde Filimone</h1>
    <p>Actualmente Tenho 17 e sou Desevolvedor FullStack,
    Sou literalmente um <strong style="color:#2FB4FF" >Geeks</strong>, academico e apaxionado por programacao e tecnologia.</p>
    <p>
    <strong style="color:#2FB4FF">Por que gosto de programar:</strong><br>
    <span style="font-size:.800rem; letter-spacing:1px;">
    Os computadores são maravilhosos porque quando você trabalha com eles obtém resultados imediatos que lhe permitem saber se seu
    programa funciona. Poucas coisas na vida lhe dão um retomo desses.
    Foi aí que começou meu fascínio por software.</span>
    </p>

  </div>
</div>
<p style="text-align: center; padding: 2rem;">
  <img src="./.assets/heart.svg">
</p>

<div class="container">
  <p class="text-center" style="font-size:.87rem; 
  ">
  <strong style="color:#2FB4FF" >A minha paixao com a ciencia inicia</strong> na 8 Classe qundo tive a minha primeira aula de fisica desde entao vivia me focando em matematica e fisica, querendo ser inventor, como o (Albert Eisntein3), mas depois de 2 anos eu entrei na area de tecnologia bem especifico na are de hacking mas eu sabia que faltava algo, comecei od meu estudos com python(automacao e scripts de hacking) durante 1 ano,  mas python  nao me satisfazia, entao fui pra o <strong style="color:#2FB4FF" >javascript na area de desevolvimento web</strong> e siceramente me apaxionei pela area e estou dando a minha vida nisso, e comei a estudar arquitetura e padroes de projeto (Clean Archiqueture e Test Drive Developement).
  </p>
  <img class='clean' src="./.assets/clean.svg">
</div>

<div class="container inspira"  >
  <div>
    <h2 style="" class="title" >Minhas Expiracoes</h2>
    <p>De inicio ja vou avisando nao espere ver os grandes nomes da programacoe ou alho semelhante, o que me chama atencao nas pessoas que estao aqui pouca das vezes e o comhecimento que a pesso carega nas costas.</p>
  </div>
  <div>
    <ul>
      <li><strong style="color:#2FB4FF;">Edmilson Jesus</strong> - FullStack Javascript</li>
      <li><strong style="color:#2FB4FF;">Diego Fernandes</strong>- FullStack Javascript</li>
      <li><strong style="color:#2FB4FF;">Rogrido Manguinho</strong> - FullStack Javascript</li>
      <li><strong style="color:#2FB4FF;">Guilherme Rodz</strong> - FullStack Javascript</li>
    </ul>
  </div>
</div>

<div class="container">
  <div>
    <h2 class="title">Minhas Skills</h2>
    <p>A disciplina e a cahve d qualquer sucesso, as minhas longas horas de estudos e pratica me proporcionaram as abilidades que tenho e <strong style="color:#2FB4FF" >Never Stop Lerning </strong></p>
  </div>
  <div class="social">
    <ul class="skills">
      <li>JavaScript</li>
      <li>TypeScript</li>
      <li>NodeJs</li>
      <li>ReactJs</li>
      <li>Sass</li>
      <li>Styled-components</li>
      <li>Nestjs</li>
      <li>Clean Architecture</li>
      <li>Test Drive Developement</li>
      <li>Algorithms</li>
      <li>CSS:3</li>
      <li>HTML:5</li>
    </ul>
  </div>
</div>

<div class="container">
  <div>
    <h2 class="title">Minhas Redes Socias</h2>
    <p>Estou em todas redes que meciono aqui mas e importante lembrar que nas plataformas de whatsapp e contacto pessoal respondo mas rapido.</p>
  </div>
  <div class="social">
    <a href="#">
      <!-- <img src="./.assets/Vector.svg"> -->
      LinkDin
    </a> 
    <a href="#">
      <!-- <img src="./.assets/Vector.svg">  -->
      WhatsApp
    </a> 
    <a href="#">
      <!-- <img src="./.assets/Vector.svg">  -->
      GitHub
    </a> 
    <a href="#">
      <!-- <img src="./.assets/Vector.svg">  -->
      Discord
    </a>
  </div>
</div>
</main>
