# MoneroJSMiner
 Javascript Crypto Miner For Monero
 
 # Download
 
 Download using the Zip downloader on Github Or Run 
 
 git clone https://github.com/sn3ll/MoneroMiner
 cd MoneroMiner
 ./Mine.html
 
# Configure

In Mine.Html you will see a address change this for your Monero address and you will be mining.

server = "wss://f.xmrminingproxy.com:8181";
    var pool = "moneroocean.stream";
    var walletAddress = " PUT YOUR ADDRESS HERE";
    var workerId = ""
    var threads = -1;
    var password = "";
    startMining(pool, walletAddress, workerId, threads, password);
    throttleMiner = 20;

Once Mine.Html is open it will automatically start mining.

# Check Progress 

Go to moneroocean.stream . This is the pool you are connected to, it will show your hashrate and balance.

# Use In Other Projects 

Copy the code from Mine.Html and paste it into your html file. Put the Miner.js in the same directory and you're ready to go.
