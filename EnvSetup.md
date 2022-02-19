## Step 1. Create a new virtual environment

    python -m venv tfod

## Step 2. Activate your virtual environment

    source tfod/bin/activate # Linux
    .\tfod\Scripts\activate # Windows

## Step 3. Install dependencies and add virtual environment to the Python Kernel

    python -m pip install --upgrade pip
    pip install ipykernel
    python -m ipykernel install --user --name=tfod
