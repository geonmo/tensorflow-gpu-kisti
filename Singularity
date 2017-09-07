Bootstrap: docker
From: abhishek404/tensorflow-gpu:latest

%runscript

exec echo "The runscript is the containers default runtime command!"


%files


%environment
VARIABLE=MEATBALLVALUE
export VARIABLE

%labels
AUTHOR vsochat@stanford.edu

%post

mkdir /cvmfs

echo "The post section is where you can install, and configure your container."
