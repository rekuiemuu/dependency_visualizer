

---

# Dependency Visualizer

## What is it?
Dependency Visualizer is a command-line tool for analyzing and visualizing the dependency graph of a Git repository. It traces file modification history and generates a DOT format graph for clear visualization with Graphviz.

## Flags
**Command-line flags are set:**
- Path to the Git repository.
- Specific file hash to analyze.
- Path to the output file for the DOT representation.

## Example

```
python src/main.py --repo_path /path/to/repo --file_hash 0b35cc10941dae14e12271aa380c367436c79d05 --output_path output.dot
```

## Downloading Python packages
You will most likely need to install the following libraries:
- [GitPython](https://pypi.org/project/GitPython/)
- [Graphviz](https://pypi.org/project/graphviz/)

Install the required packages using pip:

```
pip install GitPython
```
```
pip install graphviz
```

## If you don't have pip installed
If you don't have pip installed, follow these steps:

**Download PIP get-pip.py**
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```
**Installing PIP on Windows**
```
python get-pip.py
```
**Verify Installation**
```
python -m pip help
```

For more information, visit this [site](https://phoenixnap.com/kb/install-pip-windows).

---
