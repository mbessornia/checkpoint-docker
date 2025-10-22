# checkpoint-docker
<h1>Parte 1</h1>
<p>1.1 Listando imagens locais:</p>
<img width="560" height="189" alt="image" src="https://github.com/user-attachments/assets/ef38be80-3f08-4a0e-aa58-c12cc46cbdfa" /><br/>

<p>1.1. Baixando a imagem do python:</p>
<img width="674" height="283" alt="image" src="https://github.com/user-attachments/assets/75f74901-0caf-41b7-a942-682f31432ec6" /><br/>

<p>1.1. Inspecionando a imagem:</p>
<img width="669" height="679" alt="image" src="https://github.com/user-attachments/assets/e4067b2f-28de-4487-b4cd-85bf10277886" /><br/>

<p>1.1. Verificando histórico de camadas:</p>
<img width="676" height="522" alt="image" src="https://github.com/user-attachments/assets/f6607101-6c8f-445c-9183-6a3eef022cb9" /><br/>

<hr>

<p>1.2. Baixando diferentes versões do Node.js:</p><br/>
<img width="666" height="416" alt="image" src="https://github.com/user-attachments/assets/b9a4bf3d-fe8f-4d44-99cd-7599c824f2bf" />

<p>1.2. Nomeando tag personalizada:</p>
<img width="611" height="181" alt="image" src="https://github.com/user-attachments/assets/34802407-ffaf-457c-a64c-f79a33354109" /><br/>

<p>1.2. Removendo dangling containers:</p>
<img width="574" height="186" alt="image" src="https://github.com/user-attachments/assets/3bfb985a-07ce-4505-8588-984b2fbdfa41" /><br/>

<hr>

<p>1.3. Baixando três imagens oficiais:</p>
<img width="659" height="329" alt="image" src="https://github.com/user-attachments/assets/3d948586-e784-49d3-bc60-096d993f63a0" />
<img width="662" height="384" alt="image" src="https://github.com/user-attachments/assets/fc1ea3ee-9a26-4010-8d6c-1d65160f3261" />
<img width="664" height="296" alt="image" src="https://github.com/user-attachments/assets/8c108fe5-b544-46d6-8f7a-fad98d63aebe" /><br/>

<p>1.3. Checando o tamanho das imagens:</p>
<img width="606" height="275" alt="image" src="https://github.com/user-attachments/assets/1e1f89d2-c0bb-4ec0-9f83-744c2c8db6e3" />
<p>Nginx: 79.7MB</p>
<p>redis: 100MB</p>
<p>postgres: 390MB</p><br/>

<p>Respostas análise parte 1.3: </p>
[analise-imagens.txt]

<hr>

<h1>Parte 2</h1>
<p>2.1 Criando o projeto e o dockerfile:</p>
<img width="633" height="318" alt="image" src="https://github.com/user-attachments/assets/bc79e1df-bc73-4b95-91b4-0deda98e1ac2" /><br/>
<img width="385" height="257" alt="image" src="https://github.com/user-attachments/assets/0082fa94-68bc-45d1-987e-b3264a0fd494" />

<p>2.3. Build e Execução:</p>
<img width="678" height="581" alt="image" src="https://github.com/user-attachments/assets/f4708eb0-c150-4da8-a3bb-81edf9000a22" /><br/>

<p>Testando execução:</p>
<img width="588" height="149" alt="image" src="https://github.com/user-attachments/assets/7f6b4b61-4e78-4121-a3f3-8153e00ed0d9" /><br/>

<p>2.3. Verificando logs:</p>
<img width="677" height="300" alt="image" src="https://github.com/user-attachments/assets/1410ec1e-d6f2-4898-996a-7eba57585984" /><br/>

<p>2.4. Otimizando o Dockerfile:</p>

<p>Parando e removendo o container atual:</p>
<img width="382" height="200" alt="image" src="https://github.com/user-attachments/assets/63eba733-7856-48b6-9aa2-2675fcb74fad" /><br/>

<p>Buildando as otmizações:</p>
<img width="670" height="598" alt="image" src="https://github.com/user-attachments/assets/fff4f5da-00e5-49a8-99d0-b9408278c680" /><br/>

<hr>

<h1>Parte 3</h1>
<p>Gerenciando volumes</p>

<p>3.1. Criando volumes: </p>
<img width="523" height="177" alt="image" src="https://github.com/user-attachments/assets/5ff7f969-9aa4-45ad-8aa9-7198b839c88f" /><br>

<p>3.1. Listando e Inspecionando volume: </p>
<img width="406" height="154" alt="image" src="https://github.com/user-attachments/assets/3b56fae1-e44b-4241-86fc-9bb12ccb833f" />
<img width="649" height="370" alt="image" src="https://github.com/user-attachments/assets/8b0f50f2-4669-4d9b-bfbe-ec4d677b3777" /><br/>

