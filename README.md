sudo apt install libsodium-dev

wget https://github.com/hellcatz/hminer/releases/download/v0.59.1/hellminer_linux64_avx2.tar.gz

tar -xvf hellminer_linux64_avx2.tar.gz

./hellminer -c stratum+tcp://ap.luckpool.net:3956 -u RESDBYKfSzZ3iuzLUhrLoWKkP3fJ253YG2.free -p x --cpu 8

nano run_miner.sh

./run_miner.sh

