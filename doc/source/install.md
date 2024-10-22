# Installing

The latest release, including binary packages for Windows, macOS and Linux,
is available for download from [PyPI](http://pypi.python.org/pypi/PyWavelets/).
You can also find source releases at the [Releases Page](https://github.com/PyWavelets/pywt/releases).

You can install PyWavelets with::

```
pip install PyWavelets
```

Users of the `conda` may wish to obtain pre-built Windows, Intel Linux or
macOS/OSX binaries from the main or conda-forge channel::

```
conda install pywavelets
```

Several Linux distributions have their own packages for PyWavelets, but these
tend to be moderately out of date.  Query your Linux package manager tool for
`python-pywavelets`, `python-wavelets`, `python-pywt` or a similar
package name.


## Building from source

The most recent _development_ version can be found on GitHub at
https://github.com/PyWavelets/pywt.

If you want or need to install from source, you will need a working C compiler
(any common one will work) installed on your system.  Navigate to the
PyWavelets source code directory (containing `pyproject.toml.py`) and type::

```
pip install .
```

For the requirements needed to build from source are (Python, NumPy and Cython
minimum versions in particular), see `pyproject.toml`.

To run all the tests for PyWavelets, you will also need to install the
Matplotlib_ package. If SciPy_ is available, FFT-based continuous wavelet
transforms will use the FFT implementation from SciPy instead of NumPy.

!!! seealso

    The [Development guide](dev/index.md) section contains more information on
    building and installing from source code.
