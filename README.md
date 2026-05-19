# Spark

## 1.3 Démarrage du cluster
Lancer la commande suivante :

```bash
docker compose up -d
```

Vérifier ensuite les conteneurs :

```bash
docker ps
```
Question: Qu'obtenevez vous ?

```
CONTAINER ID   IMAGE                             COMMAND                  CREATED         STATUS                   PORTS                                                                                                                                   NAMES
3f1b193e16c4   apache/spark:3.5.1                "/opt/entrypoint.sh …"   2 minutes ago   Up 2 minutes                                                                                                                                                     spark-worker-1
f49b12f17fa4   apache/spark:3.5.1                "/opt/entrypoint.sh …"   2 minutes ago   Up 2 minutes                                                                                                                                                     spark-worker-2
2c7533d7be60   apache/spark:3.5.1                "/opt/entrypoint.sh …"   2 minutes ago   Up 2 minutes                                                                                                                                                     spark-worker-3
123037bb582e   jupyter/pyspark-notebook:latest   "tini -g -- start-no…"   2 minutes ago   Up 2 minutes (healthy)   4040/tcp, 0.0.0.0:8888->8888/tcp, [::]:8888->8888/tcp                                                                                   spark-jupyter
46acea945b2b   apache/spark:3.5.1                "/opt/entrypoint.sh …"   2 minutes ago   Up 2 minutes   
```

## 1.4 Vérification du cluster
Interface Jupyter
Ouvrir :
```bash
https://urban-space-pancake-q4gg9wp9qv425p7-8888.app.github.dev/login?next=%2Flab%3F
```

