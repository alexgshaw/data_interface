# data_interface

data_interface is a Python module used to visualize data and molecular structures.
Inspired by Dr. Sandip De's Interactive Sketchmap Visualizer

## Usage

```python
import pandas
import data_interface

my_dataframe = pandas.read_csv('example.csv')
structure_list = my_dataframe['structure path'].tolist()

data_interface.visualize(data_df=my_dataframe, structure_filenames=structure_list)
```

## Dependencies

The following python libraries are required:

```bash
pip install numpy
pip install pandas
pip install ase
pip install bokeh
pip install colorcet
```

For molecular visualization to work, the following file and folder must be in
the working directory:

```
jsmol.min.js
j2s
```

Both the file and the folder are found in the jsmol folder after downloading
Jmol at

```
https://sourceforge.net/projects/jmol/files/Jmol/
```

## Support

Feel free to reach out at
```
ashaw8@byu.edu
```
if you have any questions.
