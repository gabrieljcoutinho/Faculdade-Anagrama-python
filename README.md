# Contador de Frequência de Caracteres

Este script em Python tem como objetivo analisar uma string e contabilizar a ocorrência de cada caractere, retornando um dicionário com os resultados.

---

## 🛠️ Funcionamento do Algoritmo

O código utiliza uma estrutura de dados do tipo **Dicionário** (chave-valor) para mapear a frequência dos caracteres:

* **Inicialização**: Um dicionário vazio é criado para armazenar os dados.
* **Iteração**: O laço `for` percorre cada caractere da string fornecida.
* **Verificação Condicional**: 
    * Se o caractere ainda não existe no dicionário, ele é adicionado com o valor inicial de 1.
    * Se o caractere já existe, seu valor é incrementado em +1.
* **Retorno**: A função devolve o objeto final contendo a contagem completa.

---

## 📂 Exemplo de Saída

Ao executar o script com a entrada `"fiapp"`, o retorno exibido no console será:

```python
{'f': 1, 'i': 1, 'a': 1, 'p': 2}
