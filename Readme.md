## Create new environment and add libraries with poetry (no pip install needed)

poetry init --no-interaction
poetry add jupyterlab
poetry add pandas

## info sur environment

poetry env list
poetry env info
poetry show

if not activated or library not found problem

poetry install
poetry shell


## Lancez jupyter lab

jupyter-lab