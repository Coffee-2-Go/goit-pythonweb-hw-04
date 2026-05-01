# Tier 2. Module 6 - Fullstack Web Development with Python

## Topic 4. Homework - Asynchronous programming in Python

A Python script that reads all files in a user-specified source folder and sorts them into subfolders in the output folder based on file extension. The script performs the sorting asynchronously to process large numbers of files more efficiently.

### Instruction

```bash
git clone https://github.com/Coffee-2-Go/goit-pythonweb-hw-04.git
```

```bash
cd goit-pythonweb-hw-04
```

```bash
poetry install
```

```bash
poetry run python app/main.py path/to/source_folder path/to/output_folder
```

### Technical task

1. Import the necessary asynchronous libraries.
2. Create an `ArgumentParser` object to process command line arguments.
3. Add the necessary arguments to specify the source and destination folders.
4. Initialize the asynchronous paths for the source and destination folders.
5. Write an asynchronous function `read_folder` that recursively reads all files in the source folder and its subfolders.
6. Write an asynchronous function `copy_file` that copies each file to the corresponding subfolder in the destination folder based on its extension.
7. Configure error logging.
8. Run the asynchronous function `read_folder` in the main block.
