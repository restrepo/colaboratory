# Colaboratory
## How to use it
Upload a jupyter notebook into Google Drive and try to open it. Choose "Open with colaboratory" to open the file in Gogle Drive. The first time may be is necessary to install the [extension](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo?hl=en). In Google Drive settings, choose Manage Apps and check the "Use by Dafault" Option of Colaboratory

## To edit a GitHub notebook directly in collaboratory
1. Change the first part: `https://github.com/` of the GitHub notebook visualization link: 
```
https://github.com/user/repo/blob/master/file.ipynb 
```
by: `https://colab.research.google.com/github/`, so that the colaboratory edit link look like this one:
```
https://colab.research.google.com/github/user/repo/blob/master/file.ipynb 
```
Example:

https://colab.research.google.com/github/restrepo/colaboratory/blob/master/example.ipynb 

To save back the notebook into GitHub, use: `File → Save a copy in GitHub`

## To create a new notebook from GitHub
1. [Crates a new file in GitHub](https://help.github.com/articles/creating-new-files/) with file extension ipynb
2. Copy and paste the contents of an empty Python 3 notebook: https://raw.githubusercontent.com/restrepo/colaboratory/master/blank.json
3. Make the commit

## To use `matplotlib` default style
Colaboratory change the default style of `matplotlib`. To recover the defaul style use:
```python
import matplotlib.style
import matplotlib as mpl
mpl.style.use('default') # or 'classic'
```
Check [Style reference](https://matplotlib.org/gallery/style_sheets/style_sheets_reference.html)
