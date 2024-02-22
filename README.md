# A 4-week Research Internship on RISC-V using VSDSquadron Mini RISC-V Dev Board
# Task 1:

install RISC-V GNU Toolchain

install Yosys

install iverilog

install gtkwave

CLONING RISC-V GNU TOOLCHAIN
sudo apt install git-all # To install git

sudo apt-get install autoconf automake autotools-dev curl python3 libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev make sure to install the dependencies

![1](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/9e73b21d-5f57-4f27-b5a4-2c489b0d40f1)


# Create a opt dir
mkdir /opt/riscv try sudo incase of permission denial

In my case I created a driectory mkdir riscv

![2](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/dd1838e8-9dff-4b8c-bf7c-eb15e49723c6)


# INSTALLING IVERILOG GTKWAVE & YOSYS
YOSYS
git clone https://github.com/YosysHQ/yosys.git cd yosys sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev make config-gcc make sudo make install

![yoy](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/f9861c13-edc8-432d-8545-3228134550bf)

![yoy1](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/8b2a5e5c-f57c-4b2f-bb26-ef1a24b8612c)

# iVerilog
sudo apt-get install iverilog


![iveri](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/751aa030-ce0a-4da8-bd4e-2d59633ed5e8)
# GTkWave
sudo apt-get install gtkwave

![gtk](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/bc6a7107-6d42-4eb7-ab36-9079111e341b)
