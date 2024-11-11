# sigconverter.io 🔄

[![Website](https://img.shields.io/badge/Website-sigconverter.io-blue)](https://sigconverter.io)

Welcome to sigconverter.io, a user-friendly converter for Sigma rules. This project is designed to keep in sync with the pySigma project's backends. Inspired by [uncoder.io](https://uncoder.io), it aims to provide an easy-to-use interface for converting Sigma rules.

## 🌟 Key Features

- Easy-to-use interface for Sigma rule conversion
- Supports multiple backends through pySigma
- Continuously updated to stay in sync with pySigma
- Multiple Sigma versions support through isolated environments

## 🚀 Getting Started

### Local Development:

```bash
# Install Poetry if you haven't already
curl -sSL https://install.python-poetry.org | python3 -

# Clone the repository
git clone https://github.com/magicsword-io/sigconverter.io.git
cd sigconverter.io

# Install dependencies
poetry install

# Setup Sigma versions
poetry run python app/setup.py

# Run the application
poetry run python app/main.py
```

### With Docker:

```bash
# Build the image
docker build -t sigconverter.io .

# Run the container
docker run -d -p 8000:8000 sigconverter.io
```

Visit the live instance at [https://sigconverter.io](https://sigconverter.io) or locally at [http://localhost:8000](http://localhost:8000).

## 📞 Support

For bugs or feature requests, please use the [GitHub issue tracker](https://github.com/magicsword-io/sigconverter.io/issues).

## 🤝 Contributing

We welcome contributions from the community. If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create a new branch for your changes
3. Commit your changes to your branch
4. Push your changes to your fork
5. Open a Pull Request against the upstream repository

## 📜 Contributors

- [Jose Enrique Hernandez](https://twitter.com/_josehelps)
- [Nasreddine Bencherchali](https://twitter.com/nas_bench)
- [Kostas](https://twitter.com/Kostastsale)
- [Michael Haag](https://twitter.com/M_haggis)
- [Julian Ortel](https://twitter.com/m3nixx)

## 📝 Credits

This project was completely based on [sigmaio by M3NIX](https://github.com/M3NIX/sigmaio). Special thanks to the author [M3NIX](https://twitter.com/m3nixx).
