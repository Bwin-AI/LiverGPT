# LiverGPT
This is a large liver disease model fine-tuned using LoRa based on clinical liver disease data.

Fine-tuning is based on the Qwen14B base model built with LLama Factory. 
This method is implemented with Transformers4 and pef5 libraries.
In the training settings, the training batch size for each device is 2, the number of gradient accumulation steps is 8, the learning rate is set to 0.0001, the number of training epochs is 3, the cosine learning rate schedule is used, the number of warm-up steps is 0.1, and mixed precision training (fp16) is turned on.
