# 3-Joguinhos
Esse trabalho é um projeto desenvolvido por mim para a minha avaliação do meu primeiro período. Minha dupla trancou o curso faltando uma semana para a entrega do trabalho, o que ocasionou neste que vos fala não conseguindo entregar um dos três jogos que deviam ser criados para a tarefa.  

Dito isso, a seguir segue a explicação do funcionamento dos dois jogos feitos, além do menu inicial que liga os três (dois) jogos em um só código.

## Cavalo Celestial Budista
"Cavalo Celestial Budista", ou "Pergunta e Resposta", foi o primeiro jogo mencionado na atividade, além de ser o mais simples. Os requisitos para sua criação foram:
● O jogo conterá um total de cinco perguntas fixas;

● A ordem das perguntas e suas respostas não precisa ser alterada entre
as rodadas;

● Ao finalizar, o jogador poderá optar por jogar novamente ou voltar ao
menu principal.

### Processo de Criação
Quando eu comecei a programar o jogo (e vale ressaltar que esse foi o último que eu fiz), tentei criar uma história para dar ao jogo. Assim, eu poderia dar uma temática para ele, uma explicação que desse ao usuário um motivo para responder as perguntas, e um direcionamento melhor ao escolher as cores que seriam aplicadas no monitor. Foi então que eu lembrei do episódio de Apenas Um Show em que... 
Como eu posso explicar?

![image](https://github.com/user-attachments/assets/a56377cf-12d2-432e-8e43-1803c7751c49)

É... acho que a inspiração já ficou meio óbvia...

### Criação das Perguntas
Então eu basicamente criei o jogo já tendo em mente que as perguntas seriam de um tema comicamente tosco em relação aos riscos presentes na história. Após muito refletir, escolhi que o tema seria "futebol paraense". Infelizmente, eu detesto futebol, então criar tais perguntas não seria possível sem a ajuda da nossa "pessoinha de luz" favorita... o tão aclamado Chat GPT.

https://chatgpt.com/share/67ef4e4e-24a8-8008-a929-67164f46755e

NOTA: o GPT também foi usado para conseguir as cores nas tabelas ASCI, mas esse e outros usos, que foram usados em quase todo o programa, eu vou deixar para falar mais para a frente.

### Funcionamento
O funcionamento do jogo é simples, e na verdade, ao cria-lo eu tentei não fugir muito das instruções iniciais (ao contrário do terceiro jogo). 

Cinco perguntas são feitas ao usuário. Caso estas sejam respondidas corretamente, o usuário marca 1 ponto por cada resposta correta. Ao fim do jogo, o usuário recebe sua pontuação, referente à soma de seus acertos e o final que ele conseguiu na história:

● Até 2 pontos para o final ruim;
● De 3 à 4 pontos para o final neutro; e
● 5 pontos para o final bom.

## Grimórios e Pergaminhos
Grimórios e Pergaminhos foi a minha versão do jogo Gousmas War, mas com algumas alterações nas regras, que eu pedi ao professor a permissão de fazer. Seguem os requisitos iniciais, com as substiutições que eu fiz nos respectivos objetivos.

● Cada jogador inicia com duas Gousmas, cada uma com nível de fúria 1;
####Alteração:
Aqui a mudança foi puramente estética. Ao invés de Gousmas, cada jogador começa com seus dois personagens: Edranyl e Alaric (feiticeiros) ou Gardel e Esdras (magos). Além disso, ao invés dos "níveis de fúria", os personagens possuem "ciclos de mana". 

● Quando uma Gousma ataca outra, transfere todo o seu nível de fúria
para a Gousma atacada;

● Se uma Gousma atingir um nível de fúria maior que 5, ela se desintegra ; 
#### Alteração: 
Programei o jogo para que os magos (gousmas) fiquem apenas "paralisados" se, e apenas se, chegarem ao 5° ciclo de mana (5 pontos de fúria). Assim, ele pode retornar ao jogo depois, como será explicado futuramente. Caso seu ciclo de mana (nível de fúria) ultrapasse 5, ele fica apenas com o resto. Por exemplo: se um feiticeiro com o 4° ciclo de mana ataca um mago que está no 3° ciclo, o mago ficará com o 2° (4+3-5) ciclo de mana, ao invés de paralisar.

● O jogador pode optar por dividir uma Gousma, transferindo uma parte da
fúria para uma nova Gousma (respeitando o limite de duas Gousmas por
jogador);
####Alteração:
Os conjuradores de cada jogador só podem dividir entre si seus ciclos de mana quando a soma entre os dois é par. Além disso, um conjurador paralisado (que para a regra de divisão é considerado com o seu ciclo de mana em 0), pode voltar ao jogo se seu parceiro estiver em um ciclo de mana par.

● O jogador que perder todas as suas Gousmas será derrotado;

● Ao final do jogo, o jogador pode optar por reiniciar ou retornar ao menu
principal.

### Processo de Criação
Sinceramente, não lembro quando foi que surgiu a ideia de magos e feiticeiros se enfrentando no lugar das "gousmas". Talvez tenha sido por um determinado impelimento por tornar o meu trabalho o mais original possível. Há anos eu tenho esse gosto por histórias de fantasia medieval, então acho que em algum momento a história apenas surgiu na minha mente e eu a agarrei.

### Funcionamento
Aqui não tem nada de muito diferente do que foi explicado na descrição dos requisitos para a criação do jogo. O jogo vai sempre começar no turno dos feiticeiros, e cada jogador terá direito à uma ação (atacar ou dividir) até que os dois personagens de um dos jogadores esteja paralisado. Após diversos testes feitos por via de terceiros, creio que a alteração das regras resultou em uma maior variedade de jogadas e estratégias, tornando o jogo mais divertido.

## Menu Inicial
