<!DOCTYPE <html>
<html lang="pt-br">

<style>
@charset "UTF-8";
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
@font-face {
    font-family: idroid;
    src: url(../fontes/idroid.otf);
    font-weight: normal;
}
/*
#c5ebd6
#83e1ad
#3ddc84
#2fa866
#1a5c37
#063d1e
*/


#PROJETO {
    background-color: var(--cor4);
}

:root {
    --cor0: #dbd9b3;
    --cor1: #83e1ad;
    --cor2: #3ddc84;
    --cor3: #2fa866;
    --cor4: #1a5c37;
    --cor5: #063d1e;

    --fonte-padrao: Arial, Verdana, Helvetica, sans-serif;
    --fonte-destaque: "Bebas Neue", cursive;
    --fonte-androif: "idroid", cursive;
}

* { /* determina margin e padding para tudo*/
    margin: 0px;
    padding: 0px;
}

body{
    background-color: var(--cor0);
    font-family: var(--fonte-padrao);
}
a.externo::after {
    content: "\1F517";
}


header {
    background-color: var(--cor4);
    min-height: 150px;
    text-align: center;
    padding-top: 30px;
    background-image: linear-gradient(to bottom, var(--cor3), var(--cor5));
}
header > h1 {
    color: white;
    font-family: var(--fonte-destaque);
    font-size: 3em;
    margin-bottom: 20px;
    text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.5);
    font-weight: normal;
}
header > p {
    font-family: var(--fonte-padrao);
    font-size: 1.2em;
    color: white;
    max-width: 600px;
    padding: 0 10px 0 10px;
    margin: auto;
    text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.5);
}


nav {
    background-color: var(--cor5);
    padding: 10px;
    box-shadow: 0px 7px 9px rgba(0, 0, 0, 0.250);
    text-align: center;
}
nav a {
    color: var(--cor1);
    padding: 10px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px 5px 0 0;
    transition-duration: 0.3s;


}
nav > a:hover {
    background-color: var(--cor3);
    color: var(--cor5);
    font-size: 18px;
}


main {
    min-width: 300px;
    max-width: 1000px;
    margin: auto;
    margin-bottom: 30px;
    padding: 20px;
    background-color: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
    border-radius: 0 0 10px 10px;
}
main img {
    width: 100%;
}
main img.pequena {
    display: block;
    max-width: 400;
    margin: auto;
}
div.video {
    background-color: var(--cor5);
    margin: 0px -20px 30px -20px;
    padding: 20px;
    padding-bottom: 56.60%;
    position: relative;
}
div.video > iframe {
    position: absolute;
    top: 5%;
    left: 5%;
    width: 90%;
    height: 90%;
}

main h1 {
  font-family: var(--fonte-androif);
  color: var(--cor4);
  font-size: 1.3em;
  background-image: linear-gradient(to right, var(--cor1), transparent);
  text-indent: 8px;
  font-weight: normal;
}
main h2 {
    font-family: var(--fonte-androif);
    color: var(--cor4);
    font-size: 1.3em;
    background-image: linear-gradient(to right, var(--cor1), transparent);
    text-indent: 8px;
    font-weight: normal;

}
main h3 {
    font-family: var(--fonte-androif);
    color: var(--cor4);
    font-size: 1.3em;
    background-image: linear-gradient(to right, var(--cor1), transparent);
    text-indent: 8px;
    font-weight: normal;

}
main p {
    margin: 15px 0;
    text-align: justify;
    text-indent: 30px;
    font-size: 1em;
    line-height: 2em;
}
main strong {
    color: var(--cor4);
    font-weight: bold;
    padding: 2px 6px;
}
main a {
    text-decoration: none;
    font-weight: bold;
    color: var(--cor5);
    background-color: var(--cor1);
    padding: 2px 6px;
    border-radius: 5px;
}
main a:hover {
    text-decoration: underline;
    color: var(--cor4);

}


aside {
    background-color: var(--cor1);
    padding: 10px;
    border-radius: 10px;
    box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.37);
}
aside ul {
    list-style-type: "\2714\00A0";
    list-style-position: inside;
    columns: 2;
}
aside li {
    cursor: help;
}
aside h3 {
    background-color: var(--cor4);
    color: white;
    padding: 10px;
    margin: -10 -10 0 -10;
    border-radius: 10px 10px 0 0;
}

footer {
    background-color: var(--cor5);
    color: white;
    text-align: center;
    font-size: 1em;
    padding: 5px;
}
footer a {
    color: white;
    font-weight: bolder;
    text-decoration: none;
}
footer a:hover{
    text-decoration: underline;
    color: var(--cor1);
}

</style>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="estilo/style.css">

    <title>Eletiva de robótica</title>

