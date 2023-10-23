# ChatGPT-Prompt-Engineering

Get your API key from openai website.

Option 1: Set your ‘OPENAI_API_KEY’ Environment Variable using zsh in MacOS:
    1.  Run the following command in your terminal, replacing yourkey with your API key. 
        echo "export OPENAI_API_KEY='yourkey'" >> ~/.zshrc
    2.  Update the shell with the new variable:
        ource ~/.zshrc
    3.  Confirm that you have set your environment variable using the following command. 
        echo $OPENAI_API_KEY

Option 2: explicitely enter it in your code replacing yourkey with your API key.:
    openai.api_key = "yourkey"
