May need to disable selinux on host machine (not docker container)

The Web demos can be run if the port on the machine is mapped to the host machine's port:
docker run -i -t -p 5004:5004  ricks_dotnet_rh1_2 /bin/bash

You can run as a normal user by using 'su - rick' to become that user, then do the dnu restore, dnx web.
