# English Translation of "Deep Learning From Scratch"

This is a translation of the best book series ever written, called [Deep Learning From Scrach](https://koki0702.github.io/dezero-book/en/index.html). I already did the translation using Google Translate API. If you buy the book, you can use the patch files I made to translate your own copy!

![sample.png](https://github.com/ConsciousMachines/English-Translation-of-Deep-Learning-From-Scratch/blob/main/docs/sample.png)

## Why?

There are a lot of books on Deep Learning, but they all drone on forever when it would be much faster to just see how it works via code. Notable exceptions in English are [micrograd](https://github.com/karpathy/micrograd) by Andrej Karpathy, and  [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/index.html) by Michael Nielsen. However, these are just toys. I stumbled upon DLFS, which is capable of running models of arbitrary complexity, with a book to explain it all! As such, this is the **only resource anybody needs to understand deep learning**. 

## Usage

Simply update the path of your .EPUB file:

```Python
book_path          = r'/path/to/books/DL1.epub'
patch_file_path    = r'DL1_patch.txt'
patch_book(book_path, patch_file_path)
```

## Features

- **In-line latex**: Because text had to be pulled out of paragraphs, the in-line latex between Japanese words is now clustered at the end of a paragrah. You will need to figure out which formula is being referred. 
