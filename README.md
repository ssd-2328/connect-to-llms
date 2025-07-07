# How to use Ollama to run LLMs locally

Added different approaches using three various LLM models - llama3.2, OpenAI, deepseek-r1:1.5b

Follow below steps to connect to Ollama ->

Visit [ollama.com](https://ollama.com) and install!

Once complete, the ollama server should already be running locally.  
If you visit:  
[http://localhost:11434/](http://localhost:11434/)

You should see the message `Ollama is running`.  

If not, bring up a new Terminal (Mac) or Powershell (Windows) and enter `ollama serve`  
And in another Terminal (Mac) or Powershell (Windows), enter `ollama pull llama3.2`  
Then try [http://localhost:11434/](http://localhost:11434/) again.
