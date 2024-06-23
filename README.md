# KeepCoding-IA-I-llm-engineering-Practice

Las consignas de la práctica están en el archivo

[0- Práctica LLMs.pdf](./0%20-%20Práctica%20LLMs.pdf)

Como no se me ocurrió ninguna idea, lo que hice fue modificar el ejemplo del profesor.
Para que no sea idéntico, se lo adaptó para que responda en Castellano en vez de catalan.
Además, se utilizó para entrenar un modelo que solo contenga inglés y castellano, lo que hace necesario algunas adaptaciones simples extras a los notebooks originales.



## Mi ejemplo (Ejemplo del profesor modificado a Castellano)
- Quiero demostrar que el modelo Flor es un buen modelo para un 
Chatbot de asistencia al cliente
- Voy a partir del modelo fundacional y lo voy a finetunear para que 
responda mejor como un modelo de asistencia al cliente
- Necesito un dataset con Q&A en ~~catalan~~ Castellano
- Voy a finetunear una versión del modelo cuantificado Flor 1.3B
- Para demostrar que funciona lo voy a testear con un RAG sencillo.

laboratorios:  
[1- CustomerService_Spanish_dataset.ipynb](./1-%20CustomerService_Spanish_dataset.ipynb)     
[2- CustomerServiceTuning_FLOR1_3B_QLoRA.ipynb](./2-%20CustomerServiceTuning_FLOR1_3B_QLoRA.ipynb)         
[3- CustomerServiceInference_FLOR1_3B.ipynb](./3-%20CustomerServiceInference_FLOR1_3B.ipynb)     
[4- CustomerServiceRAG_Langchain_FLOR1_3B-finetuned.ipynb](./4-%20CustomerServiceRAG_Langchain_FLOR1_3B-finetuned.ipynb)        



## Extra

Se hizo fine tuning sobre un chat entrenado con videos de "Javier Milei"
Para lo cual se partió de un ejemplo de **Instruct-tuning de LLaMA 2 con QLoRA** y se lo adapto para que use **LLaMA 3**

[Milei chat tuning con LLaMA 3 y QLoRA.ipynb](./Milei%20chat%20tuning%20con%20LLaMA%203%20y%20QLoRA.ipynb)



## Links a colab de respaldo

Chatbot customer-service Castellano     

https://colab.research.google.com/drive/1gvCiXegDVZtke9Nu15-yEnPkeLmShc8N?usp=sharing    

https://colab.research.google.com/drive/19FqffgWNPZkQghkmBb4w5akdJUf8P-id?usp=sharing     

https://colab.research.google.com/drive/1shiNsuKQx3OBqyOOvNzMq5qZ59SsyVIX?usp=sharing     

https://colab.research.google.com/drive/1OzB2V39GlbkKBuCZZAii6qLMknuFduP9?usp=sharing     



Milei chat tuning con LLaMA 3 y QLoRA.ipynb   

https://colab.research.google.com/drive/12KpR44RG-4cgJp3mRCsoDGYk3CJPqjan?usp=sharing    