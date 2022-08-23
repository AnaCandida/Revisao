pip install fastapi

pip install "uvicorn[standard]"

Create a file  `main.py`, importanto e instanciando o FastApi

from  typing  import  Union  
from  fastapi  import  FastAPI  
app  =  FastAPI()

uvicorn main:app --reload