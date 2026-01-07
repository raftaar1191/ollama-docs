# Example of Open source Model


| Company Name | Model Name |
|-------------|------------|
| Meta        | Ollama     |
| Google      | Gemma      |
| DeepSeek AI | DeepSeek  |
| Mistral     | Mistral   |
| OpenAI     | gpt       |
| Qwen        | Qwen      |
| Microsoft  | MAI       |



## Where to Find Open Models

- https://huggingface.co/
- Find them on the official company website



## Tools to running Open LLMs Locally
 - Llama.cpp
 - LM Studio ( This is a wrapper based on Llama.cpp with UI )
 -  Ollama ( This is a wrapper based on Llama.cpp without UI )
 - https://groq.com/ ( Paid )



## Inference
Trained models generate output based on input. The process in which we get the output from the Model is called the Inference and for that we need a server that must have hosted an already trained model.


## Calculate Token
	https://tiktokenizer.vercel.app/



## Run Model in Ollama
 - Ollama pull model-id -> to download the model into the local machines
 - Ollama run model-id -> to download the model into the local machines and also run it
 - By using the modelfile https://docs.ollama.com/modelfile Example: ollama create m1 -f /FILEPATH/modeltextfile.txt
 - By using the GGUI format model file
