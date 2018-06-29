## MIT&TNB 区块链浏览器说明文档  
### 1.首页  
分为两大模块：Blocks和Transactions。  
Blocks显示最新产生的10个块的信息，信息包括块号、块产生的时间、矿工地址、获得的奖励。  
Transactions显示最新产生的10个交易信息，信息包括交易哈希、转账地址（转币地址from和收币地址to)、转账数量。  
点击View all可查看所有  
### 2.Blocks  
显示产生的所有区块信息列表，每一行信息包括Height、Time、Txs	Uncles、Miner、GasUsed、GasLimit、GasPrice、BlockReward。  
点击Height可根据区块高度查看区块信息，比如区块哈希、区块奖励等。  
点击Miner可根据矿工地址查看地址相关信息，比如地址账户余额，地址所产生的交易列表等。  
### 3.Transactions  
显示所有交易的信息列表，每一行信息包括TxHash、Height、Time、From、To、Value、TxFee。  
点击TxHash可根据交易哈希查看对应的交易信息，比如交易状态、交易地址等。  
点击Height可根据区块高度查看区块信息，比如区块哈希、区块奖励等。  
点击From可根据转币地址查看地址相关信息，比如地址账户余额，地址所产生的交易列表  。
点击To可根据收币地址查看地址相关信息，比如地址账户余额，地址所产生的交易列表。To地址可分为普通地址和合约地址，如果是合约地址则会显示合约相关的信息。  
### 4.Pending Transactions  
显示正在Pending中的交易信息列表，信息包括可参考交易信息。  
### 5.Accounts  
显示所有用户信息列表，信息包括Rank、Address、Balance、TxCount。  
点击Address可根据地址查看地址相关信息，比如地址账户余额，地址所产生的交易列表。
### 6.搜索框
可在搜索框根据Address / Txhash / BlockHeight查询相关信息。  
通过Address查询某个地址对应的地址相关信息，比如地址账户余额，地址所产生的交易列表。  
通过Txhash查询某笔交易对应的交易信息，比如交易状态、交易地址等。    
通过BlockHeight查询某个块对应的区块信息，比如区块哈希、区块奖励等。    
