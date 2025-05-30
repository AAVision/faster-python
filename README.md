# Faster-Python
A collection of Python packages built on top of Rust.

<p align="center">
  <img src="./logo.png"/>
</p>

## Contents
- Table of Content
    - [Core Tools & Infrastructure](#core-tools--infrastructure)
    - [Data & Scientific Computing](#data--scientific-computing)
    - [Utilities & Formatters](#utilities--formatters)
    - [Web & Networking](#web--networking)
    - [Cryptography & Security](#cryptography--security)
    - [Embedding & Interop](#embedding--interop)
    - [Emerging Projects](#emerging-projects)
    - [Database](#database)
    - [Learning](#learning)

## Core Tools & Infrastructure

_Tools for help building projects._
- [uv](https://github.com/astral-sh/uv) - An extremely fast Python package and project manager, written in Rust.
- [ty](https://github.com/astral-sh/ty) - An extremely fast Python type checker and language server, written in Rust. 
- [ruff](https://github.com/astral-sh/ruff) - An extremely fast Python linter and code formatter, written in Rust.
- [maturin](https://github.com/PyO3/maturin) - Build and publish crates with pyo3, cffi and uniffi bindings as well as rust binaries as python packages.
- [PyO3](https://github.com/PyO3/pyo3) - Rust bindings for Python, including tools for creating native Python extension modules. Running and interacting with Python code from a Rust binary is also supported.
- [RustPython](https://github.com/RustPython/RustPython) - A Python Interpreter written in Rust.
- [Huak](https://github.com/cnpryer/huak) - My experimental Python package manager.
- [setuptools-rust](https://github.com/PyO3/setuptools-rust) - Setuptools plugin for Rust support.
- [maturin-action](https://github.com/PyO3/maturin-action) - GitHub Action to install and run a custom maturin command with built-in support for cross compilation.
- [python3-dll-a](https://github.com/PyO3/python3-dll-a) - Standalone python3.dll import library generator.
- [python-pkginfo-rs](https://github.com/PyO3/python-pkginfo-rs) - Parse Python package metadata from sdist and bdists and etc.
- [maturin-import-hook](https://github.com/PyO3/maturin-import-hook) - Import hook for maturin.
- [datafusion-ballista](https://github.com/apache/datafusion-ballista) - Apache DataFusion Ballista Distributed Query Engine.

**[⬆ back to top](#contents)**

## Data & Scientific Computing

_Tools for building scientific projects._
- [polars](https://github.com/pola-rs/polars) - Dataframes powered by a multithreaded, vectorized query engine, written in Rust.
- [polars-lts-cpu](https://pypi.org/project/polars-lts-cpu) - Polars is a DataFrame interface on top of an OLAP Query Engine implemented in Rust using Apache Arrow Columnar Format as the memory model.
- [connector-x](https://github.com/sfu-db/connector-x) - Fastest library to load data from DB to DataFrames in Rust and Python.
- [pydantic-core](https://github.com/pydantic/pydantic-core) - Core validation logic for pydantic written in rust.
- [rust-numpy](https://github.com/PyO3/rust-numpy) - Rust bindings for the NumPy C-API.
- [feos](https://github.com/feos-org/feos) - A Framework for Equations of State and Classical Density Functional Theory.
- [delta-rs](https://github.com/delta-io/delta-rs) - A native Rust library for Delta Lake, with bindings into Python.
- [forust](https://github.com/jinlow/forust) - A lightweight gradient boosted decision tree package.
- [mocpy](https://github.com/cds-astro/mocpy) - Python library to easily create and manipulate MOCs (Multi-Order Coverage maps).
- [arro3](https://github.com/kylebarron/arro3) - A minimal Python library for Apache Arrow, connecting to the Rust arrow crate.
- [parquet2](https://github.com/jorgecarleitao/parquet2) - Fastest and safest Rust implementation of parquet. `unsafe` free. Integration-tested against pyarrow.
- [rustworkx](https://github.com/Qiskit/rustworkx) - A high performance Python graph library implemented in Rust.

**[⬆ back to top](#contents)**

## Utilities & Formatters

_Tools to help you in your projects._
- [orjson](https://github.com/ijl/orjson) - Fast, correct Python JSON library supporting dataclasses, datetimes, and numpy.
- [pixi](https://github.com/prefix-dev/pixi) - Package management made easy.
- [tiktoken](https://github.com/openai/tiktoken) - tiktoken is a fast BPE tokeniser for use with OpenAI's models.
- [tokenizers](https://github.com/huggingface/tokenizers) - 💥 Fast State-of-the-Art Tokenizers optimized for Research and Production.
- [jsonschema](https://github.com/Stranger6667/jsonschema) - A high-performance JSON Schema validator for Rust.
- [html2text-rs](https://github.com/deedy5/html2text_rs) - Python library for converting HTML to markup or plain text.
- [tzfpy](https://github.com/ringsaturn/tzfpy) - Probably the fastest Python package to convert longitude/latitude to timezone name.
- [pyo3-built](https://github.com/PyO3/pyo3-built) - Expose build variables obtained with built as a PyDict.
- [pyo3-async-runtimes](https://github.com/PyO3/pyo3-async-runtimes) - PyO3-based bridges between Python and Rust async runtimes.
- [pytantivy](https://github.com/quickwit-oss/tantivy-py) - Python bindings for Tantivy.
- [hyperjson](https://github.com/mre/hyperjson) - 🐍 A hyper-fast Python module for reading/writing JSON data using Rust's serde-json.
- [pyo3-log](https://github.com/vorner/pyo3-log) - Logging bridge from pyo3 native extension to python.
- [python-zstandard](https://github.com/indygreg/python-zstandard) - Python bindings to the Zstandard (zstd) compression library.
- [molpipx](https://github.com/ChemAI-Lab/molpipx/) - Differentiable version of Permutationally Invariant Polynomial (PIP) models in JAX and Rust. 
- [PyOxidizer](https://github.com/indygreg/PyOxidizer) - A modern Python application packaging and distribution tool.
- [pylyzer](https://github.com/mtshiba/pylyzer) - A fast, feature-rich static code analyzer & language server for Python.
- [rusty-logger](https://github.com/demml/rusty-logger) - Fast Python logging library written in Rust, ready for production.
- [py-spy](https://github.com/benfred/py-spy) -  Sampling profiler for Python programs.

**[⬆ back to top](#contents)**

## Web & Networking

_Tools for building networking projects._
- [robyn](https://github.com/facebookexperimental/Robyn) - Robyn is a Super Fast Async Python Web Framework with a Rust runtime.
- [granian](https://github.com/emmett-framework/granian) - A Rust HTTP server for Python applications.
- [primp](https://github.com/deedy5/primp) - 🪞PRIMP (Python Requests IMPersonate). The fastest python HTTP client that can impersonate web browsers.
- [utiles](https://github.com/jessekrubin/utiles) - utiles = utils & (web-map-)tiles w/ (rs & pyo3).
- [css-inline](https://github.com/Stranger6667/css-inline) - Python library to easily create and manipulate MOCs (Multi-Order Coverage maps).

**[⬆ back to top](#contents)**

## Cryptography & Security

_Tools for securing your projects._
- [cryptography](https://github.com/pyca/cryptography) - cryptography is a package designed to expose cryptographic primitives and recipes to Python developers.
- [johnnycanencrypt](https://github.com/kushaldas/johnnycanencrypt) - Python module for OpenPGP written in Rust.
- [fastbloom](https://github.com/yankun1992/fastbloom) - A fast bloom filter implemented by Rust for Python! 10x faster than pybloom.
- [opendal](https://github.com/apache/opendal) - Apache OpenDAL: One Layer, All Storage.

**[⬆ back to top](#contents)**

## Embedding & Interop

_Tools to help you building embedding projects._
- [inline-python](https://github.com/m-ou-se/inline-python) - Inline Python code directly in your Rust code.
- [rustimport](https://github.com/mityax/rustimport) - Import Rust source files directly from Python!

**[⬆ back to top](#contents)**

## Emerging Projects

_Tools to help you building emerging projects._
- [blake3-py](https://github.com/oconnor663/blake3-py) - Python bindings for the BLAKE3 cryptographic hash function.
- [bed-reader](https://github.com/fastlmm/bed-reader) - A library for easy, fast, and efficient reading & writing of PLINK Bed files.
- [cellular_raza](https://github.com/jonaspleyer/cellular_raza) - Cellular agent-based modeling from a clean slate.
- [rustimport](https://github.com/attack68/rateslib) - A fixed income library for pricing bonds and bond futures, and derivatives such as interest rate swaps (IRS), cross-currency swaps (XCS) and FX swaps. Contains tools for full Curveset construction with market standard optimisers and automatic differentiaton (AD) and risk sensitivity calculations including delta and cross-gamma.

**[⬆ back to top](#contents)**

## Database

_Tools for building database projects._

- [psqlpy](https://github.com/psqlpy-python/psqlpy) - Asynchronous Python PostgreSQL driver written in Rust.
- [Raphtory](https://github.com/Pometry/Raphtory) - Scalable graph analytics database powered by a multithreaded, vectorized temporal engine, written in Rust.
- [Daft](https://github.com/Eventual-Inc/Daft) - Distributed data engine for Python/SQL designed for the cloud, powered by Rust.

**[⬆ back to top](#contents)**

## Learning
_Tools to learn binding Rust with Python._

- [rust-python-example](https://github.com/rochacbruno/rust-python-example) -  Example of using Rust to Extend Python.
- [python2rust](https://github.com/bedroombuilds/python2rust) - Code for Youtube series introducing Rust to Python programmers.

**[⬆ back to top](#contents)**
---

## LICENSE :balance_scale:

This project is licensed under the MIT License. See the [LICENSE](https://github.com/AAVision/faster-python/blob/main/LICENSE) file for details.