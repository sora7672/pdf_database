# PDF Database

#### Preface
As i got into talks with my stepdad, we talked about that he has so many
PDFs (maybe also some other files types) and its a pain to find articles
or files he just knows some side parameters, liek maybe one word/title.
So i thought abut, why not writing a DB for that and some smart algorithms.
The goal is a free and local program to find what you saved anywhen.

## What should this program do?
The user should be able to add PDFs (later some other file types too, or convert images automatically to a pdf)
easy into the program (best is drag and drop and alternativ a file navigation).
The files then will be moved to the directory the DB saves their files.
The file will be analyzed & auto indexed, with a preview of indexed words,
which the user then can swap in order of priority and also add some other keywords manually.
Most of the order should be created automatically.
Infos will only be saved locally, in case its private data (like diarys, project ideas and so on) 
The program will include a backup option, where the data can be saved onto a external USB/Drive
automatically (with also checking before if files exist, maybe with hash file values comapred if its really the same)


## Technical infos
- Python with SQLite
- Rest to follow
