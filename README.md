# riscv32-chisel-mycode
RISC-VとChiselで学ぶ はじめてのCPU自作 ――オープンソース命令セットによるカスタムCPU実装への第一歩  
https://www.amazon.co.jp/dp/4297123053/  

## PrePare Settings
1. clone this repository(would like to clone submodule, so add --recursive option.)
```
git clone --recursive https://github.com/sa-kei728/riscv32-chisel-mycode
```

2. install docker
[for Ubuntu20.04]  
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-ja  

3. create docker image
```
cd ./riscv-chisel-book
docker build . -t riscv/mycpu
```

4. run docker(mount src directory)
```
./docker_run.sh
```
