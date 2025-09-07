*Introdução*

Problema central: entregas sendo feitas fora do prazo determinado, o que gera insatisfação dos clientes e prejuízos econômicos, tanto em questão de combustível como para o mantimento da empresa.
Desafio: criar uma Inteligência Artificial para fazer com que as entregas sejam mais rápidas, econômicas e que gerem confiança ao cliente. Para que haja eficácia nesse projeto, devemos considerar, por exemplo, referente aos entregadores:
se as entregas forem feitas por camimhos mais rápidos, precisamos considerar como estará o tráfego pelas vias, acidentes que podem ocorrer, excesso de demanda na parte interna da empresa, atraso no preparo do pedido
(isso pode incluir a empresa buscar o alimento em determinado local e o mesmo estiver lotado).

Essa empresa não possui nenhum apoio tecnólogico e o proprietário deseja uma solução a qual as entregas poderão ser feitas de forma mais rápida e eficiente.
Logo, será necessário criar um algoritmo que mostre as melhores rotas e fazer um agrupamento de entregadores próximos, para os casos em que surgirem muitos pedidos a serem feitos. Isso servirá para a empresa também
se atualizar referente ao avanço tecnológico e entender como que a tecnologia pode ajudar no crescimento da empresa, gerando consequentemente o lucro e satisfação dos clientes.

Utilizei os seguintes comandos: K-Means para agrupamento de dados em clusters e o Dijkstra para traçar uma menor reta entre a empresa e o cliente.

Abaixo, segue um gráfico que mostra as coordenadas X e Y e os respectivos clientes que pertencem a elas:
<img width="475" height="1240" alt="image" src="https://github.com/user-attachments/assets/9e08ac44-467f-46b9-ae61-5331bcd4f1fc" />

No código, aparecerá grupo 0 e 1. O grupo 0 são aqueles que estão na coordenada Y e o grupo 1 na coordenada X.

Por ter sido um algoritmo simples, vejo que pode melhorar em bastante coisa, como por exemplo: a maneira que os entregadores fariam essas entregas mais rápidas (o que seria feito dentro da empresa e fora dela para que isso aconteça) e ter mais detalhes das rotas de entrega.

Este trabalho fiz com a ajuda do ChatGPT, embora tenha feito alguns comandos sozinho.
