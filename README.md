# CONDA Cheatsheet ✨
A curated list of the most important 'conda' commands.

### update conda in your default environment 
```
$ conda upgrade conda
$ conda upgrade --all
```

### create a new environment with conda
```
$ conda create -n [my-env-name]
$ conda create -n [my-env-name] python=[python-version]
```

### activate the environment you created
```
$ source activate [my-env-name]
```

### deactivate the environment you created
```
$ conda deactivate
```

### take a look at the environment you created
```
$ conda info
$ conda list
```

### install a package with conda and verify it's installed
```
$ conda install numpy
$ conda list
```

### take a look at the list of environments you currently have
```
$ conda info -e
```

### remove an environment
```
$ conda env remove --name [my-env-name]
```

### freeze installed packages in requirements.txt
```
$ conda list --export > requirements.txt 
```

### create environment file 
```
$ conda env export > environment.yml
```

### update your environment according to the yaml file
```
$ conda activate [my-env-name]
$ conda env update --file local.yml
```
