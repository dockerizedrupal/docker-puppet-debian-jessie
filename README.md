docker-puppet
============

Build the image
-----------------

`# docker build -t puppet http://git.simpledrupalcloud.com/viljaste/docker-puppet.git`

Push the image to private docker registry
---------------------

`# docker tag puppet docker-registry.simpledrupalcloud.com/puppet`

`# docker push docker-registry.simpledrupalcloud.com/puppet`

Run as container
---------------

`# docker run --name puppet -t -i puppet /bin/bash`