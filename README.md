# The Personal Blog of Alan Grgic

[![AppVeyor](https://img.shields.io/appveyor/ci/alanag13/alanag13-github-io/source.svg)]()

## Running the Blog locally (Windows required)
- Install the latest version of [Wyam](https://github.com/Wyamio/Wyam/releases)
- Add the path to Wyam.exe to your system PATH environment variable
- Execute the following in your favorite command line client:

````
$ git clone https://github.com/alanag13/alanag13.github.io
$ cd alanag13.github.io
$ wyam -r Blog -t CleanBlog
````
Then navigate your browser to `http://localhost:5080`.
