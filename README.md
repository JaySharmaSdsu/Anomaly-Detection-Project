# CCTV
Defect detection in underground infrastructures

# Setup for development:

- Setup a python venv (`.venv`)
- You can run `./scripts/create-venv.sh` to generate one
- Upgrading pip `pip3 install --upgrade pip`
- Install pip-tools `pip3 install pip-tools`
- Update requirements: `pip-compile --output-file=requirements.txt requirements.in`
- Install requirements `pip3 install -r requirements.txt`

## Update versions
`pip-compile --output-file=requirements.dev.txt requirements.dev.in --upgrade`
