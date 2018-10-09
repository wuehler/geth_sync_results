# geth_sync_results

This is the console output from a test of a Fast sync geth node performed on Oct 7, 2018 on a fresh i3.large EC2 instance.

Commands run:

wget https://gethstore.blob.core.windows.net/builds/geth-linux-amd64-1.8.16-477eb093.tar.gz

tar zxvf geth-linux-amd64-1.8.16-477eb093.tar.gz

nohup geth-linux-amd64-1.8.16-477eb093/geth --cache 4096 --syncmode "fast" &


Outcome:

Headers synced: ~10hrs

State synced: ~30hrs
