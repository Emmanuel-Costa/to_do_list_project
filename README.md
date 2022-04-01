# to_do_list_project
Projeto To do list, aplicativo criado como teste final do bootcamp Santander em parceria com a Digital Innovation One (DIO). O objetivo era criar um app 
de lista de tarefas usando Kotlin, utilizando as melhores ferramentas e bibliotecas mais atuais como o Android Jetpack e seguindo o Material Design. Mais abaixo explico melhor o app 
e quais recursos utilizei. 😃  
<br />

# Destrinchando o projeto
### Primeira tela vazia
Logo de início utilizei o view binding para facilitar a manutenção das minhas views de um jeito mais seguro e conciso, a primeira tela logo abaixo possui um 
floating action button que é o indicado pelo material design pela facilidade de acesso do botão para o usuário. O plano de fundo exibe a imagem quando a lista 
está vazia. Assim que forem criadas as tarefas o aplicativo faz uso de uma Recycler View para exibi-las em forma de lista.    
<br />
<img src="https://user-images.githubusercontent.com/82117565/161181476-3b72e744-1ee4-4591-be14-7a15d06ef9c8.jpg" width="350" hspace="100">
<br />
### Segunda tela
Clicando no fab(floating action button) nós vamos para a segunda tela, que é a de criação de tarefas. Nesta tela nós temos os campos de título e descrição e 
também temos um Material Date Picker para escolher a data da tarefa e um Material Time Picker para escolher o horário da tarefa.  

<img src="https://user-images.githubusercontent.com/82117565/161181482-ab0b97d3-5ca4-43f3-9d9d-06a37f2b8f54.jpg" width="350" hspace="100" align="left">
<img src="https://user-images.githubusercontent.com/82117565/161181484-ca0f8aca-4e14-41e7-9b20-da1a4df69978.jpg" width="350">

### Primeira tela com tarefa
Por fim temos a recycler view já com algumas tarefas. Adicionei um botão em cada tarefa que quando clicado leva de novo a segunda tela, porém com o intuito de 
editar a tarefa já existente e não de criar outra. E por último temos o botão com ícone de lixeira para excluir todas as tarefas. Lembrando também que para excluir 
as tarefas individualmente deve-se apertar no botão de editar e aí sim clicar na lixeira para excluí-la.   

<img src="https://user-images.githubusercontent.com/82117565/161181485-6f6b96f3-7843-4e14-96a9-4cc928c0084c.jpg" width="350" hspace="100" align="left">
<img src="https://user-images.githubusercontent.com/82117565/161181486-1dd5b453-2eda-4970-9601-f99ed0f261d7.jpg" width="350">

### Obs
Tomei a liberdade de adicionar a persistência de dados com Room, para tentar melhorar o app o máximo possível. Esse é um aplicativo que tenho um certo carinho
já que este foi meu primeiro bootcamp e o primeiro aplicativo "um pouco mais completo" que fiz.

# Info
Conheça mais dessa plataforma incrível que é a [Digital Innovation One (DIO)](https://www.dio.me/)!  🚀

E me mandem um convite no LinkedIn, vamos fazer novas conexões: [Emmanuel Costa - LinkedIn](https://www.linkedin.com/in/emmanuel-costa-93480a171/) 😃



