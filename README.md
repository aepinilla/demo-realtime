[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![codecov](https://codecov.io/gh/mscheltienne/demo-realtime/branch/main/graph/badge.svg?token=EN5L5ZS6HG)](https://codecov.io/gh/mscheltienne/demo-realtime)
[![tests](https://github.com/mscheltienne/demo-realtime/actions/workflows/pytest.yml/badge.svg?branch=main)](https://github.com/mscheltienne/demo-realtime/actions/workflows/pytest.yml)
[![build](https://github.com/mscheltienne/demo-realtime/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/mscheltienne/demo-realtime/actions/workflows/build.yml)

# Real-time demo using LSL

This repository can be installed via `pip` with `pip install git+https://github.com/mscheltienne/demo-realtime`.

It implements simple real-time demonstration using [BSL](https://bsl-tools.github.io/).

# Example

```
from demo_realtime import nfb_alpha_power_occipital

stream_name: str = "My LSL Stream"
nfb_alpha_power_occipital(stream_name)
```
