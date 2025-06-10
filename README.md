> [!IMPORTANT]
This is a fork of [the Gray Paper](https://github.com/gavofyork/graypaper) repo that automatically
renders the `main` branch as PDF.  
> You can download the PDFs them from the
[CI](https://github.com/JamBrains/graypaper/actions/workflows/render-latex.yaml) artifacts of the last run. They are displayed on [jamcha.in](https://jamcha.in/spec).

# Gray Paper: The JAM Specification

The description and formal specification of the Jam protocol, a potential successor to the Polkadot Relay chain.

Build with xelatex.

https://graypaper.com/

# Setup
## Pre-commit
Install the [`pre-commit` CLI tool](https://pre-commit.com/), available via brew on macOS:
```sh
brew install pre-commit
```

Then install the hook:
```sh
pre-commit install
```