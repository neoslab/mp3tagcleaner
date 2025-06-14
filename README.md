# MP3TagCleaner — Year Tags Remover

**MP3TagCleaner** remove unwanted "year" (`date`) tags from MP3 files using a simple Python utility powered by Mutagen. Clean individual files or entire folders with optional verbose logging.

* * *

## Features

- Remove `date` (year) tag from MP3 metadata
- Clean individual MP3 files or entire directories
- Optional verbose logging
- Built using `mutagen.easyid3` and `mutagen.id3`
- Lightweight and dependency-light

* * *

### Requirements

- Python 3.6+
- [mutagen](https://pypi.org/project/mutagen/)

Install Mutagen with pip:

```bash
pip install mutagen
````

* * *

### Usage

#### 1. Clone the Repository

```bash
git clone https://github.com/neoslab/mp3tagcleaner
cd mp3tagcleaner
```

#### 2. Run the Script

```bash
python mp3tagcleaner.py
```

#### 3. Example: Clean a Single File

```python
cleaner.cleanfromfile(r"C:\Users\YourName\Music\song.mp3")
```

### 4. Example: Clean All MP3s in a Folder

```python
cleaner.cleanfromfolder(r"C:\Users\YourName\Music")
```

* * *

### File Structure

```
mp3tagcleaner.py        # Main script containing MP3TagCleaner class
README.md               # Project documentation
```

* * *

### Example Output

```text
[OK] Removed year tag from: C:\Users\YourName\Music\song1.mp3
[SKIP] No year tag found in: C:\Users\YourName\Music\song2.mp3
[ERROR] Cannot process C:\Users\YourName\Music\badfile.mp3: ...
```

* * *

### Why Use It?

* Eliminate unnecessary or incorrect `year` metadata from MP3s
* Standardize your media files for automation tools or streaming
* Quickly clean up messy downloads and audio archives

* * *

### License

This script is open source under the [MIT License](LICENSE).

* * *

### Contact

Created by [@neoslab](https://neoslab.com/contact/) – Feel free to reach out!