This project fine-tunes Llama 3 (8B, instruction/chat model) on a domain dataset (medical patient-doctor dialogues), then merges the adapter weights into the base model, quantizes it into GGUF format, and enables local inference via tools like the Jan application. 

It shows how to go from training on cloud/GPU, to pushing the model to Hugging Face, converting/quantizing to a lightweight format, and finally running the model locally
