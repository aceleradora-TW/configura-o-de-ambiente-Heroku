
# Tutorial de configuração de ambiente Heroku    
## Deploy, testes e QA   

1º Passo    
- Criar um usuário no <a href="https://www.heroku.com/" target=_blank>HEROKU</a>

2º Passo  
- Login
<img width="535" src="https://user-images.githubusercontent.com/80184523/137900936-1d27560c-d254-4a9f-9da7-755961b9f074.png"/>

3º Passo
- Clicar em **New**   
  - Selecione **Creat new app**   
  
<img width="700px" src="https://user-images.githubusercontent.com/81186935/136805150-a5e971ae-f75f-4e48-a005-84c3f3104c92.png"/>
  

4º Passo   
- No campo nome acrescentar **seu-nome-acelera-mais-teste**   
  - ex: Jorel-acelera-mais-teste     (Repositório Front-End)   
  - ex: Jorel-acelera-mais-api-teste (Repositório Back-End)   

<img width="700px" src="https://user-images.githubusercontent.com/80184523/138100211-18440d95-7bcc-4525-90bf-5e44167e0711.png"/>


5º Passo
-  Conectar ao GithHub
-  Selecionar **aceleradora-TW** 
-  Selecionar o repositório de acordo com o que esta sendo criado:
  - Selecione **acelera-mais** para Front-End
  - Selecione **acelera-mais-api** para Back-End

<img width="700px" src="https://user-images.githubusercontent.com/81186935/136807493-f93bd69b-f9c3-438c-8ec2-347b751cef1e.png"/>


6º Passo    
- Clique em conect de acordo com o repositorio escolhido

<img width="700px" src="https://user-images.githubusercontent.com/81186935/136809495-3012b043-326a-4be2-81b6-769e51a1f1da.png"/>
  
7º Passo    
- Clique em **Disable Automatic Deploys** (Isso vai desabilitar o deploy automático)

<img width="700px" src="https://user-images.githubusercontent.com/80184523/138096807-77087a84-1d16-4174-be01-af62fc596ce2.png"/>


8º Passo  
- Escolher a branch que será testada   
- Clicar em Deploy Branch 
  
<img width="700px" src="https://user-images.githubusercontent.com/80184523/138097796-2719b212-c4ec-44b8-8f48-dd141f3b84b6.png"/>


9º Passo   
- Aguardar a finalização do deploy   
- Clicar em **View** se for uma aplicação front-end  

<img width="700px" src="https://user-images.githubusercontent.com/80184523/138098908-9d74af87-d784-44b3-bfb8-fe8c779575f2.png"/>


# Videos demostrativos   

1º Passo  

- Criar um usuário no <a href="https://www.heroku.com/" target="_blank" rel="noopener" >HEROKU</a>

2º Passo   
- Clique na imagem abaixo e você será direcionado para um video onde temos o passo a passo da criação de um ambiente de teste no HEROKU.

<a href="https://youtu.be/RNQ5XsGADdg>" target="_blank"><img width="535px" src="https://user-images.githubusercontent.com/81186935/137147067-f0995af1-9d2b-4f05-8409-81f6552ad96c.png" target="_blank"></a>

# Fazendo deploy de uma branch

1º Passo 
  
<a href="https://youtu.be/DMPJNe8PqnU>" target="_blank"><img width="535px" src="https://user-images.githubusercontent.com/81186935/137147199-e55afe6c-b2b3-444f-995a-dc2c303c8233.png" target="_blank"></a>

## Pronto, agora você tem um ambiente próprio para testar suas branchs e também fazer QA

=========================================//==============================================

# Adicionando variável de ambiente para testar features do backend
### 
1º Passo

- Selecionar o ambiente de teste da api

<img width="700px" src="https://user-images.githubusercontent.com/81186935/138734885-2b12cddb-25b0-48a8-a485-43490b115d1f.png"/>

2º Passo

- Clicar em **Resources**

<img width="700px" src="https://user-images.githubusercontent.com/81186935/138735407-a6c4a8e2-3f06-4a4c-bbee-e5d7d3bda7a1.png"/>

3º Passo

- Digitar postgres na busca dos **Add-ons**
- Selecionar o item **Heroku Postgres**

<img width="700px" src="https://user-images.githubusercontent.com/81186935/138735348-ed76926e-c26d-4b45-957d-0e6991474eed.png"/>

4º Passo

- Clicar no botão roxo **Submit order form**

<img width="700px" src="https://user-images.githubusercontent.com/81186935/138735604-ac7d778d-1139-4e2c-b7f9-e52edc2717de.png"/>

5º Passo

- Clicar em **Settings**

<img width="700px" src="https://user-images.githubusercontent.com/81186935/138736013-51d72cbd-5a7b-4187-ab4e-4200203728c0.png"/>

6º Passo

- Clicar em **Reveal Config Vars**

<img width="700px" src="https://user-images.githubusercontent.com/81186935/138736070-8bbf49e9-7953-48c2-8c06-1952421431c0.png"/>

7º Passo

- Adicionar uma **Key** chamada **NODE_ENV**
- Adicionar o **value** chamado **test**
- Clicar em **add** para adicionar.

<img width="700px" src="https://user-images.githubusercontent.com/81186935/138736127-916beb21-3bb8-4a30-bbc9-c6f93df41b4b.png"/>



