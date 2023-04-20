# Meu Front

 ```
 O objetivo é a entrega do MVP que tem como escopo a implementação de um FrontEnd, com 3x metodos de API em uma tabela de roupas para cadastro, busca e deleção
 ```
 
```
Para executar os comandos estamos utilizando um ambiente virtual env.
```
 
 (env)$ pip install -r requirements.txt
```
Este comando instala as dependências/bibliotecas, descritas no arquivo `requirements.txt`.

Para executar a API  basta executar:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

Em modo de desenvolvimento é recomendado executar utilizando o parâmetro reload, que reiniciará o servidor
automaticamente após uma mudança no código fonte. 

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

Abra o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador para verificar o status da API em execução.