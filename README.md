# Learning-Docker


Neste repositório estarei aprendendo sobre Docker Fundamentals.

<br>

<div align="right">
    OLÁ TODO!! SOU EU!! O FAVORITO DE TODOS OS AMIGOS [[Vendedor Número 1 de 1997]]. SPAMTON G. SPAMTON!! HAHAEHAEHAHEA!!
</div>

<br>


<div align="right">
<img src="https://media1.tenor.com/m/6KbL2D4bvUQAAAAC/spamton-laugh.gif" width="150px" align="center">

</div>



<p align="right">[[SEJA UM BIG SHOT!]]</p>

---

<div>

| | |
| :--- | :--- |
| POIS BEM, TENHO UMA [[Oferta Especial]] PARA [[Corações]] SOLITÁRIOS COMO VOCÊ!!<ul><li>VAMOS AGARRAR [[Esse Ensino Delicioso]]</ul></li><ul><li>AGARRAR E IRMOS EM DIREÇÃO AO [[CÉU]]!! TÃO ALTO TÃO ALTO QUE SEREMOS [[Hyperlink bloqueado]]</ul></li><ul><li>ENTÃO NÃO SEJA UMA [[Pequena Esponja]] E VAMOS APRENDER ESSE [[Docker]]!!!! | <div align="center"><img src="https://media.tenor.com/8x1FW_yWrYIAAAAi/spamton-deltarune.gif" width="150px"><br>BIG!!</div> |

</div>

---

### O que é Docker?

- Docker é um software livre desenvolvido pela Docker Inc. Ele foi apresentado ao público em geral em 13 de março de 2013 e se tornou desde então algo necessário no mundo da tecnologia.

- Ele permite que os usuários criem ambientes de desenvolvimento independentes e isolados para lançar e implantar suas aplicações. Esses ambientes são, então, chamados de contêineres (containers, em inglês).

<br>

<details>
<summary><b>[[$$DETALHES IMPORTANTES!!!$$]]</b></summary>

<br>

**O Docker é multiplataforma. Você pode lançar seu contêiner em qualquer sistema.**

<br>

**O Docker é rápido. Diferentemente de uma máquina virtual, sua aplicação pode ser inicada em poucos segundos e encerrada com a mesma rapidez.**

<br>

**Observação: você não precisará instalar o Python em seu computador. Ele funcionará no ambiente do Docker para conter o Python que executará o seu código.**

</details>

---

<br>

<div align="right">
    <p>[[1000 KROMERS]]!!</p>
    <img align="right" alt="Gerson" width="150px" src="https://media.tenor.com/RHfFDsuFYNYAAAAi/spamton-deltarune.gif">


</div>

<div>

<h3> MUITO BEM [[Pequena Esponja]]!!!</h3>

</div>

<p> A PARTIR DE AGORA VEREMOS COMO PODEMOS [[Saborear]] MAIS PROFUNDAMENTE DO [[Docker]]!!!. ISSO MESMO!!! AGORA [[Adentraremos]] NA PARTE PRÁTICA!!!!!</p>

<br><br>

- **Instalar Docker em sua máquina(Ubuntu)**

Primeiro, atualize o seu terminal do Ubuntu:

> $ sudo apt update

E em seguida, instale o Docker:

> $ sudo apt install docker.io

Por fim, verifique se o Docker foi instalado corretamente:

> $ sudo docker run hello-world

<br>

<details>
<summary><b>Windows</b></summary>

<br>

**Acesse este link: https://docs.docker.com/desktop/setup/install/windows-install/**

> O QUÊ?!?! NÃO TEM COMO EU TESTAR TODOS OS S.O PARA COMPROVAR PARA VOCÊ [[Custa 200 KROMERS]]!!. NÃO TEM COMO!! NÃO TEM COMO!! NÃO TEM COMO!!

</details>

<br>

<details>
<summary><b>Mac</b></summary>

<br>

**Acesse este link: https://docs.docker.com/desktop/setup/install/mac-install/**

> VOCÊ USA MAC?! [[Pobre Alma Solitária]]. ESCUTE O [[Vendedor Número 1 de 1997]] E TROQUE [[De Vida]] AGORA MESMO!!!!

</details>

---

<br><br>

<h3 align="center">Demonstração:</h3>

<br><br>


<div align="right">
    <p>SÓ PRA VOCÊ SABER EU[[Pobre Miserável]] USO O CODESPACE!!!</p>
    <img align="right" src="https://media.tenor.com/aGOWJrqMLEMAAAAi/spamton-g-spamton.gif" width="150px">
</div>

<div align="center">
    <h3>VEJA [[Atenciosamente]] O EXEMPLO QUE FIZ!!!</h3>
</div>

<div>
    <img align="center" src="teste_docker(1) .jpg" width="500px">
    ACESSE <a href="./teste_docker(1) .jpg">A IMAGEM COMPLETA</a>
    <p> NESTA [[Jpg]] EU CRIEI A IMAGEM PYTHON E FIZ COM QUE O DOCKER BUILDASSE.</p>
</div>

> Para buildar a imagem que você quer, apenas digite no terminal: $ docker build -t python test .
> 
> Em caso de estar utilizando o Github Codespace (Recomendo para quem não possui um notebook com muito disco disponível ou um ambiente virtual adequado), você pode apenas selecionar o código que você deseja buildar e clicar na opção "Build Image"

<br><br>

<div>
    <img align="center" src="teste_funcional_docker(1).jpg" width="500px">
    ACESSE <a href="./teste_funcional_docker(1).jpg">A IMAGEM COMPLETA</a>
    <p>SIM!!! AGORA NESTA [[Jpg]] EU ESTOU MOSTRANDO ALGUNS [[Codes]] E COMO FICARIA O SEU [[Docker Gostoso]] APÓS CRIAR A [[Imagem]]!!!</p>
</div>

<br>

<details>
<summary><b>[[Hyperlink bloqueado]]</b></summary>

> O QUÊ??!! VOCÊ QUER APRENDER OS [[Codes]] DO [[Docker]]??!! SUA [[Pequena Esponja]] É ASSIM QUE SE FALA!!!
>
> FAÇAMOS UM [[Acordo Gostosinho]] PARA IRMOS JUNTOS SER GRANDES!!! GRANDES!!!! GRANDES!!!!!
>
> Aceite o acordo.

</details>

<br><br>

<details>
<summary><b>ACORDO</b></summary>

> ENTÃO ACORDO É ACORDO!!!!
>
> FIQUE AGORA COM OS [[Codes]] DO DOCKER!!! HAHAHAEHAHEAEHA!!!
>
> <img align="right" src="https://media.tenor.com/Q2-C8kWf6FMAAAAi/spamton-glitch.gif" width="130px">
>

<br><br>

> $ docker run help
>
> É um help e lista todos os comandos que podem ajudar a usar o Docker


> $ docker images / docker image
>
> Lista suas imagens


> $ docker image rm [nome da imagem]
>
> Remove uma imagem específica


> $ docker ps -a
>
> Lista todos os contêineres existentes (em execução ou não)

> $ docker rm [nome do contêiner]
>
> Remove um contêiner específico (que não estiver em execução)

> $ docker stop [nome do contêiner]
>
> Parar um contêiner específico