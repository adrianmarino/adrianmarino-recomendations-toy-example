# Tourism recommendation system

A toy example.

### Install database
1. `yay -S neo4j-community`
2. disable SERVER authentication:
     1. `vim /etc/conf/neo4j.conf`
     2. Change `dbms.security.auth_enabled=false`
3. `sudo systemctl restart neo4j`

### Setup project
3. `conda env create -f environment.yml`
4. `conda activate neo4j-recomendations`
5. `jupyter labextension install @jupyter-widgets/jupyterlab-manager`


### Getting started

1. `conda activate neo4j-recomendations`
2. `jupyter lab`
3. Open [Jupyter Notebook](toy-example.ipynb).
4. Query browser: http://localhost:7474
