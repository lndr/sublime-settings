# sublime-settings
My Sublime Text settings.
## Usage
* Clone this repository into the Sublime Text `User` directory.
* Do not forget to populate the `Dictionaries` directory/submodule by calling:

        git submodule init
        git submodule update


## Additional configuration
* For LaTeX equation preview to work in Windows, make sure the system check shows nothing is missing, create a environment variable `GS_LIB` and set it to `C:\texlive\2022\tlpkg\tlgs\Resource\Init;C:\texlive\2022\tlpkg\tlgs\kanji` (modify according to the system configuration).
