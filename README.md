# Informatics_573 Script

## Identifying Information
  Programmer: Jason Moore
- Language: Bash Script
- Version: 1.0
- Date Submitted: 09/15/2024
- Description: This script navigates to the user's home directory, creates a directory titled "Informatics_573", downloads all secondary assemblies for human chromosome 1 from the UCSC Genome browser, unzips the downloaded files, and generates a summary file with detailed information about the files.

## Required Files
- None: All necessary files are downloaded by the script.

## Required Libraries/Packages/Software
- wget: For downloading files from the internet.
- gunzip: For unzipping `.gz` files.
- bash: The script is written in Bash and requires a Bash-compatible shell to run.

## Instructions for Running the Script
1. **Download the Script**: Save the script with a `.sh` extension.
2. **Make the Script Executable**: Open a terminal and run the following command:
    ```sh
    chmod +x script_name.sh
    ```
3. **Run the Script**: Execute the script by running:
    ```sh
    ./script_name.sh
    ```
4. **Verify Output**: Check the `Informatics_573` directory in your home directory for the `data_summary.txt` file and the downloaded chromosome 1 assemblies.

## Files Created During Script Execution
- **Informatics_573**: Directory created in the user's home directory.
- **data_summary.txt**: File containing detailed information about the downloaded chromosome 1 assemblies, including file names, sizes, permissions, the first 10 lines of each file, and the total number of lines in each file.
- **chr1_* files**: Downloaded and unzipped chromosome 1 assemblies from the UCSC Genome browser.

Feel free to reach out if you have any questions or need further assistance!
