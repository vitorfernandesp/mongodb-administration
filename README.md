# 🌱 MongoDB 

Bem-vindo ao repositório de consultas que utilizo diariamente como DBA!

Este repositório é uma coleção valiosa de comandos para monitoramento, manutenção e troubleshooting.

## 📂 Tópicos

- **📊 Monitoramento**

  - db.serverStatus() → Status do servidor

  - db.stats() → Estatísticas do banco

  - db.collection.stats() → Estatísticas da coleção

  - db.currentOp() → Operações em andamento

- **🛠️ Manutenção**

  - db.collection.createIndex({campo: 1}) → Cria índice

  - db.collection.dropIndex('indexName') → Remove índice

  - db.repairDatabase() → Repara banco

  - db.collection.reIndex() → Reorganiza índices

- **🔍 Troubleshooting**

  - db.killOp(opId) → Encerra operação

  - db.currentOp({ "secs_running": { "$gte": 60 } }) → Queries lentas

  - db.getProfilingStatus() → Status do profiler

  - db.setProfilingLevel(2) → Ativa monitoramento
