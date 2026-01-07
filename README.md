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
 - By using the modelfile https://docs.ollama.com/modelfile Example: ollama create model-name -f /FILEPATH/modeltextfile.txt and then run ollama run model-name
 - By using the GGUI format model file


 ## Access models
 - Can access via terminal by using the Ollama run model-id command
 - Can also use the default Ollama GUI
 - Can also use Open WebUI https://openwebui.com/ollama/


## Setting up Open WebUI for Ollama
 - Install docker desktop
 - Star t docker desktop
 - To download the image run command ```docker pull ghcr.io/open-webui/open-webui:main```
 - TO start run ```docker run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui ghcr.io/open-webui/open-webui:main```
