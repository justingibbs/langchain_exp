# langchain_exp

## Get started

1. Create a virtual environment to run
```
python3 -m venv env_langchain_exp
source env_langchain_exp/bin/activate
```

2. Install requirements
```
pip install -r requirements.txt
```

Had to comment out `multidict` but the latest version seems to be installed, so moving forward until told otherwise.

3. Create a .env file with 
```
# This is a comment, ignored by the program
ANTHROPIC_API_KEY=your_api_key_here
```