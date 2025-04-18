# SoMo Installation & Setup

## Install

### Ubuntu

sudo apt-get update

sudo apt-get install -y build-essential libssl-dev zlib1g-dev libbz2-dev \
                        libreadline-dev libsqlite3-dev wget curl llvm \
                        libncurses5-dev libncursesw5-dev xz-utils tk-dev \
                        libffi-dev liblzma-dev python3-openssl git

mkdir ~/python38
cd ~/python38
wget https://www.python.org/ftp/python/3.8.10/Python-3.8.10.tgz
tar -xf Python-3.8.10.tgz

cd Python-3.8.10

./configure --enable-optimizations

make -j$(nproc)

sudo make install

python3.8 --version

python3.8 -m venv venv

clone repo, install reqs

error when running python3 run_traj.py --env_name SnakeLocomotionDiscrete --traj_name test
