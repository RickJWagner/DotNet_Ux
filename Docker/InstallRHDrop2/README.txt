May need to disable selinux on host machine (not docker container)

Copied 'runtime requirements' libs from Drop1, installed in Dockerfile.  Also copied 'demo/samples' from Drop1.

Once on the machine:
$ scl --list
> rh-dotnet-core10
$ scl enable rh-dotnet-core10 bash
$ dotnet new
> (Makes a sample project)
