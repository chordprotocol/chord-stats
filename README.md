# chord-stats
Tutorial for getting info from chord token using remix

## steps

1. install metamask extension https://metamask.io/download.html
2. switch to binance chain
* open expand view
* go to settings
* go to networks
* click add network
* fill fields (url: https://bsc-dataseed.binance.org/, chainID: 56)
* click save
* go to main page and choose binance network
3. open remix https://remix.ethereum.org/
4. import abi 
* create new file with extension abi (e.g. chord.abi)
* paste in th file content from here https://github.com/ghordprotocol/chord-stats/blob/main/abi/chord.abi
5. connect to contract
* go to Deploy & run transactions (in left menu)
* choose Environment Injected Web3
* paste the address `0xb2f7797389ad34Ebd3a30ac6402861844fAC7F5e` near the button `At Address`
* press the button `At Address` 
* below `Deployed contract` you will be able to call contract methods
