# Gensiss-Text-Completion---MLM

## Overview 

Genesis is the first book in the bible which written by moses. The book talks about creation of the world, how humans are created and start to struggle their life in the earth.
I created a Project on Masked Language Model. It is domain focused on Genesis book from the bible. The model is finetuned with genesis texts and now it can predict the next word after giving next word.

MLM is used for training transformer-based language models. This approach is known as Filtering mask. 

For example, the sentence 
"The cat sat on the mat" might be transformed to 
"The [MASK] sat on the [MASK]".

The objective of this model is to predict original words which masked intentionally. 

## Installation

Use [Hugging Face](https://huggingface.co/models) to download models for pretraining.

```bash
pip install transformer
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.



## License

[MIT](https://choosealicense.com/licenses/mit/)
