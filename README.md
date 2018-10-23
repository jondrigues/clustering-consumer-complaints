# Consumer-Business-Complaints

Kaggle - Dataset: Consumer Business Complaints in Brazil 

1- Dataset:
	- Fazer download dos dados:
		https://www.kaggle.com/gerosa/procon#reclamacoes-fundamentadas-sindec-2012.csv
		https://www.kaggle.com/gerosa/procon#reclamacoes-fundamentadas-sindec-2013.csv
		https://www.kaggle.com/gerosa/procon#reclamacoes-fundamentadas-sindec-2014.csv
		https://www.kaggle.com/gerosa/procon#reclamacoes-fundamentadas-sindec-2015.csv
		https://www.kaggle.com/gerosa/procon#reclamacoes-fundamentadas-sindec-2016.csv
	- Os datasets devem ser salvos em uma pasta chamada "data";
	- A pasta "data" deve ser criada na raiz do arquivo .ipynb ou py


2- Bibliotecas:
	- Sertifique-se de ter instalado em seu ambiente as seguintes bibliotecas:
		nltk, etc

3- Agrupamento em função das características  das reclamações:

	Todos os dados concatenados possuem mais de 1 milhão de linhas.
	Para rodar o script com uma amostra menor é necessário retirar o comentário (caracter "#") das seguintes linhas:

		#numSampleRow = 5000
		#procon = procon.sample(numSampleRow)

	A variável numSampleRow possui a quantidade de linhas a serem utilizadas como sample do estudo. 
	Por default ela está definida com 5000, mas pode ser modificada.

	
	- O resultado dos clusters como o banco de dados completo são salvos na variável "proconResult"
	- Os dataframe "proconResult" é importado para um arquivo .csv na raiz do projeto com nome "proconResult.csv"
	
