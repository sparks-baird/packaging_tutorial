# Example Package
This is a simple example package following the tutorial in https://packaging.python.org/tutorials/packaging-projects. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.

## Creating an Environment with Commands
https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands

```python
conda create -n packaging_tutorial python
```

You can verify that the python executable points to the conda environment via (Windows):
```bash
where python
```
> ```bash
> C:\Users\sterg\anaconda3\envs\packaging_tutorial\python.exe
> C:\Users\sterg\AppData\Local\Programs\Python\Python39\python.exe
> C:\Users\sterg\AppData\Local\Microsoft\WindowsApps\python.exe
> ```

Notice the anaconda3 path at the top of the list (i.e. first one to be used).

```python
python -m pip install --upgrade build
```
