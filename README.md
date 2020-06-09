# HealthTrack

 Projeto
 
1.1 Tema do projeto
Health Track - Sistema para Triagem e Monitoramento de Pessoas com Covid

1.2 Case
No atual momento em que vivemos (que se mostra muito diferente) devemos ter
consciência do papel que podemos exercer na sociedade. Mesmo sendo
profissionais da área de tecnologia de informação podemos auxiliar no
atendimento de pacientes criando ferramentas que permitam tornar mais rápido
e eficiente possível, o encaminhamento dos pacientes aos locais de atendimento
médico e também oferecer informação sobre o paciente por parte dos familiares.
Quando um paciente procura uma unidade de atendimento com alguns sintomas
que o aflige esses devem ser analisados por um médico para determinar se este
deve ou não ser internado.
Caso esse paciente tenha que ser internado deve-se decidir o melhor local para
ele. Porém, essa atribuição deve também considerar implicações no sistema de
saúde oferecido pela cidade. Uma melhor distribuição dos pacientes pode levar
a uma logística de distribuição de insumos como EPI e equipamentos como
tomógrafos, respiradores, etc.
Neste momento, onde a ocupação de leitos em algumas unidades de internação
na cidade de São Paulo está acima de 80%, tem sido comum o deslocamento
de pacientes entre as unidades. As razões para isso diferem muito:
Alteração do estado do paciente (há unidades que deve apenas internar
pacientes de baixa complexidade e outra pacientes em estado mais grave)
• Maior disponibilidade de profissionais e equipamentos mais adequados
para o atendimento.
• Menor ocupação dos leitos, por ser região onde não há uma
contaminação em massa.
Como, no caso de covid-19, não há possibilidade de visitas aos internados, os
familiares sentem muito a necessidade de obter informações sobre o estado do
paciente e até mesmo em que local ele está internado.

1.3 Descrição
Desafio: Propor e elaborar um programa que dentro de um hospital cadastre
vagas para internação e depois, usando um menu de opções, realize as
seguintes operações:

1. Recepção de paciente: cadastra o registro do paciente, seu nome e seu
CPF e coloque inicie o status do paciente para “filaAtendimento” e insira na fila
para atendimento. O registro do paciente deve também ser inserido na lista de
pacientes que procuraram o hospital.

2. Atendimento de paciente: retira 1 paciente que estava aguardando na fila
de atendimento. Este paciente deve responder algumas perguntas sobre seus
sintomas (pesquise quais são no caso do covid-19 e faça com que o programa
faça essas perguntas). Usando as respostas, o programa deve decidir se este
paciente deve ser ou não internado, se não precisar de internação, avise que o
paciente foi liberado e altere o status do paciente para “liberado” na lista de
pacientes.
Se o paciente deve ser internado é preciso verificar se há vaga. Se não houver
vaga, o paciente entra em outra fila onde deve aguardar a vaga da internação
(fila para internação) e também altere o status do paciente para
“filaInternação” na lista de pacientes.
Caso haja vaga para a internação, o status do paciente deve ser alterado para
“internado” na lista de pacientes.

3. Liberação de vaga na unidade: o paciente que terá alta é identificado por
seu CPF (altere o status do paciente para “em alta” ou “óbito” na lista de
pacientes), então depois que o paciente é retirado internados e 1 vaga é aberta.
Com a vaga liberada é retirado um paciente que estava na fila para internação,
caso haja algum paciente aguardando nessa fila.

4. Consulta registro do paciente identificado pelo CPF na lista de pacientes
que procuraram o hospital apresentando as informações contidas nesse registro
(nome e status).
