<h1 align="center">model_LLM(saiga_mistral_7b)_wikipedia</h1>

<h2 align="center">Used Libraries</h2>
<div align="center">

 <a href="https://www.python.org" target="_blank" rel="noreferrer" style="display: inline-block;"> 
   <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="60" height="60"/>
 </a>

 <a href="https://numpy.org/" target="_blank" rel="noreferrer" style="display: inline-block;">
   <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="Numpy" alt="Numpy" width="60" height="60"/> 
 </a>

 <a href="https://www.tensorflow.org/" target="_blank" rel="noreferrer" style="display: inline-block;"> 
   <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" title="tensorflow" alt="tensorflow" width="60" height="60"> 
 </a>

 <a href="https://keras.io/" target="_blank" rel="noreferrer" style="display: inline-block;">
   <img src="https://github.com/devicons/devicon/blob/master/icons/keras/keras-original.svg" title="keras" alt="keras" width="60" height="60"> 
 </a>

 <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer" style="display: inline-block;">
   <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" title="Pandas" alt="Pandas" width="60" height="60"/> 
 </a>

<a href="https://pytorch.org/" target="_blank" rel="noreferrer" style="display: inline-block;">
   <img src="https://avatars.githubusercontent.com/u/21003710?s=200&v=4" title="pytorch" alt="pytorch" width="60" height="60"/> 
</a>

<a href="https://huggingface.co/docs/hub/index" target="_blank" rel="noreferrer" style="display: inline-block;">
   <img src="https://avatars.githubusercontent.com/u/25720743?s=200&v=4" title="huggingface" alt="huggingface" width="60" height="60"/> 
</a>

<a href="https://www.llamaindex.ai/" target="_blank" rel="noreferrer" style="display: inline-block;">
   <img src="https://avatars.githubusercontent.com/u/130722866?s=200&v=4" title="llamaindex" alt="llamaindex" width="60" height="60"/> 
 </a>

<a href="https://www.wikipedia.org/" target="_blank" rel="noreferrer" style="display: inline-block;">
   <img src="https://www.wikipedia.org/portal/wikipedia.org/assets/img/Wikipedia-logo-v2.png" title="wikipedia" alt="wikipedia" width="60" height="60"/> 
 </a>
</div>

<h2 align="center">Instructions</h2>


## Installation of Dependencies

You can install the required dependencies either manually or using the `requirements.txt` file.

###  Install Manually
```bash
pip install torch
pip install numpy
pip install gradio
pip install huggingface-hub
pip install llama_index
pip install llama-index-llms-huggingface
pip install llama-index-embeddings-huggingface
pip install llama-index-embeddings-langchain
pip install llama-index-readers-wikipedia
pip install transformers
pip install sentencepiece
pip install bitsandbytes
pip install peft
pip install accelerate
pip install tokenizers
pip install langchain
pip install langchain_community
pip install langchain-huggingface
pip install pypdf
pip install wikipedia
pip install pyvis
pip install Ipython
pip install regex
pip install packaging
pip install pyyaml
pip install requests
pip install tqdm
pip install filelock
pip install safetensors

````

### Install using the `requirements.txt` file
```bash
pip install -r requirements.txt

````
### Описание программы

Создан граф знаний для чат-бота с использованием модели <a href = "https://huggingface.co/IlyaGusev/saiga_mistral_7b_lora">saiga_mistral_7b_lora</a> в качестве основы. Модель была дообучена для взаимодействия с графом знаний, позволяющим боту отвечать на вопросы по заданной теме, используя информацию из <a href='https://www.wikipedia.org/'>Wikipedia</a>, с применением подхода RAG (Retrieval-Augmented Generation).

Также был добавлен интерфейс для взаимодействия с готовым чат-ботом, а также возможность добавлять новые графы знаний, что расширяет функциональность чат-бота.

Модель была взята из <a href="https://huggingface.co/docs/hub/index">Hugging-Face</a> и использует
<a href = "https://huggingface.co/IlyaGusev/saiga_mistral_7b_lora">saiga_mistral_7b_lora</a> как базовую