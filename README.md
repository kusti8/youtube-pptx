# Youtube-PPTX

The most efficient way to download youtube videos to your favorite video format, pptx.

## Install

Clone the repository.

**Using python3**, nstall all of the requirements in `requirements.txt` and make sure you [download chromedriver](https://chromedriver.storage.googleapis.com/index.html?path=2.42/).

Run the download.py script.

## Example

Run the `demo.sh` to try out a demo.

## Usage

```
usage: download.py [-h] [-d DURATION] [-t TEMP_DIR] url output

Download some youtube videos the long way.

positional arguments:
  url                   URL to download.
  output                Output pptx file

optional arguments:
  -h, --help            show this help message and exit
  -d DURATION, --duration DURATION
                        Optional seconds to download. If not specified,
                        download everything
  -t TEMP_DIR, --temp-dir TEMP_DIR
                        Temporary directory to hold the screenshots
```

## Disclaimer

This is entirely a joke. The code is bad. The documentation is bad. The entire idea is bad. I'm not liable for anything that happens.