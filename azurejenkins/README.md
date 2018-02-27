# Jenkins for Azure

This docker image;
- Is based on the Jenkins lts docker [image](https://hub.docker.com/r/jenkins/jenkins/)
- Comes with the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/overview?view=azure-cli-latest) installed
- Comes with [AZCopy](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-linux?toc=%2fazure%2fstorage%2fblobs%2ftoc.json) installed
- Has some commonly used Azure plugins installed

You can continue to add other Azure related plugins to the image by adding entries in the plugins.txt file.