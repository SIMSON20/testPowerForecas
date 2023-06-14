conda create --name testPowerForecastEnv python=3.11

conda activate testPowerForecastEnv

pip install requirements.txt 

python ./setup.py install


cd views 

streamlit run main.py
