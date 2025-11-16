# Performance dos Alunos

Uma universidade veio em busca de uma analise e direcionamento sobre as notas de seus alunos porque isso estava atrapalhando a nota da faculdade, eles fizeram uma pesquisa com os alunos com o seguinte questionário: 
</br></br>
🔹Horas Estudadas - (Hours Studied) </br> 
🔹Horas Dormidas - (Sleep hours) </br>
🔹Frequência nas Aulas - (Attendance percent) </br>
</br>
Com isso a faculdade realizou a pesquisa com 200 alunos que estão com as notas abaixo da média solicitada. O motivo disso foi para que eles possam subir a nota no inep e buscar novos clientes.
</br>
🔹A média atual das notas da universidade e de **33%** e a universidade que aumentar pelo menos em **50%**.
</br> 
<hr>

## Análise Exploratória dos Dados

Foi realizado uma análise exploratória dos dados citados acima, tentando encontrar padrões e verificando se a algum outliers.


*Horas Estudadas - Hours Studied*

Na análise exploratória não houve outliers, e vimos que a concentração dos alunos está entre 3 a 5 horas estudadas. </br>
A média estudada e de 6 horas por semana com os dados apontados abaixo. </br>

<img width="1300" height="482" alt="image" src="https://github.com/user-attachments/assets/86d122ea-4693-4e80-b7e4-9fc98f26349f" />

</br>
</br>

*Horas Dormidas - Sleep Hours*

Na análise exploratória das horas dormidas ou descansada, mostra que quase 50% dos alunos estão dormindo até 6 horas por dia, conforme a análise abaixo. </br>
A média aponta que estão dormindo de fato por volta de 6 horas, por dia. </br>

<img width="1556" height="469" alt="image" src="https://github.com/user-attachments/assets/19ff6a78-f3ac-41b2-ad34-0136aa137abb" />

</br>
</br>

*Frequência nas aulas - Attendence percent*

Na frequência dos alunos mostra que a maioria está com frequência boa de 93% isso mostra que eles estão indo bem nas aulas. </br>
A média da frequência e de 75% dos alunos em geral. </br>

<img width="1399" height="472" alt="image" src="https://github.com/user-attachments/assets/37635138-fbeb-4d69-b1c4-63ee13499e64" />

<hr>

## Análise de Correlação

Realizei uma analise de correlação para verificar quais dos 3 itens estava mais afetando a nota dos alunos, e com isso montar um plano de ação para resolver o caso. </br>
Com isso a base foi montada referênciando a prova final com os devidos campos informados anteriormente. </br>

Com isso foi identificado que a correlação mais forte entre os 3 e as notas estudadas, conforme o grafico de disperção mostrados abaixo:

<img width="1873" height="433" alt="image" src="https://github.com/user-attachments/assets/dd3ba96f-95b5-459d-bbe1-f8e8e1aaef73" />

Com os dados acima eu preferi usar a regressão linear para montar o plano de ação de transformar a média que é de **33%** em **50%**. <br>

<hr>

## Regressão linear - Hora Estudada x Nota Prova final

Utilizando a regressão linear foi identificado que a nota do aluno aumenta 1,63 por hora semanal estudada com isso, realizando o cálculo abaixo.

 <img width="982" height="519" alt="image" src="https://github.com/user-attachments/assets/46ff14ff-2010-4bb1-b421-46b614fb91ad" />

</br>
</br>

**Cálculo**

Meta: 50 </br>
Média atual: 33,93 </br>
Diferença: 50 - 33,93 = 16,07 </br>

Conforme a análise, a cada 1 hora de estudo sua nota aumenta 1,63411 pontos. </br>
Horas adicionais = Pontos necessários / Pontos por hora </br>
Horas adicionais = 16,07 / 1,63411 = 9,83 horas
</br>

Isso mostra que os alunos precisa estudar aproximadamente 9 horas e 50 min no por semana.


<hr>

## Plano de ação

🔹Conforme informado no Business case, e preciso orientar os alunos e professores sobre a importância dos estudos, e reforçar que eles precisam se dedicar mais nas hora de estudo semanal. </br>
🔹Com isso iremos realizar outra prova e ver como eles se comportaram com o novo método de ensino e com as nova horas adicionadas no horário de estudo.









 



