# Falcon40BFinetune

Use Falcon40BTrain to finetune Falcon 40B on a subset of the Open Assistant dataset provided [here](https://huggingface.co/datasets/timdettmers/openassistant-guanaco). You need atleast 40GB of GPU RAM to finetune this model which is being loaded in 4-bit using bitsandbytes. Connect your HuggingFace account by providing your access token in order to upload the adapters to your HF repo. Falcon40BTest shows you how to merge your adapters with base model and use it for inferencing. Remember to disconnect the kernel after training to create GPU RAM space for testing.
