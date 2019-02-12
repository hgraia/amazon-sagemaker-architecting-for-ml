# Audio Books Classification By Author
Model to classify/predict audio books by authors of Jane Austen and Charles Dickens.

# Datasets
- Source of books are from Free MP3 Audio Books of authors can be found at:
http://www.openculture.com/freeaudiobooks

We selected  two books for training :
•	For Pride and Prejudice  from Jane Austen
•	A Christmas Carol from  Charles Dickens
    https://s3.amazonaws.com/books-on-tape-mlclass/test/t_PrideAndPrejudice.txt
	https://s3.amazonaws.com/books-on-tape-mlclass/test/t_christmas_carol.txt


For Validation

    https://s3.amazonaws.com/books-on-tape-mlclass/validation/v_copperfield.txt
    https://s3.amazonaws.com/books-on-tape-mlclass/validation/v_sense_and_sensability.txt


# Modeling Strategy
It is a two step process - 1) Convert MP3 audio books of above authors using AWS Transcribe service, and 2) Use BlazingText model to classify the books.

# End Goal
Predict the author of a book.