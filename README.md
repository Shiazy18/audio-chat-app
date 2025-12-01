# audio-chat-app
We will use the Phi-4-multimodal-instruct generative AI model to generate responses to prompts that include audio files and develop an app that provides AI assistance for a produce supplier company by using Azure AI Foundry and the Python OpenAI SDK to summarize voice messages left by customers.

## To run locally

Create a .env files with below values

``` code
PROJECT_ENDPOINT="your_project_endpoint"
MODEL_DEPLOYMENT="your_model_deployment"
```

replace the your_project_endpoint placeholder with the endpoint for your project (copied from the project Overview page in the Azure AI Foundry portal), and the your_model_deployment placeholder with the name you assigned to your Phi-4-multimodal-instruct model deployment.

install the libraries in islolated env, use the below commands

```code
python -m venv audioapp
./audioapp/bin/Activate.ps1
pip install -r requirements.txt azure-identity azure-ai-projects openai
```

## Summary
We have used Azure AI Foundry and the Azure AI Inference SDK to create a client application uses a multimodal model to generate responses to audio
