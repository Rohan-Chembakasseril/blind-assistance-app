# blind-assistance-app
This app has been built as a course outcome in the IDL401 course under Instructor Dr. Ankit Bhurane at Visvesvaraya National Institute of Technology.The purpose of this project is to build a blind assistance system using custom or existing pre-trained models. I have implemented it using 4 different models. It takes a live image input from the camera, and generates a descriptive summary. The output is an audio corresponding to the text summary generated.

1]VIT-GPT2: The Vision Encoder Decoder Model has been used to initialize an image-to-text model using VIT as the encoder and the pre-trained language model GPT2 as the decoder.

2]BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation: a)Large, b) Base and c)Long. BLIP is a new Vision Language Processing framework which transfers flexibly to both vision-language understanding and generation tasks. BLIP effectively utilizes the noisy web data by bootstrapping the captions, where a captioner generates synthetic captions and a filter removes the noisy ones.
