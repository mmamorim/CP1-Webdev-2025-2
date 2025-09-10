![](./fiap.png)

# Web development 2024/2

| Checkpoint        | 1      | ```CURSO:```     | ENGENHARIA DE SOFTWARE |
| ----------------- | ------ | ---------------- | ---------------------- |
| ```DISCIPLINA:``` | Webdev | ```PROFESSOR:``` | Marcelo Amorim         |


| ```TURMAS:``` | 1ESPR | 1ESPS |  
| - | - | - |


# ⏰ Missão Caça ao Tempo da Reunião 
#### Descubra a duração da reunião!

Imagine que você está em uma empresa e precisa registrar o tempo exato das reuniões para saber quanto tempo foi gasto em cada projeto. Só que, em vez de usar uma calculadora ou planilha, sua missão é criar um programa em JavaScript que faça esse cálculo automaticamente. 

O relógio está correndo ⏰... será que você consegue programar uma solução capaz de dizer exatamente quanto tempo a reunião durou?


# 📌 Exercício: Calculando a duração de uma reunião  

Você deverá criar um pequeno projeto em **JavaScript** para calcular quanto tempo durou uma reunião.  


#### Tem um exemplo de como deveria ficar meu App?

Sim. O video abaixo ilustra como seu App deve mais ou menos ficar...



## Requisitos  

1. Crie uma pasta chamada **`CP1-TempoReuniao`** contendo dois arquivos:  
   - **`index.html`** (interface para o usuário inserir os dados)  
   - **`script.js`** (onde ficará a lógica em JavaScript)  

2. No **HTML**, prepare um formulário simples para o usuário digitar:  
   - Horário de **início da reunião**  
   - Horário de **término da reunião**  

👉 Se preferir, você pode implementar a leitura desses dados utilizando o comando **`prompt()`** no JavaScript, em vez de criar um formulário em HTML.  

Caso deseje, o HTML descrito abaixo poderá ser usado como modelo:

~~~html
<h1>Webdev CP01 - Ex01</h1>
<h3>
    Calcular o tempo de duração da reunião.
</h3>
<div>
    <span><strong>Início:</strong></span>
    <span>Horas</span>
    <input style="width:30px" id="horaIni" type="text">
    <span>Minutos</span>
    <input style="width:30px" id="minIni" type="text">
</div>
<div>
</div>
    <span><strong>Término:</strong></span>
    <span>Horas</span>
    <input style="width:30px" id="horaFim" type="text">
    <span>Minutos</span>
    <input style="width:30px" id="minFim" type="text">
</div>
<div style="margin-top:10px">
    <button onclick="calcular()">Calcular duração</button>
</div>
<h2>
    Duração: 
    <span id="horas">00</span>:<span id="minutos">00</span>
</h2>
<script src="./main.js"></script>
~~~

3. No **JavaScript**:  
   - Leia os valores informados no formulário.  
   - Calcule o tempo total de duração da reunião.  
   - Exiba o resultado em **horas, minutos**.  

4. Considere também:  
   - Reuniões que ultrapassam a **meia-noite** (por exemplo: início às 22:00 e término às 01:30).  
   - **Validação das entradas**: se os horários não forem válidos, mostre uma mensagem de erro.  


### Seu projeto deve seguir os seguintes critérios:

1. O arquivo HTML deve ser nomeado como index.html e respeitar a estrutura fundamental, incluindo as tags essenciais e título contendo a palavra ```CP Webdev```.

2. O arquivo javascript deve estar na mesma pasta do projeto e ser nomeado como ```main.js```.

3. Seu programa javascript **não poderá converter** os horários em tipos como ```Date``` e **não poderá usar nenhuma biblioteca javascript de tempo**.
4. O resultado contendo o tempo de duração deve ser apresentado com ```horas : minutos``` com zero a esquerda caso as horas ou minutos sejam inferiores a 10.
   

# ENTREGA: 

1. A entrega deste arquivo deve ser realizada no TEAMs na tarefa que foi criada para sua turma / disciplina (web development).

2. Um dos integrantes do grupo deve criar um repositório no Github contendo:
    - `readme.md` com os dados de cada integrante do grupo: NÚMERO DE MATRICULA + NOME COMPLETO
    - HTML `index.js`
    - Javascript `main.js`

3. Enviar o link do github na entrega pelo TEAMs.    

