conda create -n ibm_venv python=3.10.8
conda activate ibm_venv
activate ibm_venv
pip freeze
pip install -r requirements.txt
conda deactivate
conda env remove --name ibm_venv


pip install virtualenv
python -m venv ibm_venv
.\ibm_venv\Scripts\activate
pip install -r requirements.txt
deactivate

C:\Users\tomek\anaconda3\envs\ibm_venv\python.exe
~\anaconda3\envs\ibm_venv\python.exe




```shell
pip install virtualenv
python3 -m venv venv
pip install -r requirements.txt
.\myenvname\Scripts\activate
deactivate
pip freeze > requirements.txt

conda create --name moje_srodowisko python=3.8
conda info
conda env list 
conda create --name {env_name}
conda create --name test python=3.8
conda env remove --name test
activate env_name
conda deactivate
conda env export > environment.yml
conda env create -f environment.yml
conda env remove --name moje_srodowisko
```

Python 3.10.8