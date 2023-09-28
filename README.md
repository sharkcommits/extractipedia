# Wikimedia Extractor

The following package aims to create plain-text WikiMedia file in order to create faiss-like indexes for special purposes such as 
scientific chunk, sports chunk.

<b>Input file:</b> wikimedia xls file which can be found on [Wikimedia Dumps](https://dumps.wikimedia.org/enwiki/).

<b>Output file:</b> SQLite database.

## Potential Improvements:

- Get the templates and split the entire .xls into seperate and desired files.
- Increase speed, using multiprocessing.
- Simplify the regex, more human-readable.
- Get the tables (if there is any) and process them.

### Let there be extraction!
