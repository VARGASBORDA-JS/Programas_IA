=====Ejecucione=======

1. Instale las actualizaciones 
    -apt-get update
    -apt-get install -y libgl1-mesa-glx
    -apt-get install -y libglib2.0-0
    e instale:
        -pip install --upgrade --force-reinstall opencv-python-headless

 En caso de docker ejecute e instale las librerias:
    docker exec -u root -it <container_id_or_name> /bin/bash 
        -apt-get update
        -apt-get install -y libgl1-mesa-glx
        -apt-get install -y libglib2.0-0
    e instale:
        -pip install --upgrade --force-reinstall opencv-python-headless

2. Ejecute el codigo