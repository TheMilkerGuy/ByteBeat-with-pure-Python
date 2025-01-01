# PyByteBeat
Process your ByteBeat codes and output .wav files with Python

# How to use:
```python
from PyByteBeat import *
equation = "((t >> 10) & 42) * t"
seconds = 5
buffer = _buffer(equation, seconds)
output_file = "output.wav"
_wav(output_file, buffer, seconds)
```

# Modules used
There are no modules used, it's 100% pure Python (and Cowy love 😘)
