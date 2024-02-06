# Django Hello World

cd GitHub\django_hello_world

conda create --name env_hello_world python

conda activate env_hello_world_310
conda deactivate

pip install Django==3.*

django-admin startproject hellodjango

cd hellodjango

python manage.py migrate