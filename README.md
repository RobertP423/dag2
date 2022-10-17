Installation
```
sudo wget https://github.com/SumDumOp/dag2/raw/main/dag2 -O /usr/local/bin/dag2 && sudo chmod +x /usr/local/bin/dag2
```

Usage
```
dag2
```

Note: I make no guarantees that this will work for you. Fortunately it can't really fuck anything up too bad. But don't take my word for it.

Seriously.

Look at the script commands yourself before you execute it. Get into a habit of doing that. You're about to download and execute a stranger's code; never something to be taken lightly.

High level summary of this script:
-Check and compare your installed version of Tessellation to the version the load balancer is running. Update local .jar files if needed.
-Kill any node processes.
-Restart node services and join the l0 and l1 clusters.

As with everything else in life, further development from here is not guaranteed. I do hope some of you find this little script as useful as I already have.
