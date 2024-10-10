# Data Engineering 101

## Section 01. Introductions

### What is Data-Engineering?

- Data flows
  - Generated
  - Changed(Transformed, saved)
  - Served(Web, Analysis, ML, DL ...)

<p style="color:#2373dc">! kafka, flink 데이터 -> 실시간 배달 위치 같은거 처리할 수 있다.</p>

### Why is it important?

- Explosion of data sources
- Explosion of data uses

### End-to-end Datapipeline

- Two parts of D.P.

  - Data Pipeline
    - ETL / ELT
  - Under currents
    - Orchestration
    - Security
    - Data governance
    - DataOps
    - Data Quaility
    - Software Engineer

### Data Pipeline

- Ingestion: storing raw data
  - raw data: orderd data, images, unoreded values ...
- Storage
  - RDB(Mysql)
  - Object(S3)
- Serving
  - to other team memebers...

<p style="color:#2373dc">! 스토리지는 데이터 엔지니어링 전체 과정에서 다양한 형태로 발생</p>

### Undercurrent

- properties that data processed well

### Data warehouse

- well-ordered data(RDB)
  - data driven decisions
- Massive Pararrel Processing
- Monolithic, On-premise

### Cloud base

- distributed data storage
- cloud base, easily scalable
