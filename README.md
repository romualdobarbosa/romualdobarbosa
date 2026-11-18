# Oi, eu sou o Romualdo

Construo pipelines de dados de ponta a ponta, em batch e em streaming, e agora estou levando o mesmo cuidado com medição pros sistemas de IA. Os números abaixo estão nos repositórios, dá pra conferir.

## Projetos em destaque

- [Vox Urna](https://github.com/romualdobarbosa/vox_urna): arquitetura medallion sobre os boletins de urna do TSE. No 2º turno de 2026 foram 499.207 boletins decodificados, com os totais batendo voto a voto com o resultado oficial. [Dashboard](https://voxurna.streamlit.app/)
- [Sentinela Coins](https://github.com/romualdobarbosa/sentinela_coins): Apache Kafka com 3 brokers e fator de replicação 3, 66,1 milhões de trades da Binance em 7 dias e bronze no AWS S3. Na auditoria achei 169 duplicatas geradas pelo at-least-once, que a camada raw com deduplicação idempotente resolve, e compactar 6.946 parquets em 40 derrubou a leitura do S3 de 709 s pra 56 s. [Dashboard](https://sentinelacoins.streamlit.app/)
- [YouTube Audience Pipeline](https://github.com/romualdobarbosa/youtube-audience-pipeline): YouTube Data API → dbt → DuckDB pra medir quem ganhou a Copa 2026 no YouTube entre 4 canais de esporte. A CazéTV ficou com 94,9% das views do grupo durante o torneio. A parte de podcasts tem dimensões SCD2 e rodou 27 cargas no GitHub Actions. [Dashboard](https://youtubeviewcounter.streamlit.app/)

Em construção: [Dennou](https://github.com/romualdobarbosa/dennou), um RAG local sobre minhas notas, e [linkeasy](https://github.com/romualdobarbosa/linkeasy), um pipeline de conteúdo pro LinkedIn orquestrado por agente de IA com skills especializadas.

## In English

I build end-to-end data pipelines, batch and streaming, and I'm bringing the same measurement discipline to AI systems. Highlights: a medallion pipeline that decoded 499,207 official Brazilian ballot-box records and reconciled them vote for vote with the official results ([Vox Urna](https://github.com/romualdobarbosa/vox_urna)); a 3-broker Apache Kafka pipeline that ingested 66.1M crypto trades in 7 days into a lakehouse on AWS S3, where an audit found 169 duplicates from at-least-once delivery, now handled by idempotent deduplication, and compacting 6,946 parquet files into 40 cut S3 reads from 709 s to 56 s ([Sentinela Coins](https://github.com/romualdobarbosa/sentinela_coins)); and an ELT pipeline with YouTube Data API, dbt and DuckDB that measured which of 4 Brazilian sports channels won the 2026 World Cup on YouTube, plus SCD Type 2 dimensions and 27 loads on GitHub Actions ([YouTube Audience Pipeline](https://github.com/romualdobarbosa/youtube-audience-pipeline)).

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
