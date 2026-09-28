# cifar10
CIFAR-10 Dataset downloadable here instead of the slow U of T servers.

Command to download:

mkdir cifar10 && cd cifar10 && curl -s https://raw.githubusercontent.com/JoshBecker2/cifar10/refs/heads/main/download.txt | wget -i - && tar -xzvf cifar10-1.tar.gz && tar -xzvf cifar10-2.tar.gz && rm *.tar.gz && mv cifar10-1/* ./ && mv cifar10-2/* ./ && rmdir cifar10*/

Copy and paste this command to download and unzip the archive in one go just like if you downloaded it with 
the original link!
