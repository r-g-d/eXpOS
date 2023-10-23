![expos](http://exposnitc.github.io/img/logo.png)

# EXPOS

EXPOS Project is done as a part of Operating System Lab in 5th SEM in NITC.
Roadmap to follow for this Project - [Roadmap](http://exposnitc.github.io/Roadmap.html)

EXPOS is an experimental operating system that supports multiuser, virtual memory functionality, some basic file system operations, forking process, etc.


#### 1. The following figure illustrates the OS development environment from an OS programmer's viewpoint.

![](http://exposnitc.github.io/img/Kernel_Module.png)

#### 2. The following figure illustrates the development environment from an application programmer's perspective.

![](http://exposnitc.github.io/img/Applicn_Pgm.png)

### Final System

![finalSystem](http://exposnitc.github.io/img/User_View.png)

#### The following figure gives a high level picture of the OS that you will build by the end of the project.

![](http://exposnitc.github.io/img/os-design/high_level_design.png)


## How to run XSM machine

1. Install this repository.
2. Name it to myexpos.
3. Save this in $HOME directory.
4. Run the following commands.

The final code for EXPOS is in ```myexpos``` for running xsm machine use the following command:-

```bash
cd $HOME/myexpos/xfs-interface
./xfs-interface < run.dat
cd $HOME/myexpos/xsm
./xsm --timer 200
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

### Note :-
In some batch files if ```/home/hitesh/``` is written when specifying path please change it to ```$HOME/```
