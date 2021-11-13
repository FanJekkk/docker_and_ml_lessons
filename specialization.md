docker run -v C:/Users/dns/Desktop/Specialization:/home/jovyan/ 8000:8000 -p jupyter/scipy-notebook:33add21fab64
docker run -p 8888:8888 jupyter/scipy-notebook:33add21fab64

docker run -it --rm -p 8889:8888 --network none jupyter/scipy-notebook:33add21fab64

docker run --rm -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes -v C:\Users\dns\Desktop\Specialization:/home/jovyan/work jupyter/datascience-notebook:33add21fab64