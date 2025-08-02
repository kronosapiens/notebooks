# notebooks
Notebooks for data analysis in Python

## Getting Started

This project uses [uv](https://docs.astral.sh/uv/) for dependency management.

### Prerequisites

Make sure you have `uv` installed. If not, install it:

```bash
# On macOS/Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

# Or with pip
pip install uv
```

### Setup

1. Install the project dependencies:
   ```bash
   uv sync
   ```

2. Start JupyterLab:
   ```bash
   uv run jupyter lab
   ```

This will start the Jupyter server and open your browser to the JupyterLab interface where you can access your notebooks.

### Dependencies

This project includes the following key packages:
- **JupyterLab** - Interactive notebook environment
- **NumPy & Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **Rich** - Enhanced terminal output
- **OpenPyXL** - Excel file support

### Adding New Dependencies

To add new packages:
```bash
uv add package-name
```

To add development dependencies:
```bash
uv add --dev package-name
```
