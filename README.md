# SEACF
## Download tweet images and set up image path
- Download each tweet's associated image via this link (https://drive.google.com/file/d/1PpvvncnQkgDNeBMKVgG2zFYuRhbL873g/view).
- Before you run the bash file, you need to change the parameter --img_path to your saved path.
- For the textual input of each sample, please refer to TomBERT to download them from the absa_data folder, and then change the parameter --data_dir to your saved path.
## data and roberta
- Create a new folder named data and a folder named roberta.
- The Roberta pre-trained model can be downloaded from Hugging Face:https://github.com/huggingface/transformers.
## Training and Inference
```bash
bash run_himt.sh
```
## Acknowledgements
Most of the codes are based on the codes provided by huggingface: https://github.com/huggingface/transformers.
