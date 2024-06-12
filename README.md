![ ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/bcfc56a4-b124-4988-88b4-e860cb438f27)

<h1 align="center"> Genome Identifier - Projeto PCD </h1>

### Projeto Práticas em Ciências de Dados, Turma 2024
### Colaboradores: Enzo Januzzi, Gabriel  Viégas e Glauber Nascimento.  
 <h4 align="center"> 
    ☑️  Projeto em concluído ☑️
</h4>

## 💡 Descrição
### Identificador de aminoácidos de uma sequência de nucleotídeos de DNA ou RNA e plotagem de gráficos quantitativos e qualitativos.

## 🔨 Funcionalidades do projeto
### `Genome_identifier` - Recebe uma sequência de nucleotídeos, se possui Timina e se é uma fitta negativa de RNA. Retorna os aminoácidos correspondentes e gráficos.

### `Trancrição`: Caso o códon possua Timina, identifique-o e ele será transcrito para Uracila.

### `Contagem de aminoácidos em uma sequência de nucleotídeos`: Através de uma lista com os nucleotídeos escolhidos, o código conta, respeitando os codons de iníciação e de parada, os aminoácidos presentes nessa lista.<br> 

### `Plotagem de gráficos quantitativos`: Um gráfico em barras é plotado, com os dados obtidos na contagem de aminoácidos, comparando a quantidade de todos aminoácido presentes.

### `Plotagem de gráficos quantitativos`: Um gráfico de pizza é plotado para mostrar a quantidade de aminoácidos com a mesma característica.

## 🪛 Funcionalidades embutidas

### `tratamento_str` - Recebe como argumento uma string. Retorna sem números, espaços e os caracteres maiúsculos
### `neg_transcription` - Recebe com argumento uma fita de rna negativa. Retona uma positiva
### `onde_esta_aug` - Recebe como argumento uma sequência de nucleotídeos e se DNA = True, ele troca as Timinas por Uracilas. Retorna a sequência de RNA a partir do códon de início `AUG`.
### `id_aminoacidos` - Recebe uma sequência d ecódons como argumento. Retorna uma sequência de aminoácidos.
### `ocorencias_aminoacidos` - Recebe uma sequência de aminoácidos. Retorna uma biblioteca com a quantidade de vezes que um aminoácidos apareceu.
### `grafico_ocorrencias` - Recebe o dicionário com as ocorrências de cada aminoácido. Retorna um gráfico interativo com os dados.

## 📁 Acesso ao projeto

### você pode acessar o código pelo github ou, preferencialmente, baixa-lo.

## 🛠️ Abrir e rodar o projeto

### Depois de baixar o projeto você deve abri-lo no Jupyter Notebook

## ✔️ Linguagens e programas usados

#### `Python`, `Jupyter Notebook`, `Plotly`, `Matplotlib`, `Datetime`
##

##  :octocat:  Autores

| [<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/7739b48f-cff8-4278-ae19-a38aa4f451df" width=115><br> <sub>Gabriel Viégas </sub>](https://github.com/gabviegas)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/9830206667772540)<br> [<sub>Linkedin</sub>]()|  [<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/ecbf1a63-69ba-450a-bb1d-770450b17189" width=115><br><sub>Glauber Nascimento de Oliveira</sub>](https://github.com/Glaubernaoli)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/0913262665776521)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/glauber-naoli/) |  [<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/3a46fdd6-2a61-4d80-92ec-efa18f758f50" width=115><br><sub>Enzo Januzzi</sub>](https://github.com/EnzoJanuzzi)<br> [<sub>Currículo Lattes</sub>]()<br> [<sub>Linkedin</sub>]() |
| :---: | :---: | :---: |
 #### `Contribuições` - Todos os autores construíram o código juntos, quando não coletivamente, atuavamos na revisão do código, e os gráficos também.
 ##### `Glauber Nascimento`escreveu esse documento, revisado por `Gabriel Viégas` e `Enzo Januzzi`

![ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/6c9216ea-0cdb-4dac-aac5-445d505b2804)





