# TODO
Taskwarrior wrapper for running task managment in a local directoy to a project. Tasks are isolated by project and travel with the project git.


# Install
1. nstall task warrior
```shell
	sudo port install task
```

2. Clone the git
```shell
	git clone https://github.com/drclaw1394/todo.git
```
3. Copy the todo script to each of the local directories you would like to use it
```shell
	cp todo/todo path/to/my/project
```

4. Change into the project directory and run
```
	cd path/to/my/project
	./todo
```


# Why?
- I was tired of typing the project name for each of the tasks I was added to my global task warrior
- Having a project local data set means the tasks travel with the project (if you add it to the project git for example). This gives task tracking where ever you work on the project.
- Provides basic multiuser task managment in the project
