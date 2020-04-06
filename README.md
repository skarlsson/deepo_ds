# deepo_ds
deepo full container and datasources

https://github.com/ufoym/deepo

postgres support, psycopg2, sqlalchemy



docker build -f /home/saka/claes/deepo_ds/Dockerfile.all-jupyter -t deepo.all.jupyter . 
  

docker run -d -it -p 8888:8888 --ipc=host --name=jupypter-0 deepo.all.jupyter jupyter notebook --no-browser --ip=0.0.0.0 --allow-root --NotebookApp.token= --notebook-dir='/root'

open browser
http://localhost:8888/tree?



https://towardsdatascience.com/in-12-minutes-stocks-analysis-with-pandas-and-scikit-learn-a8d8a7b50ee7