</head>
<body>
    <header>
        <h1>DIY: PROJETANDO E PROGRAMANDO - DESENVOLVIMENTO SUSTENTÁVEL</h1>
        <p>Professor Júlio Cesar</p>
    </header>
    <nav>
        <a href="#" id="PROJETO">PROJETO</a>
        <a href="#" id="EQUIPES SUCATAS">EQUIPES SUCATAS</a>
        <a href="#" id="EQUIPES LEGO">EQUIPES LEGO</a>
        <a href="#" id="EQUIPE ARDUINO">EQUIPE ARDUINO</a>
    </nav>
    <main>
        <article>

            <h1>JUSTIFICATIVA</h1>
            <p>A sigla DIY, em inglês Do it Yourself (ou faça você mesmo, em português) é um conceito bem amplo e, portanto, pode ser aplicado de diversas formas. Atualmente, existem outras correntes que incorporam a essência do DIY. É o caso do Movimento Maker, que também agrega valores hackers — como as diversas licenças open-source e o ato de compartilhar conhecimento.</p>
              <p>Para acompanhar as demandas dos estudantes das novas gerações, novos conceitos e metodologias surgem para associar o ensino à inovação. Nesse contexto, a educação maker emerge com o grande potencial de engajar os estudantes em atividades de aprendizagem muito diferentes da educação tradicional.</p>
              <p>Todos os segmentos da Educação Básica e todas as áreas de conhecimento podem se apropriar das ações experimentalistas do movimento maker para potencializar a aprendizagem dos estudantes. Lembrando, aqui, da importância da intencionalidade pedagógica em todas as práticas realizadas. Ou seja, a implementação de práticas maker no projeto pedagógico não pode fugir das exigências curriculares, devendo ser uma combinação entre teoria e prática.</p>
              <p>O uso de robôs desempenha papel importante para alcançar os objetivos de desenvolvimento sustentável estabelecidos pelas Nações Unidas (17 ODS), que são 17 objetivos ambiciosos e interconectados, que abordam os principais desafios de desenvolvimento enfrentados por pessoas no mundo todo. Os Objetivos de Desenvolvimento Sustentável são um apelo global à ação para acabar com a pobreza, proteger o meio ambiente e o clima e garantir que as pessoas do mundo todo possam desfrutar de paz e de prosperidade. A Federação Internacional de Robótica (IFR) identificou 13 ODS, em que os robôs ajudam a criar um planeta melhor.</p>
              <p>O ambiente educacional vem percebendo a necessidade de integrar o uso de tecnologias como ferramenta de ensino em sala de aula. Essa nova integração tem despertado nos estudantes uma melhor percepção e aprendizado, como por exemplo, no ensino de robótica onde, os discentes aplicam os conceitos de programação, desenvolvem um raciocínio logico e aprendem informática.</p>
              <p>Esse projeto é idealizado para ser executado dentro do Centro de Ensino em Tempo Integral Carlos Drummond de Andrade (CEPI - CDA), localizada no município de Novo Gama - GO</p>
            <h2>OBJETIVOS</h2>
            <p>OBJETIVO GERAL</p>
Desenvolver projetos atendendo a 13 Objetivos de Desenvolvimento Sustentáveis, utilizando as metodologias e ferramentas apresentadas na capacitação, convergindo com as práticas realizadas pelo mercado de trabalho.

<p>OBJETIVOS ESPECÍFICOS</p>
Desenvolver a motricidade fina.
Analisar e entender o funcionamento dos mais diversos mecanismos físicos
Proporcionar a formação de habilidades manuais.
Desenvolver a concentração e a observação
Motivar a precisão de seus projetos

            </p>
            <h3>METODOLOGIA</h3>
            <p>Serão ministradas aulas de robótica, durante as aulas serão desenvolvidos os conhecimentos de programação no qual utilizaremos a IDE do Arduino para desenvolver os códigos fonte dos mesmo e será necessário o aprimoramento da matemática básica, eletrônica básica.</p>
          </p>A turma irá se dividir em 3 grupos para desenvolverem projetos finais distintos.</p>
<p>Serão propostos alguns temas exemplos (irrigação automatizada, coleta seletiva) que os alunos poderão ou não utilizar.</p>
<p>Os projetos finais irão visar desenvolver uma das 13 ODS. Os alunos irão propor um tema no qual eles irão desenvolver a programação (software) e a parte física (hardware) dos projetos que irão utilizar os materiais recicláveis.</p>

            </p>

                        </article>
    </main>
    <footer>
        <p>Website Developed By <a href="https://www.instagram.com/weslleymk1/?hl=pt" target="_blank">Wesley Marques</a>
           & <a href="https://www.instagram.com/julioborges.12/"target="_blank">Professor JC </a>
        </p>
    </footer>
</body>
</html>
