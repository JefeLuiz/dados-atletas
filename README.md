# dados-atletas
Criar uma aplicação capaz de receber informações de um atleta, bem como calcular parâmetros e exibi-los para o usuário.

No primeiro momento foi definido o método para classificar em qual categoria o atleta se encaixa:

Infantil: 9 a 11 anos
Juvenil: 12 e 13 anos
Intermediário: 14 e 15 anos
Adulto: 16 a 30 anos
Sem categoria: demais idades

Na segunda etapa foi implementado o calculo para encontrar o IMC do atleta conforme formula a seguir:

ICM = Peso / Altura²

Para calcular a média do atleta, foi desconsiderado a nota mais alta e mais baixa obtida, que 
somadas e dividas pela quantidade de notas remanescentes resultou na media válida.

E por fim foi definidos métodos para obter os resultados obtidos seguindo a seguinte formatação em exemplo:


Nome: Cesar Abascal 
Idade: 30 
Peso: 80 
Altura: 1.7 
Notas: 10,9.34,8.42,10,7.88 
Categoria: Adulto 
IMC: 27.68 
Média válida: 9.25
