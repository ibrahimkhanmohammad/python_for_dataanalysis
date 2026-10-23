# Python for Data Analysis

A structured collection of Python examples and practice exercises, organized as a learning journey toward data analysis. The repository starts with core Python and builds through functions, collections, object-oriented programming, and working with common file formats.

> The current materials focus on Python fundamentals. The repository topics also point toward tools such as NumPy, pandas, Matplotlib, and Seaborn; those libraries are not represented in the current lesson folders.

## Learning path

Work through the numbered folders in order:

| Folder | Topics |
| --- | --- |
| `001_variables and datatypes` | Variables, built-in data types, printing, conversion, and input |
| `002_escapseq and operators` | Escape sequences and arithmetic, comparison, logical, and membership operators |
| `003_conditional statements` | `if`/`elif`/`else`, nested conditions, ternary expressions, and a leap-year exercise |
| `004_while loops` | `while` loops and practice problems |
| `005_for loops` | `for` loops, reverse iteration, and practice problems |
| `006_break and continue` | Loop control statements |
| `007_nested loops` | Nested iteration and printed patterns, including Floyd's triangle |
| `008_functions` – `014_functions practise` | Defining and calling functions, parameters, return values, arguments, scope, lambdas, and exercises such as FizzBuzz |
| `015_lists` – `019_strings` | Lists, tuples, dictionaries, sets, strings, their methods, comprehensions, and exercises |
| `020_shallow copy deep copy` – `022_type annotations` | Copying and mutation, Python's object/reference behavior, and type annotations |
| `023_OOPs` | Classes, objects, attributes, encapsulation, inheritance, method resolution, and polymorphism |
| `024_File_handling` | Reading, writing, and appending files, with notebook examples and exercises |
| `025_JSON` | Loading and creating JSON, and reading and writing JSON files |
| `026_Date_time` | Date and time examples in a Jupyter notebook |

Folder and file names are kept as they appear in the repository. Some names contain spaces or typos.

## Getting started

You need Python 3 to run the `.py` examples. Most examples use the Python standard library, and the repository does not currently include a dependency or requirements file.

1. Clone the repository:

   ```bash
   git clone https://github.com/ibrahimkhanmohammad/python_for_dataanalysis.git
   cd python_for_dataanalysis
   ```

2. Run an example by passing its path to Python. Quote paths that contain spaces:

   ```bash
   python "001_variables and datatypes/001_dsa.py"
   ```

3. To work with the `.ipynb` lessons under `024_File_handling`, `025_JSON`, and `026_Date_time`, use Jupyter Notebook or JupyterLab. Install Jupyter in your preferred Python environment if it is not already available, then start it from the repository folder:

   ```bash
   jupyter notebook
   ```

## How to use the examples

- Start with the early numbered folders and move forward at your own pace.
- Read each short script, run it, and change the inputs to see how the output changes.
- Try the practice problems before looking at or editing their solutions.
- For notebooks, open the `.ipynb` file in Jupyter and run its cells in order.

## Contributing

Suggestions, corrections, and additional learning examples are welcome. Open an issue to discuss a change, or submit a pull request with a focused improvement.

## License

No license file is currently included. Until a license is added, the repository's contents are not explicitly granted for reuse, modification, or redistribution.
