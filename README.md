# RedHat-Openshift
All About Red Hat OpenShift

Minimum requirements to install OpenShift on a laptop are 16GB of RAM and 4CPU

I am using it on an AWS EC2 instance

Steps to Install:
1: Download OC for Windows        wget https://mirror.openshift.com/pub/openshift-v4/clients/ocp/latest/openshift-client-linux.tar.gz
2: Unzip the file                 tar -xvf openshift-client-linux.tar.gz
3: move files /usr/local/bin/     sudo mv oc kubectl /usr/local/bin/
4: Verify the version             oc version
5: log in with your tokens        oc login --token=<token> --server=<server-URL>


END-TO-END OPENSHIFT PROJECT
