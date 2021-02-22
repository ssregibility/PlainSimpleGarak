# Plain Simple Garak - A Quote Generator

Plain Simple Garak is a BiGRU text generation model that the goal is generating texts similar to [Garak](https://memory-alpha.fandom.com/wiki/Elim_Garak, "Memory Alpha")'s quotes.   
The model contains two seperate GRU layers and a shared Embedding layer. For each input, the model randomly selects which layer should be used - meaning that the text generated will be always different for the same input.

## Requirements

- Python 3.6.9+
- Pytorch 1.7.0+
- CUDA 10.1+
- nltk 3.0+
- Pandas 1.0+

To install requirements:

```setup
pip3 install -r requirements.txt
```

## Model Training

Upload PlainSimpleGarak.ipynb to your Google Drive for training. .py script file will be uploaded soon.

## Text Generation

Upload PlainSimpleGarak_GenerateText.ipynb, saved_dicts and a prtrained model below to your Google Drive for text generation. .py script file will be uploaded soon.

## Pretrained Model

https://drive.google.com/file/d/1u0EUo2XYVCoLl2PtLgp77L3wkTeBGjOU/view?usp=sharing

## Examples

```
INITIAL INPUT: spy? i 'm plain and simple
GENERATED SEQUENCE: spy ? i 'm plain and simple garak , captain , i 've been in this conversation . but i 'd rather not be ever seen the head of the agency ever , even for the moment . END
```

```
INITIAL INPUT: spy? i 'm plain and simple
GENERATED SEQUENCE: spy ? i 'm plain and simple garak . i never know what might happen . END
```

```
INITIAL INPUT: i'm not a spy, doctor .
GENERATED SEQUENCE: i 'm not a spy doctor . i 'm sure you 'll derive years of enjoyment trying to determine exactly who they are . END
```

```
INITIAL INPUT: i'm not a spy, doctor .
GENERATED SEQUENCE: i 'm not a spy doctor . i always said your shortsightedness would be your downfall . END
```
```
INITIAL INPUT: doctor bashir
GENERATED SEQUENCE: doctor bashir may provide them with an unfortunate misunderstanding . i would n't have the time to make a good idea . END
```

## Contributing

There is no way to contribute to the code yet - however, this is subject to be changed.

## Attribution

Uses TNG.csv by RMHogervorst from https://github.com/RTrek/startrekTNGdataset