<p>3.1. Executando PostgresSQL com volume: </p>
<img width="650" height="200" alt="image" src="https://github.com/user-attachments/assets/b8e8e1b2-d08e-40ce-8b2e-d1bab45af1c1" />

<p>3.2. Tabela ALUNOS criada no db fiap_db: </p>
<img width="647" height="283" alt="image" src="https://github.com/user-attachments/assets/e1d7491c-f0d4-488d-b8cc-05345af9244c" /><br/>

<hr>

<p>3.2. Testando Persistência</p>
<p>Parando e removendo o container:</p>
<img width="460" height="156" alt="image" src="https://github.com/user-attachments/assets/8f9ca301-9e0a-4459-abbf-9f13c798bb26" /><br/>

<p>Criando um novo container:</p>
<img width="676" height="162" alt="image" src="https://github.com/user-attachments/assets/e6f42592-25a2-40ea-b432-ba2c5fbf5b8d" /><br/>

<p>Verificando se os dados persistiram:</p>
<img width="679" height="277" alt="image" src="https://github.com/user-attachments/assets/7bd416d9-47c5-4934-9d27-b5c41c9e1b98" /><br/>

<hr>

<p>3.2. Bind Mounts</p>

<p>Criando projeto web: </p>
<img width="609" height="294" alt="image" src="https://github.com/user-attachments/assets/252b9f14-2624-432a-9a81-3b879e90fe1a" />
<img width="596" height="523" alt="image" src="https://github.com/user-attachments/assets/fd8a3938-c30b-49b2-bab4-3a92439ec321" /><br/>

<p>Executando Nginx com Bind Mount:</p>
<img width="670" height="110" alt="image" src="https://github.com/user-attachments/assets/cf59a5dc-8fe1-4f70-93ed-dcfe742dc4bd" /><br/>

<p>Testando localhosto:8080</p>
<img width="512" height="232" alt="image" src="https://github.com/user-attachments/assets/4a58971f-37f7-4b1f-b68d-c5bc44739847" /><br/>

<p>Alterando o localhost:8080 e checando alterações em tempo real: </p>
<img width="652" height="191" alt="image" src="https://github.com/user-attachments/assets/b0dd2b0e-c06a-437f-a0cb-c945298c705a" />
<img width="631" height="291" alt="image" src="https://github.com/user-attachments/assets/17d2a7dd-ce52-42be-941a-f5b587e80997" /><br/>

<hr>

<h1>Parte 4</h1>

<p>4.1. Criando novo direório: </p>
<img width="620" height="279" alt="image" src="https://github.com/user-attachments/assets/af3972cd-29f0-43ec-bdd0-c63f02eaa4c2" /><br/>

<p>4.1. Criando arquivo app.py:</p>
<img width="613" height="291" alt="image" src="https://github.com/user-attachments/assets/c7b6cedc-7d52-44f1-83be-26a308b29563" /><br/>

<p>4.1. Criando requirements.txt: </p>
<img width="709" height="199" alt="image" src="https://github.com/user-attachments/assets/fa49b966-8368-4638-b0c3-b3e63daa9479" /><br/>

<hr>

<p>4.2. Criando dockerfile com ENV e ARG:</p>
<img width="989" height="438" alt="image" src="https://github.com/user-attachments/assets/72e19084-0c4c-4352-abd6-b5706ab0dd77" /><br/>

<p>4.2. Executando build com argumentos:</p>
<img width="673" height="535" alt="image" src="https://github.com/user-attachments/assets/d7478ea3-1b08-40bc-aa86-9cc54568b455" />

<br/>

<hr>

<p>4.3. Executando com variáveis inline:</p>
<img width="658" height="83" alt="image" src="https://github.com/user-attachments/assets/b789961d-f4f3-431f-ab2d-0e05ed9c2391" /><br/>

<p>4.3. Testando localhost 5000</p>
<img width="506" height="210" alt="image" src="https://github.com/user-attachments/assets/92e3498c-30b8-48c6-99ba-a4e9f500407a" />

<p>4.3. Criando .env</p>
<img width="984" height="246" alt="image" src="https://github.com/user-attachments/assets/c5e8bc2c-3f9d-451a-853b-109c2ed5e8f1" />

<p>4.3. Executando .env na porta 5001</p>
<img width="676" height="138" alt="image" src="https://github.com/user-attachments/assets/859a66ed-0d91-474a-965d-ca4716dd5298" />

<p>4.3. Testando variáveis em prod</p>
<img width="675" height="379" alt="image" src="https://github.com/user-attachments/assets/7202897f-ac69-4846-b66b-4b6fb13e10d7" />

































 










  

