# go-docker

## Elements of a container and how containerization work

-   Containers rely on three main things
    -   namespaces: which provide isolation for multiple containers (PID, NET, MNT, UTS, IPC, USER)
    -   cgroups: collect processes and task ids together and limit them (resource sharing)
    -   layered filesystems: optimizes the calls for copying containers
