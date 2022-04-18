EN-US
When a user accesses a malicious link containing this payload, a recursive javascript function is executed, which performs bulk requests causing an overload of memory entries, causing the browser to stop working and totally polluting the browsing history.
This script contains a repetition counter generating a recursive redirection counter generating massive buffer overflow entries executed.

PT-BR:
Quando um usuário comum acessa um link malicioso contendo esse payload, é executado uma função recursiva em javascript, que realiza requisições em massa causando uma sobrecarga de entradas de memoria, fazendo com que o navegador pare de funcionar e poluindo totalmente o historico de navegação.
Esse script contem um laço de repetição efetuando um contador de redirecionamento recursivo gerando entradas massivas de execução causando buffer overflow.


Proof Of Concept:<br>
![alt text](https://i.imgur.com/PQbMJqL.png)
![alt text](https://i.imgur.com/BZXBx7T.png)
