# EDH Remixer

## Overview

When recycling EDH decks into new ones, it can be challenging to efficiently identify which cards can be reused, which cards should be removed, and which new cards need to be acquired. The EDH Remixer program is designed to streamline this process, helping users quickly remix their decks with ease.

## How to Use

### Download and Setup

1. Download the executable from the [latest release](#) as a ZIP file.
2. Unzip the contents into the "Documents" folder within a sub-folder named "EDH Remixer."

Your folder structure should resemble the following:

```
EDH Remixer/
|-- _internal/
|-- source/
|   |-- example_deck_source.txt
|-- target/
|   |-- example_deck_target.txt
|-- app.exe
|-- buy.txt
|-- output.xlsx
```

### Uploading Decks

1. In the "source" and "target" folders, upload the content of the decks in a .txt file. An example is already provided in both folders.
2. You can easily export your decks as text files from platforms like Moxfield or EDHREC.

### Running the Program

1. Launch the `app.exe` executable.
2. The program will process the decks and generate two files:

   - **buy.txt:** A list of cards you need to acquire.
   - **output.xlsx:** An Excel file displaying the status of each card.

## Example

To illustrate, let's say you have two decks: one in the "source" folder and another in the "target" folder. Running the program will provide you with a clear list of cards to acquire and an Excel file detailing the status of each card.

## Dependencies

The EDH Remixer is a standalone executable and does not require any additional dependencies.

## Support

If you encounter any issues or have suggestions for improvement, please open an [issue](#) on the GitHub repository.

## Contributing

We welcome contributions! Feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE.md).

---

Happy deck remixing!
