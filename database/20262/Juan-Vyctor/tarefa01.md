# Q1. Descreva o que é um Banco de Dados e o que é um Sistema Gerenciador de Banco de Dados. Cite exemplos de Bancos de Dados e seus SGBDs.

Um banco de dados é uma forma de armazenar dados diferentes do gerenciador de arquivos. Ele não se baseia em hierarquia como o explorador e tem diversas funções a mais, como possibilidade de haver backups; ser capaz de fazer buscas por um dado específico dentro de sua base, assim como alterações, inserções e remoções em qualquer lugar; todos os dados se enxergam ao mesmo tempo, interagindo e conversando entre si; é capaz de facilmente lidar com de redundâncias e dados faltantes; por possibilitar dar permissões ao usuários, quem pode acessar que parte do banco, ele é extremamente seguro e confiável.

Seguindo essa linda, um Sistema Gerenciador de Banco de Dados é um software auxiliar que facilita o uso de um BD. Assim como o Explorador de Arquivos do Windows nos permite ver como estão organizados nossos arquivos dentro da máquina, os SGBDs conseguem interpretar o banco de dados e nos dar uma interface mais enxuta para nosso uso. Por meio deles podemos rapidamente fazer comandos e interpretar dados que estão guardados ali dentro. Alguns exemplos de Bancos de Dados e seus respectivos SGBDs são o MySQL, com o Workbench e o PostgreSQL, e o NoSQL, com o MongoDB e o Redis.

---

# Q2. Quais os principais problemas de utilizar Sistemas de Arquivos para armazenagem de dados?

Em grande escala, o fato da organização ser hierarquica pode tornar o processo de busca extremamente demorado e complicado de se fazer, já que a busca deve ser feita em cada diretório individualmente, e então retornar para entrar no próximo. Ademais, arquivos em diretórios diferentes não "se enxergam", e não podem interagir diretamente uns com os outros a não ser que uma declaração física seja feita, o problema disso é que caso o arquivo no destino mude de lugar, nada será encontrado e uma falha será gerada. Um outro grande fator é a alta taxa de redundância gerada, as vezes um dado é gerado numa pasta e usado ali, então é gerado novamente num outro lugar, e uma terceira vez num lugar distinto, sendo difícil de encontrar onde as repetições acontecem. Além disso, existe o problema de backup, ou no caso, a falta dele. Num sistema de arquivos não há backups automáticos e os mesmos são feitos pelos usuários, se algum erro ou falha acontecer, não há como recuperar de forma automática como nos Banco de Dados.

---
