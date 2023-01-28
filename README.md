# PROJETO-INDIVIDUAL-Modulo-4-Sistema-Resilia 

-

<h2>A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.</h2>

<h3>Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo:</h3>
<h4>
⇨ Existem outras entidades além dessas três?

- Sim, para este projeto foram criados, alem de cursos, turma e aluno; foram criados tambem: resilia e facilitador.

⇨ Quais são os principais campos e tipos?

- Os principais campos são as chaves primarias (PK) que são elas : id-cursos, id-turma, id-aluno, id-resilia e id-facilitador ; todos possuem seu valor int, tambem serão usadas as mesmas como chave extrangeira (FK).

⇨ Como essas entidades estão relacionadas?

- As entidades se relacionam da seguinte forma : A resilia (1,n) Cria o curso (1,1); O curso (1,n) tem turmas (1,1); O aluno(1,1) se matricula na turma (1,n); O facilitador (1,n) cordena a turma (1,1).  

</h4>


<h4> Abaixo segue os modelos logico e conceitual citados a cima.

<img src="https://github.com/Jhonatanpmp/PROJETO-INDIVIDUAL-Modulo-4-Sistema-Resilia/blob/main/projeto%20individual%20(modulo%204).png">
<p></p>
<img src="https://github.com/Jhonatanpmp/PROJETO-INDIVIDUAL-Modulo-4-Sistema-Resilia/blob/main/projeto%20individual%20(modulo%204)_logico.png".>

<h4> Para este projeto foi utilizado o site:
-Br Modelo Web
</h4>
