# spinnaker-clouddriver

github addr [https://github.com/kubernets/spinnaker-clouddriver](https://github.com/kubernets/spinnaker-clouddriver)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/spinnaker-clouddriver/raw/master/get-spinnaker-clouddriver-image.sh

## Arch and Version

- [**all** 2.0.0-20180221152902](https://hub.docker.com/r/kubernets/spinnaker-clouddriver)

    > docker pull kubernets/spinnaker-clouddriver:2.0.0-20180221152902

    > docker tag kubernets/spinnaker-clouddriver:2.0.0-20180221152902 gcr.io/spinnaker-marketplace/clouddriver:2.0.0-20180221152902 

    > docker rmi kubernets/spinnaker-clouddriver:2.0.0-20180221152902

- [**all** 3.4.2-20180828182842](https://hub.docker.com/r/kubernets/spinnaker-clouddriver)

    > docker pull kubernets/spinnaker-clouddriver:3.4.2-20180828182842

    > docker tag kubernets/spinnaker-clouddriver:3.4.2-20180828182842 gcr.io/spinnaker-marketplace/clouddriver:3.4.2-20180828182842 

    > docker rmi kubernets/spinnaker-clouddriver:3.4.2-20180828182842
