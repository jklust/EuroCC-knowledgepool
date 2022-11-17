# Basics of HPC
HPC (High Performance Computing) consists in clustering together a large amount of computing hardware, so that a large number of operations can be executed at once. A supercomputer consists of different types of hardware. In general, hardware is structured in this hierarchy:

- **CPU**, the unit that can execute a single sequence of instructions. A CPU can consists of multiple cores, so that multiple chains of instructions can be executed independently.
- **Node**, one of the computers that are installed into an HPC system.
- **Cluster**, a group of nodes that are connected together and therefore able to communicate and work together on a single task.

Moreover, a storage section connected all with one or more types of storage hardware is present in an HPC.
A **node** can consists of only one or more CPUs and some RAM memory.  There are other types of nodes containing different hardware combinations. The most common hardware that can be found in a node beyond RAM and CPUs is:

- **GPU**, a graphics card. This type of hardware was used for gaming and graphics software, but it has build up a lot of computational power capable of hundreds of parallel processes. This is particularly useful for specific types of linear algebra operations that require the same task to be performed repeatedly. Nvidia and AMD are the main GPU producers.
- **FPGA**, a programmable piece of hardware that can do specific operations many times faster than the other available solutions. It can be used to accelerate specific processes that are usually carried out using CPUs.

## Access to HPC
HPC systems allow many users to log into the system at the same time and use part of those resources, usually after they are assigned by an administrator to each user (so that using more resources than assigned will result in stopping whatever software is executed at that time). In Denmark, you have two ways of logging into an HPC system: the first is through a user-friendly interactive interface ([DeiC facility for interactive HPC](https://interactivehpc.dk/#/)), the second is through a classic command line, that requires some knowledge of the UNIX shell language ([here is a good introduction to the Linux shell](https://www.learnenough.com/command-line-tutorial/basics)). 

Usually, a user can access to a so-called *login node*: this has few computational resources allowing the user to login and perform basic operations (small code testing, file management). A user can get assigned 

- a number of CPUs and eventually GPUs/FPGAs/...
- an amount of RAM
- a quantity of storage
- an amount of total time those resources need be used

When using DeiC's facility for interactive HPC, the user asks for resources directly through the dashboard once logged in. You will have the chance to exchange messages with the front office responsible for resource assignment, in case your resource demand is too low or too high. However, we suggest to contact first your  [local front office](https://www.deic.dk/en/Front-Office) or <eurocc@listserv.deic.dk> (HPC facilitation responsible) to get help in submitting a request to obtain resources. For using non-interactive HPCs, you will need to contact the local front office and discuss the possibility of getting resources.

## What can I use HPC for

HPC systems have a large amount of computational power, but this does not mean they are only to be used for large scale projects. You can indeed request entire nodes as well as a single CPU with some GB of RAM. The Danish HPCs are available for any academic application:

 - research projects
 - student projects
 - student exercises in classroom teaching/lecturing

Students are not authorized to ask for resources. It will be responsibility of the lecturer/professor to obtain resources through the front office or facilitator. Any student can then be invited/authorized in accessing the project whose resources have been allocated to. 

Heavy focus of the Danish HPC ecosystem is on teaching and the training of new users, so applications for resources related to courses and students projects are very much welcomed.


## Advantages of using HPC

Using HPC offers many advantages, not only limited to the resources available. In general, using HPC makes the difference in relation to

- getting a large amount of resources at a cost much lower than buying/owning your own powerful workstation
- sharing data and settings with other people in collaborative projects
- using software that is already installed or manageable through a package software: save time instead of configuring and adjusting things on your computer! This is an important aspect especially in teaching, where students have different OS, software versions, and problems with packages.
- getting technical support from the help desk without being on your own
- convenience in the sense that computations do not occupy resources on the user's personal computer that is then free to perform other tasks.