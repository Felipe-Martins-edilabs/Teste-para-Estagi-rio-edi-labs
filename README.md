# Teste-Estagio-RestAPI_EdiLabs
Resolução do teste de REST API para a vaga de Estágio.

## Instruções para a realização do teste
* Privar o seu repositório ao iniciar o desenvolvimento.
* Consumir uma API REST do **restcountries** e com sua resposta realizar uma conversão para um arquivo.txt contendo os nomes das capitais e seus respectivos idiomas em cada linha do arquivo.
* Se sinta livre para utilizar a linguagem que você tiver mais afinidade.

**Endpoint que deverá ser utilizado:** https://restcountries.com/v3.1/independent?status=true&fields=languages,capital

#### **Exemplo do arquivo.txt** 

```
Encoding: utf-8, Data: 23/03/2023

+ Capital n°0, Nome: Guatemala City, Idiomas: {'spa': 'Spanish'}
- Capital n°1, Nome: Singapore, Idiomas: {'zho': 'Chinese', 'eng': 'English', 'msa': 'Malay', 'tam': 'Tamil'}
+ Capital n°2, Nome: Sarajevo, Idiomas: {'bos': 'Bosnian', 'hrv': 'Croatian', 'srp': 'Serbian'}
- Capital n°3, Nome: Malé, Idiomas: {'div': 'Maldivian'}
+ Capital n°4, Nome: Riga, Idiomas: {'lav': 'Latvian'}
- Capital n°5, Nome: Athens, Idiomas: {'ell': 'Greek'}
+ Capital n°6, Nome: Amman, Idiomas: {'ara': 'Arabic'}
- Capital n°7, Nome: Dhaka, Idiomas: {'ben': 'Bengali'}
+ Capital n°8, Nome: Rome, Idiomas: {'ita': 'Italian'}
- Capital n°9, Nome: Algiers, Idiomas: {'ara': 'Arabic'}
```
* Antes da manipulação dos dados, o arquivo deve conter o seu encoding e a data de execução no formato: **dd/mm/yyyy** na primeira linha do arquivo.
* Cada linha deve conter o número da iteração, o nome da capital e seus respectivos idiomas.
* Em cada início de linha você deverá indicar se o índice da capital/iteração é par ou impar, com '+' ou '-'.