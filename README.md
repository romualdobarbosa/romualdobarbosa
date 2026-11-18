# Oi, eu sou o Romualdo

Construo pipelines de dados de ponta a ponta, em batch e em streaming, e agora estou levando o mesmo cuidado com medição pros sistemas de IA. Os números abaixo estão nos repositórios, dá pra conferir.

## Projetos em destaque

- [Vox Urna](https://github.com/romualdobarbosa/vox_urna): arquitetura medallion sobre os boletins de urna do TSE. No 2º turno de 2026 foram 499.207 boletins decodificados, com os totais batendo voto a voto com o resultado oficial. [Dashboard](https://voxurna.streamlit.app/)
- [Sentinela Coins](https://github.com/romualdobarbosa/sentinela_coins): Apache Kafka com 3 brokers e fator de replicação 3, 66,1 milhões de trades da Binance em 7 dias e bronze no AWS S3. Na auditoria achei 169 duplicatas geradas pelo at-least-once, e a camada raw com deduplicação idempotente resolve isso. [Dashboard](https://sentinelacoins.streamlit.app/)
- [YouTube View Counter](https://github.com/romualdobarbosa/youtube_view_counter): YouTube Data API → dbt → DuckDB, com dimensões SCD2 e 27 cargas diárias agendadas no GitHub Actions. [Dashboard](https://youtubeviewcounter.streamlit.app/)

Em construção: [Dennou](https://github.com/romualdobarbosa/dennou), um RAG local sobre minhas notas, e [linkeasy](https://github.com/romualdobarbosa/linkeasy), um pipeline de conteúdo pro LinkedIn orquestrado por agente de IA com skills especializadas.

## In English

I build end-to-end data pipelines, batch and streaming, and I'm bringing the same measurement discipline to AI systems. Highlights: a medallion pipeline that decoded 499,207 official Brazilian ballot-box records and reconciled them vote for vote with the official results ([Vox Urna](https://github.com/romualdobarbosa/vox_urna)); a 3-broker Apache Kafka pipeline that ingested 66.1M crypto trades in 7 days into a lakehouse on AWS S3, where an audit found 169 duplicates from at-least-once delivery, now handled by idempotent deduplication ([Sentinela Coins](https://github.com/romualdobarbosa/sentinela_coins)); and an ELT pipeline with YouTube Data API, dbt and DuckDB, with SCD Type 2 dimensions and 27 scheduled loads on GitHub Actions ([YouTube View Counter](https://github.com/romualdobarbosa/youtube_view_counter)).

## Stack

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=for-the-badge&logo=podman&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge&logoColor=white)

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/romualdo-barbosa-b43935244/)
