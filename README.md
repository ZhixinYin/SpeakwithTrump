# SpeakwithTrump bot
This bot was trained by Trump's tweets and the prompts are generated by ChatGPT-4o. MLX LoRA was used to fine-tune the AI model. 
The trained model is llama3.1-8B. You can also train your own AI model. You can find the training data in the data folder.

# Run
### Prerequisite
Make sure you have [ollama](https://ollama.com) and [python](https://www.python.org)

### Use ollama to create trained model

```
ollama create SpeakwithTrump -f Modelfile
```

### Run the model

```
python3 run_model.py
```

# Important notice
This project does not have any political purpose. It is just for fun! :)
