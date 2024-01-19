# Colab File Downloader and Organizer

This repository contains a Google Colab script for downloading a ZIP file, extracting its contents, and moving them to a specified directory in Google Drive.

## How to Use

1. **Open the Notebook in Google Colab**: Upload the `.ipynb` file to Google Colab or open it directly if it's in your Google Drive.

2. **Set the Variables**: At the top of the script, set the following variables:
    - `DOWNLOAD_LINK`: URL of the file you want to download.
    - `ZIP_FILE_NAME`: What you want to name the downloaded ZIP file.
    - `TARGET_DIR`: Path to the directory in Google Drive where you want to store the extracted files.

3. **Run the Script**: Execute the cells in the Colab notebook. It will:
    - Mount your Google Drive.
    - Download the ZIP file from the provided link.
    - Extract the contents to a temporary directory.
    - Move the contents to the specified target directory in Google Drive.
    - Clean up the temporary files.

## Notes

- Ensure you have the necessary permissions for the Google Drive folder you're accessing.
- The script includes clean-up commands to remove temporary files. If you need to keep the ZIP file or the extracted contents in the Colab environment, you can comment out or remove the clean-up commands.

## Contributing

Feel free to fork this repository, make changes, and submit pull requests if you have suggestions or improvements.

---

## Author

- Sajith Dilan Lalinda
- [GitHub](https://github.com/SajithDL)
- [Discord](https://discord.com/invite/Ttw67ctVn5)

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

