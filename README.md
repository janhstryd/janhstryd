-P,--pool           Stratum pool. Example
                    ckb pool: stratum+tcp://youraccount.workname@ckb-eu.sparkpool.com:8888
                    eth pool: stratum1+tcp://youraccount.workname@cn.sparkpool.com:3333
                    scheme://[account[.workername]@]hostname:port

-E                  Dual mining mode, set ETH pool, single mining mode only need set -P 
                    scheme://[account[.workername]@]hostname:port

-A                  Algorithm supported:ckb,eth,eth_ckb,eth_hns,eth_trb,rvn
-h,--help           Displays this help text and exits
-V,--version        Show program version and exits
--api-bind          Default not set. Example:--api-bind 127.0.0.1:3333
                    Use negative port number for readonly mode
--api-port          Default not set.range from (1~65535) 
                    listen on this port 
--api-password      Default not set.you can set the password to protect your interaction
-I,--intensity      Dual mining mode ,ETH hashrate will faster and slave coin hashrate will slower 
                    with the smaller intensity range from (0~8).default 4
                    
