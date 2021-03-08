# **ASP.NET Core**
Essa projeto é uma aplicação web com o padrão de arquitetura de software chamado MVC. 
As aplicações do MVC são separadas em 3 camadas: Model, View, e Controller  

* _Model_ - 
Ele é responsável pela leitura e escrita de dados, e também de suas validações.

* _View_ - 
 É a camada de interação com o usuário. Ela apenas faz a exibição dos dados, sendo ela por meio de um html ou xml.
 
 * _Controller_ - 
 É responsável por receber todas as requisições do usuário. Seus métodos chamados actions são responsáveis por uma página, controlando qual model usar e qual view será mostrado ao usuário. 

# Projeto
Esta aplicação exibirá uma tabela de filmes, e permite ao usuário que ele _insira_ novos filmes na tabela, ou também poderá _editar_, _excluir_, e _pesquisar_, itens.
