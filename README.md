# **Wav2Lip**: *Accurately Lip-syncing Videos In The Wild*

## Highlights

- Works for any identity, voice, and language, including CGI faces and synthetic voices.
- Complete training code, inference code, and pretrained models are available.
- Quick-start with the Google Colab Notebook: [Link](https://colab.research.google.com/drive/1tZpDWXz49W6wDcTprANRGLo2D_EbD5J8?usp=sharing).

## Prerequisites

- `Python 3.6`
- ffmpeg: `sudo apt-get install ffmpeg`
- Install necessary packages using `pip install -r requirements.txt`.
- Download the face detection pre-trained model and place it in `face_detection/detection/sfd/s3fd.pth`.

## Inference (Lip-syncing videos using pre-trained models)

You can lip-sync any video to any audio:
```bash
python inference.py --checkpoint_path <ckpt> --face <video.mp4> --audio <an-audio-source> 
```
The result is saved (by default) in `results/result_voice.mp4`. You can specify the output path using the `--outfile` argument.

## Training (Preparing LRS2 dataset and training the models)

Please follow the instructions in the repository for training the models on the LRS2 dataset. For other datasets, specific modifications may be required.

## Acknowledgements

Parts of the code structure are inspired by the [TTS repository](https://github.com/r9y9/deepvoice3_pytorch). We also thank the authors of the [face_alignment](https://github.com/1adrianb/face-alignment) repository for releasing their code and models. Special thanks to [zabique](https://github.com/zabique) for the tutorial collab notebook.#   L i p - s y n c - u s i n g - W a v 2 L i p - s i m p l i f i e d  
 #   L i p - s y n c - u s i n g - W a v 2 L i p - s i m p l i f i e d  
 #   L i p - s y n c - u s i n g - W a v 2 L i p - s i m p l i f i e d  
 