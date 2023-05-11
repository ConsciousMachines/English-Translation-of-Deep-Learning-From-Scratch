This is a translation of the best books ever written, called [Deep Learning From Scrach](https://koki0702.github.io/dezero-book/en/index.html) series. I already did the translation using Google Translate API. You can use the patch files I made to translate your own copy, by updating the path and name of your .EPUB file:

```Python
work_dir = r'/path/to/books/'
for i in [r'DL1.epub', r'DL2.epub', r'DL3.epub', r'DL4.epub']:
    book_path = os.path.join(work_dir, i)
    patch_file_path    = r'DL1_patch.txt'
    patch_book(book_path, patch_file_path)

```
