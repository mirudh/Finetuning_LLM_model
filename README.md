In this repository we focus on how to finetune a pretrained model on our custom data to get improved results.

The steps to finetune the model are as follows:

1. Installing the dependencies
   - bitsandbytes
   - transformers
   - peft
   - accelerate

2. Load the model, we are going to use - GPT-neo-x-20B!
Note that the model itself is around 40GB in half precision

3. Preprocessing the model to prepare it for training. For that use the prepare_model_for_kbit_training method from PEFT

4. Load a common dataset, here we use a dataset containing english quotes to fine tune our model on these famous quote

5. Training and testing the model

To execute the above steps. Run the 'LLM-finetuning' notebook given above.


You can also download the finetuned model checkpoints from the drive link given below :

https://drive.google.com/file/d/1wLTai8WgYntrlQE7Oh_DnYtrSEl7UPzO/view?usp=sharing
