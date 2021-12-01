# sample script

docker run -it -v "$PWD/work":/work --cap-add=SYS_PTRACE --security-opt="seccomp=unconfined" exploit
