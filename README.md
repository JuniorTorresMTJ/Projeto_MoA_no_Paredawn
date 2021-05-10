# Projeto MoA no Paredawn
Projeto sobre Bioinformatica - Mecanismos de Ação (MoA)
<p align= "center">
<img src="https://github.com/JuniorTorresMTJ/Projeto_MoA_no_Paredawn/blob/main/image/inicio.png" >
</p>
<p align= "center">
<img src="https://camo.githubusercontent.com/1c41257b2a5d69c6ff859393ab19fb2061d3e76798128083772ecce35c30978e/68747470733a2f2f7777772e616c7572612e636f6d2e62722f6173736574732f696d672f696d6572736f65732f696d657273616f2d6461646f732f6c6f676f2d6d657273616f2e313631363530313139372e737667" min-width="300px" max-width="200px" width="300px" >
</p>

## **MODELO PREDITIVO PARA PREVER O ATIVAMENTO DO MOA E MODELO PARA PREVER O TRATAMENTO DO EXPERIMENTO**

Os dados falaram: Qualquer coisa me bota no Paredawn, eu como um bom Cientista de dados... fui lá coloquei e analisei!
<p align= "center">
<img src="https://github.com/JuniorTorresMTJ/Projeto_MoA_no_Paredawn/blob/main/image/paredawn.gif" min-width="300px" max-width="200px" width="300px" >
</p>

### **OBJETIVO**
O objetivo desse projeto é o desenvolvimento de duas maquinas preditivas, com o intuito de auxilar na descoberta de novos medicamentos através dos MoAs (Mecanismo de Ação).

1. Primeiro Objetivo: Criar uma Maquina preditiva que consiga prever se o experimento irá ativar um ou mais MoAs, com um F1-score maior que 80%.
2. Segundo Objetivo: Criar uma Maquina preditiva que consiga prever se o experimento foi tratado com droga ou com_controle.


 ### **ESCOPO**
 Você deve estar se perguntando: MoA? que treco é esse?<br>
 MoA em inglês é Mechanisms of Action o que significa em português: Mecanismos de Ação.
 É a interação de uma droga (remédio) com uma enzima ou um receptor. Qualquer substância absorvida ou administrada, possuirá um mecanismo de ação.<br>
 
Antes, as descobertas de novos medicamentos eram feitas por tentativa e erro, portanto, com esse projeto, o objetivo é automatizar uma das partes do processo, pois conseguir prever ou identificar se o experimento vai ou não ativar um mecanismo de ação ou saber se foi utilizado uma droga ou não no experimento, gera diversos benefícios, como por exemplo: o tempo.
 

### **SOBRE O PROJETO**
<div align = "left">
O projeto está estruturado da seguinte forma:<br>

   * [Objetivos do Projeto](#Sobre)
   * [Contextualizando](#Sobre)
   * [Importação das Bibliotecas](#tabela-de-conteudo)
   * [Carregamento das Bases](#instalacao)
   * [Analise Exploratória](#como-usar)
   * [Pré-processamento dos Dados](#testes)
      * [Transformações nas Variáveis](#pre-requisitos)
      * [Balanceamento dos Dados](#pre-requisitos)
      * [Seleção de Variáveis](#pre-requisitos)
   * [Levantamento das Hipóteses](#tecnologias)
   * [Criação das Máquinas Preditivas](#tecnologias)
      * [Regressão Logística](#pre-requisitos)
      * [XGBoost](#pre-requisitos)
      * [RandomForest](#pre-requisitos)
   * [Avaliações do Modelo](#tecnologias)
      * [F1-Score](#multiple-files)
      * [Recall](#multiple-files)
      * [Accuracy](#multiple-files)
      * [Precision](#multiple-files)
   * [Conclusão](#tecnologias)
</div>
O projeto foi desenvolvido de uma forma linear, então mostro todo o processo de pensamento e tratamento dos dados até chegar a conclusão.<br>
<br>

<p align= "left">
Qualquer feedback, elogio, sugestão de melhoria eu ficaria muito grato!
</p>

<a  href="https://www.linkedin.com/in/marivaldotorres/">
    <img align="left"alt="Junior Torres | Linkedin" width="24px" src="https://github.com/JuniorTorresMTJ/JuniorTorresMTJ/blob/master/image/linkedin.svg" />
  </a>

  <a href="https://www.instagram.com/callmejuniorr/">
    <img align="left" alt="Junior Torres | Instagram" width="24px" src="https://github.com/JuniorTorresMTJ/JuniorTorresMTJ/blob/master/image/instagram.svg" />
  </a>
  <a href="mailto:juniortorres.mth@gmail.com">
    <img align="left" alt="Junior Torres | Gmail" width="26px" src="https://github.com/JuniorTorresMTJ/JuniorTorresMTJ/blob/master/image/gmail.svg" />
  </a>
<br>

Fonte dos Dados: [Kaggle](https://www.kaggle.com/c/lish-moa/overview/description)

<p align= "left">
<img src="https://github.com/JuniorTorresMTJ/Projeto_MoA_no_Paredawn/blob/main/image/mergulher.gif" min-width="300px" max-width="200px" width="300px" >
</p>
<p align= "right">
<img src="https://github.com/JuniorTorresMTJ/Projeto_MoA_no_Paredawn/blob/main/image/bolhas.gif" min-width="300px" max-width="200px" width="100px" >
</p>
