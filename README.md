<h1 align= "center">
    Documentation - Enterprise Management System 
</h1>

<h3 align= "center">
    Sistema de Gerenciamento Empresarial
</h3>


O Sistema de Gerenciamento Empresarial é uma aplicação que foi desenvolvida com o objetivo de atender às necessidades de gestão de uma empresa. Ele consiste em duas partes, uma que utiliza o MySQL como banco de dados e outra que utiliza o Python e o Django para a criação de uma API Rest. 

Para garantir uma maior compatibilidade, as duas partes foram implementadas em contêineres Docker, seguindo as melhores práticas de desenvolvimento de software. Além disso, também foram desenvolvidos testes para garantir a qualidade e integridade do código.

<h4 align= "center">
  Sobre a aplicação
</h4>

####

Um usuário pode se cadastrar no sistema, e após realizar o login poderá cadastrar, editar e excluir os departamentos, projetos e funcionários.
Os funcionários podem ser associados ou removidos aos departamentos e projetos.

Cada projeto possui uma estimativa de carga horária, e quando um funcionário é associado ao projeto, são computadas 8h realizadas a cada dia passado (antes do dia atual), de acordo com o número de funcionários.

Os funcionários podem ser associados aos projetos desde que o seu acumulo de horas não ultrapasse sua carga horária semanal, que são definidas no cadastro do funcionário.


<blockquote align="center"></blockquote>
