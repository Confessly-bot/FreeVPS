wget https://github.com/xmrig/xmrig/releases/download/v6.26.0/xmrig-6.26.0-linux-static-x64.tar.gz
tar -xzf xmrig-6.26.0-linux-static-x64.tar.gz
cd xmrig-6.26.0
sudo sysctl -w vm.nr_hugepages=2048
sudo ./xmrig -o gulf.moneroocean.stream:10128 -u 45GqJTAdN1uJaffSFQbwU8Jqv3xsoSvzTGPwGzjbZFuF6m5fYcg6tja2z7HtGfuJNSh5SU2sB8t5DTSsByDgZiYf6PttU4h -p vm1 -k --threads=4
