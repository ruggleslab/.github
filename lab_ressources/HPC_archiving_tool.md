# HPC Archiving Command Line Guide

Efficient data management is crucial in High-Performance Computing (HPC) environments. This guide provides an overview of the `archive` command-line tool, designed to help you manage your files within the HPC system effectively.

## Usage

The `archive` command facilitates various operations related to file archiving. Below is the general syntax and available options:

`archive [OPTION]...`

### Options

- `-h`, `--help`: Display usage information.
- `-s`, `--status <FilePath>`: Check the status of a specific file.
- `-d`, `--directory <DirPath>`: Add a directory to the archive queue.
- `-f`, `--file <FilePath>`: Add a file to the archive queue.
- `-l`, `--list <DirPath>`: List the status of files within a directory.
- `-p`, `--pending`: List pending objects in the archive queue.
- `-r`, `--recall <FilePath>`: Recall a file from the archive in the background.

## Usage Examples

Here are some common use cases for the `archive` command:

1. **Check File Status**

   To verify the status of a file:

   `$ archive -s /path/to/file`

2. **Archive a Directory**

   To add a directory and its contents to the archive queue:

   `$ archive -d /path/to/directory`

3. **Archive a File**

   To add a single file to the archive queue:

   `$ archive -f /path/to/file`

4. **List File Status in a Directory**

   To list the status of all files within a directory:

   `$ archive -l /path/to/directory`

5. **List Pending Archive Objects**

   To view all pending items in the archive queue:

   `$ archive -p`

6. **Recall a File**

   To recall a file from the archive:

   `$ archive -r /path/to/file`

   *Note:* Retrieving files from tape storage may take some time, especially for larger files. There may not be a prompt confirming the recall, so use this command cautiously.

## Additional Information

For more detailed information about storage policies, archiving criteria, recall times, and permissions, please refer to the [HPC Archiving Wiki page](https://github.com/ruggleslab/.github/wiki/HPC‐archiving).
