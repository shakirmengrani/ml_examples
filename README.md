# Tensorflow with tensorboard in docker 
Very first you should install docker 
Then use blow command
docker run -it -p your desire port:8888 -p your desire port:6006 -v Your computer path:map to desire folder or notebooks IMAGE ID
Here 8888 is default port of jupyter notebook and 6006 is default port of tensorboard
#### To start tensorboard
docker exec CONTAINER ID tensorboard --logdir="/notebooks"
  
 After run "tf.summary.FileWriter" function then open up browser and visit http://localhost: Your desire port for tensorboard and see in Graph section
