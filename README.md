# Split and Join File Manipulation Utility

This is a simple command-line utility for splitting and joining files.

## Features

- **Splitting files:** You can split large files into smaller chunks.
- **Joining files:** You can join multiple files into one.

## Usage

### Splitting Files

To split a file into smaller chunks, use the following command:

```bash
SaJ.exe -s <input_file> <chunk_size_in_MB> <output_folder>
```

Replace `<input_file>` with the path to the file you want to split, `<chunk_size_in_MB>` with the desired size of each chunk in megabytes, and `<output_folder>` with the directory where you want to save the split files.

### Joining Files

To join multiple files into one, use the following command:

```bash
SaJ.exe -j <input_folder> <output_file>
```

Replace `<input_folder>` with the directory containing the files you want to join, and `<output_file>` with the path where you want to save the joined file.

## Examples

### Splitting Files

```bash
SaJ.exe -s large_file.txt 10 output_folder
```

This command will split the file `large_file.txt` into chunks of 10 MB each and save them in the `output_folder`.

### Joining Files

```bash
SaJ.exe -j input_folder joined_file.txt
```

This command will join all files in the `input_folder` directory into a single file named `joined_file.txt`.

## Author

This utility was created by [Bazzirovan](https://github.com/Bazzirovan/). Feel free to contact me with any questions or feedback!

```
