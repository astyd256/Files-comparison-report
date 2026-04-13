# Files comparison report

This Python script takes two paths to folders (A and B) and compares file names inside them, then it writes and excel report:


|    |    |
| --- | --- |
| filename 1 from A   | filename 1 from B   |
| filename 2 from A    |     |
| filename 3 from A    |     |
|     | filename 4 from B   |
|     | filename 5 from B   |

First will always be the matched filenames, then, the first folder names (A), then the second (B)

## Dependencies
- `openpyxl` - Library for working with Excel
## Usage
1. Set the values for `folder_path1`, `folder_path2`, and `output_file` variables according to your requirements.
2. Ensure that the `openpyxl` library is installed (`pip install openpyxl` if not already installed).
3. Run the script.
4. The merged list of file names will be written to the specified Excel file.

*Note: Ensure that the folders and files exist and the script has the necessary permissions to read from the folders and write to the output file.*

