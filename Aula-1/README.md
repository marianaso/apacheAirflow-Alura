## Apache Airflow - Transformação de dados com Spark

 - Pasta datalake: contem os arquivos conforme estrutura final:
	 - Bronze: arquivo extraído
	 - Silver: arquivo refinado
	 - Gold: arquivo refinado
- Pasta src: contem os scripts em Python utilizados para a extração e transformação dos tweets via API.
- Pasta airflow-pipeline: contem DAGs, Operators e Hooks utilizados pelo Apache Airflow ao longo do processo.

Lembrando que utilizamos um ambiente venv para todo o processo, além da instalação do spark-3.3.2-bin-hadoop3. 
