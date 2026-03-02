Setup (macOS, using venv):

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pip install ipykernel
python -m ipykernel install --user --name=venv --display-name "oscillating_pingpong_env"
