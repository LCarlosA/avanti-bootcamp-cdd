# <Império dos Dados>

<h4><b>Diamonds</b> é um dataset que apresenta informações de atributos de mais de 54 mil diamantes, sendo elas características importantes na hora da compra ou da venda de diamantes importados. Preço, tamanho e quilates são informações cruciais para o mercado de diamante, por isso faremos um estudo desses dados para que possamos encontrar informações relevantes aos nossos clientes que desejam comprar o melhor diamante nesse luxuoso mercado que movimenta milhões de reais por ano.</h4>.

## Desenvolvedores
 - [Lucas Carlos #1](https://github.com/LCarlosA/-#1)

---

## Objetivos:
Temos como objetivo nesse projeto entender quais os principais fatores que valorizam o preço do diamante, para podermos entregar um modelo com maior lucro máximo.

## Sobre o projeto:
Esse foi o meu primeiro projeto oficial de estudo de análise de dados, realizado com auxílio de mentores. Então ele teve bastantes elementos de aprendizagem e pesquisa.

### Dificuldades:
<ul>
 <li>Organização visual e seus elementos</li>
</ul>

### Solução:
<ul>
 <li>Pesquisa sobre desenvolvimento de visualização, como a leitura do livro <b>Storytelling com dados</b></li>
</ul>
### Aprendizado:
<ul>
    <li> Storytelling com Dados</li>
    <li> Funções vitais do matplotlib</li>
</ul>

### Ferramentas:
<ul>
 <li>Pandas</li>
 <li> Matplotlib</li>
 <li>Seaborn</li>
</ul>

## Organização de diretórios


```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```
