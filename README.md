<h1 align="center"> Integrate LLMs with Applications </h1>

<div align="center">
<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/Anaconda-3670A0?style=for-the-badge&logo=anaconda&logoColor=white">

</div>

<h1 align="center"> Welcome to the Integrate-LLMs-with-applications project! </h1>

This project demonstrates how to integrate **Large Language Models (LLMs)** into real-world applications, providing users with intelligent, natural language-driven functionalities that enhance user experience and business efficiency.

## 🚀 Requirements
1. **Anaconda Environment**  
2. **Python**  
3. Libraries listed in `requirements.txt`:
   - `load_dotenv==0.1.0`
   - `ibm_watson_machine_learning==1.0.345`
   - `ibm-cloud-sdk-core==3.16.7`
   - `streamlit==1.31.0`
   - `python-dotenv==1.0.0`



## 📌Instalasi
Pastikan Anaconda sudah di instal dan sudah digantikan di VScode/IDE lain menggunakan ctrl+shift+p select interpreter, pilih yang anaconda
1. Clone the repository:  
   ```bash
   git clone https://github.com/roland86-op/Integrate-LLMs-with-applications.git
2. Change Directory:
   ```bash
   cd your-repo
3. Install requirements.txt, ibm-watson-machine-learning, ibm-cloud-sdk-core, streamlit:
   ```bash
   pip install -r requirements.txt
   pip install ibm-watson-machine-learning
   pip install ibm-cloud-sdk-core
   pip install streamlit
3. Running file python:
   ```bash
   python ./demo_wml_api.py
   streamlit run demo_wml_api_with_streamlit.py
   
## 📝Contoh Hasil
   ```bash
   python demo_wml_api.py
---------------------------------------------------------------------------
Question/request: Write a paragraph about the capital of France.
Answer: Located in the east of France, Paris is the capital of France. It is also the most populated city of France with a population of 2.2 million people. It is the seat of the French parliament, the National Assembly. The city is located in the heart of France and is surrounded by the Île-de-France region.
---------------------------------------------------------------------------
C:\Users\LENOVO\anaconda3\Lib\site-packages\ibm_watson_machine_learning\foundation_models\utils\utils.py:273: LifecycleWarning: Model 'meta-llama/llama-2-13b-chat' is in deprecated state from 2024-08-26 until None. IDs of alternative models: None. Further details: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/fm-model-lifecycle.html?context=wx&audience=wdp
  warnings.warn(default_warning_template.format(
---------------------------------------------------------------------------
Prompt: 
    From the following customer complaint, extract 3 factors that caused the customer to be unhappy.
    Put each factor on a new line.

    Customer complaint:
            I just tried to book a flight on your incredibly slow website.  All
            the times and prices were confusing.  I liked being able to compare
            the amenities in economy with business class side by side.  But I
            never got to reserve a seat because I didn't understand the seat map.
            Next time, I'll use a travel agent!


    Numbered list of all the factors that caused the customer to be unhappy:


List of complaints: 1. Slow website
    2. Confusing times and prices
    3. Lack of understanding of the seat map
---------------------------------------------------------------------------
--------------------------Invocation with REST-------------------------------------------
Question/request: Write a paragraph about the capital of France.
Answer: Paris is the capital of France and the seat of government of the French Republic. The city is located in the heart of the Ile-de-France region, and its inhabitants are called Parisiens. The official name of the city is "Paris" (in French) or "Roubaix" (in Occitan).
---------------------------------------------------------------------------
