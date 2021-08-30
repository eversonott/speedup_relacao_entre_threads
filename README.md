# SpeedUp - Relação entre Threads
Atividade 02 - Sistemas Distríbuidos

## Sobre o projeto

A proposta do projeto é descobrir quais números são primos e quais não são,dentro de uma base de dados de 250.000 números

Deve-se portanto aprensentar uma solução sem o uso de threads e uma solução com. Então se calcular o SpeedUp.
Como cada execução varia o tempo, aconselha-se calcular uma média de 50 execuções para cada caso/cenário

Ao fim das execuções, deve-se concluir qual é a quantidade de threads ideal para a base utilizada, a fim de manter um bom SpeedUp.
## Ambiente Virtual (Poetry)	
`Poetry` é uma ferramenta para lidar com a instalação de dependências, bem como com a construção e empacotamento de pacotes `Python`. Ele só precisa de um arquivo para fazer tudo isso: o novo e padronizado `pyproject.toml`.

### Instalação

	pip install --user poetry

### Comandos

#### Shell
Gera um `shell`, de acordo como o `$SHELL` variável de ambiente, dentro do ambiente virtual. Se ainda não houver um, ele será criado.

	poetry shell

Dentro do ambiente virtual, basta executar o arquivo principal do projeto.

	python arquivo.py

### Mais sobre

[Website oficial do Poetry](https://python-poetry.org/)

