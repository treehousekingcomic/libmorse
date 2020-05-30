Morse - a morse code library

Available Methods
- morsify
- demorse

# Instalation

- 1) Use pip: 
```
# Linux/macOS
python3 pip install libmorse

# Windows
py -3 pip install libmorse
``` 
| [Original GitHub Repo](https://github.com/shahprog/libmorse)
- 2) Or after cloning:
```
git clone https://github.com/treehousekingcomic/libmorse
```
You'll get this repo with libmorse

# Morsify Example:
```
import libmorse 
text = "example"
morse_code = libmorse.morsify(text)
```
# Demorse Example:
```
import libmorse
code = ". -..- .- -- .--. .-.. ."
text_from_morse_code = libmorse.demorse(code)
```

# Exeptions Raises:
For mordify()
- NoTextGiven (libmorse.NoTextGiven) | Paremeter text not passed
- EmptyStringGiven (libmorse.EmptyStringGiven) | Empty text string passed

For demorse()
- NoCodeGiven (libmorse.NoCodeGiven) | Paremeter code not passed
- EmptyCodeGiven (libmorse.EmptyCodeGiven) | Empty code string passed
