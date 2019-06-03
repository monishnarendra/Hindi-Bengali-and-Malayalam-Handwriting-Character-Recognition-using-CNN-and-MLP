# Hindi, Bengali and Malayalam Handwriting Character Recognition
Hindi, Bengali and Malayalam Handwriting Character Recognition is implemented using Convolution Neural Network (CNN) and (MLP). Handwritten character recognition is an old problem that has been extensively studied for many different languages around the world. However, there have not been much significant work done in the field of recognition of Hindi and Bengali.

Here we have implemented in two ways:
- Using Web Camera (Python 3)
- Using HTML (Web Technology)

## Datasets
1. Extended MNIST dataset (letters) - [English]()
2. DHCD (Devanagari Character Dataset) - [Hindi]()
3. CMATERdb (Bengali Character Dataset) - [Bengali]()
4. Malayalam Character Dataset - [Malayalam]()

## Dependencies
- Tensorflow 1.3 (Required)
- Keras
- OpenCV
- Numpy
- Pandas
- PIL
- Sckit-Learn
- Matplotlib
- NodeJS
- HTTP-Server
- TensorflowJS

## Trained on system having following configurations
- Name – ASUS ROG GL702
- RAM – 16 GB
- Processor – Intel® Core™ i7 6700HQ Processor
- GPU – NVIDIA GeForce GTX 970M
- Camera – HD Web Camera

## Folders and Files Information
__Bengali/__ - Contains All files Associated with Bengali Recognition

__English/__ - Contains All files Associated with English Recognition

__Hindi/__ - Contains All files Associated with Hindi Recognition

__Malayalam/__ - Contains All files Associated with Malayalam Recognition

__data/__ - Each Language Folder (Bengali, Hindi and English) contains its own dataset which is split into testing and training

__Models/__ - Each Language Folder (Bengali, Hindi and English) contains pre-stored models of both CNN and MLP

__web/__ - Contains All files Associated with Bengali, Hindi and English Web based Recognition. Which include HTML, CSS, JavaScript and Json files (models)

__English_Recognition.py__ - contains the code required for recognizing English character through web cam.

__Hindi_Recognition.py__ - contains the code required for recognizing Hindi character through web cam

__Bengali_Recognition.py__ - contains the code required for recognizing Bengali character through web cam

__Malayalam_Recognition.py__ - contains the code required for recognizing Malayalam character through web cam

## Execution
For Bengali - Run the notebooks in the following order:
```bash
1. Unpack Image.rar
2. Dat_Clean_Sort.ipynb
3. Bengali_CNN.ipynb
4. Bengali_MLP.ipynb
5. Bengali_Recognition.ipynb
```

For Hindi - Run the notebooks in the following order:
```bash
1. Unpack data.rar
2. Hindi_CNN.ipynb
3. Hindi_MLP.ipynb
4. Hindi_Recognition.ipynb
```

For English - Run the notebooks in the following order:
```bash
1. English_CNN.ipynb
2. English_MLP.ipynb
3. English_RNN.ipynb (Optional but if choose to run this then skip 4)
4. English_Recognition.ipynb
5. English_Recognition_CNN,MLP,RNN
```

For Malayalam - Run the notebooks in the following order:
```bash
1. Unpack Image.rar
2. Dat_Clean_Sort.ipynb
3. Malayalam_CNN.ipynb
4. Malayalam_MLP.ipynb
5. Malayalam_LSTM.ipynb
5. Malayalam_Recognition.ipynb
```

For execution of Web App: 
Open NodeJS and type the following code:
```bash
http-server (path)/Web App/
```

Then open browser and paste any one of the url:
```bash
http://192.168.107.1:8080
http://192.168.88.1:8080
http://192.168.0.107:8080
http://127.0.0.1:8080
```

## License
Copyright [2019] [Monish N] [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
