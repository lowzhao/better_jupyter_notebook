# Better Jupyter Notebook UI

> _This ui change is incomplete._

![Screen shot](https://raw.githubusercontent.com/lowzhao/better_jupyter_notebook/master/Screenshot.png)

just: 
```
git clone https://github.com/lowzhao/better_jupyter_notebook.git;
cd better_jupyter_notebook;
mkdir -p ~/.jupyter/custom;
cp -i ./custom.css ~/.jupyter/custom;
jupyter notebook;
```

revert:
```
rm -i ~/.jupyter/custom/custom.css;
```

_Warning some important information might be removed._

### CREDITS
- Fonts: 
  - [`Fira Code`](https://github.com/tonsky/FiraCode)
  - [`Lato`](https://fonts.google.com/specimen/Lato)
- Notebook Example:
  - [`Machine Learning Notebook`](https://github.com/masinoa/machine_learning)
