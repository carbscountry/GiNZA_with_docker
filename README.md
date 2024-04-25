# GiNZA_with_docker

## エラー
```
 => ERROR [app 15/16] RUN pip install SudachiPy                                                                                        2.6s
------
 > [app 15/16] RUN pip install SudachiPy:
0.527 Collecting SudachiPy
0.649   Downloading SudachiPy-0.6.8.tar.gz (161 kB)
0.695      ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 161.9/161.9 kB 3.5 MB/s eta 0:00:00
0.725   Installing build dependencies: started
2.136   Installing build dependencies: finished with status 'done'
2.137   Getting requirements to build wheel: started
2.239   Getting requirements to build wheel: finished with status 'done'
2.240   Preparing metadata (pyproject.toml): started
2.370   Preparing metadata (pyproject.toml): finished with status 'done'
2.374 Building wheels for collected packages: SudachiPy
2.375   Building wheel for SudachiPy (pyproject.toml): started
2.474   Building wheel for SudachiPy (pyproject.toml): finished with status 'error'
2.478   error: subprocess-exited-with-error
2.478
2.478   × Building wheel for SudachiPy (pyproject.toml) did not run successfully.
2.478   │ exit code: 1
2.478   ╰─> [37 lines of output]
2.478       running bdist_wheel
2.478       running build
2.478       running build_py
2.478       creating build
2.478       creating build/lib.linux-aarch64-cpython-39
2.478       creating build/lib.linux-aarch64-cpython-39/sudachipy
2.478       copying py_src/sudachipy/config.py -> build/lib.linux-aarch64-cpython-39/sudachipy
2.478       copying py_src/sudachipy/errors.py -> build/lib.linux-aarch64-cpython-39/sudachipy
2.478       copying py_src/sudachipy/__init__.py -> build/lib.linux-aarch64-cpython-39/sudachipy
2.478       copying py_src/sudachipy/command_line.py -> build/lib.linux-aarch64-cpython-39/sudachipy
2.478       creating build/lib.linux-aarch64-cpython-39/sudachipy/dictionary
2.478       copying py_src/sudachipy/dictionary/__init__.py -> build/lib.linux-aarch64-cpython-39/sudachipy/dictionary
2.478       creating build/lib.linux-aarch64-cpython-39/sudachipy/tokenizer
2.478       copying py_src/sudachipy/tokenizer/__init__.py -> build/lib.linux-aarch64-cpython-39/sudachipy/tokenizer
2.478       creating build/lib.linux-aarch64-cpython-39/sudachipy/morphemelist
2.478       copying py_src/sudachipy/morphemelist/__init__.py -> build/lib.linux-aarch64-cpython-39/sudachipy/morphemelist
2.478       creating build/lib.linux-aarch64-cpython-39/sudachipy/morpheme
2.478       copying py_src/sudachipy/morpheme/__init__.py -> build/lib.linux-aarch64-cpython-39/sudachipy/morpheme
2.478       copying py_src/sudachipy/sudachipy.pyi -> build/lib.linux-aarch64-cpython-39/sudachipy
2.478       creating build/lib.linux-aarch64-cpython-39/sudachipy/resources
2.478       copying py_src/sudachipy/resources/sudachi.json -> build/lib.linux-aarch64-cpython-39/sudachipy/resources
2.478       copying py_src/sudachipy/resources/char.def -> build/lib.linux-aarch64-cpython-39/sudachipy/resources
2.478       copying py_src/sudachipy/resources/unk.def -> build/lib.linux-aarch64-cpython-39/sudachipy/resources
2.478       copying py_src/sudachipy/resources/rewrite.def -> build/lib.linux-aarch64-cpython-39/sudachipy/resources
2.478       running build_ext
2.478       running build_rust
2.478       error: can't find Rust compiler
2.478
2.478       If you are using an outdated pip version, it is possible a prebuilt wheel is available for this package but pip is not able to install from it. Installing from the wheel would avoid the need for a Rust compiler.
2.478
2.478       To update pip, run:
2.478
2.478           pip install --upgrade pip
2.478
2.478       and then retry package installation.
2.478
2.478       If you did intend to build this package from source, try installing a Rust compiler from your system package manager and ensure it is on the PATH during installation. Alternatively, rustup (available at https://rustup.rs) is the recommended way to download and update the Rust compiler toolchain.
2.478       [end of output]
2.478
2.478   note: This error originates from a subprocess, and is likely not a problem with pip.
2.479   ERROR: Failed building wheel for SudachiPy
2.479 Failed to build SudachiPy
2.479 ERROR: Could not build wheels for SudachiPy, which is required to install pyproject.toml-based projects
------
failed to solve: process "/bin/sh -c pip install SudachiPy" did not complete successfully: exit code: 1
```
