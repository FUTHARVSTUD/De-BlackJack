# De-BlackJack
Decentralizing the game blackjack.

HELLO!!!
===============

![main](./screenshort/main.png)

This is a NFT GAME based on blackjack multiplayer.

You can battle other players with Card NFTs with different abilities.

# Game Previews 
![login](./screenshort/login.png)
![loading](./screenshort/loading.png)
![find](./screenshort/find.png)
![main](./screenshort/main.png)
![main2](./screenshort/main2.png)
![main3](./screenshort/main3.png)
![main4](./screenshort/main4.png)

# How does my multiplayer work
  Imagine a blackjack game where there's no casino running the show, instead everything happens on a big online network like a blockchain. That's the idea behind decentralized blackjack with     NFTs.

  Think of NFTs as digital ownership certificates. In this game, every element, like the cards, the fancy table you play on, even your chips, could be an NFT. You'd actually own these things     and could even buy, sell, or trade them with other players, kind of like a collectors market inside the game itself. Imagine having a super rare NFT that gives you special card backs or        something!

  Now, how does the actual game work? Well, instead of a dealer, there's a special program called a smart contract. This code runs on the blockchain network and basically acts like the brain     of the game. It shuffles the deck, deals the cards, and checks the rules to see who wins, all automatically. Pretty cool, right?

  Since everything is happening on this blockchain network, it's all super transparent. You can see every move, every shuffle, everything. This makes sure no one's cheating and keeps things      fair for everyone. Plus, because it's all recorded on the blockchain, it's super secure too. No one can mess with the game or change the rules.

  So, what are the downsides? Well, these blockchain networks can be slow and expensive to use, which can slow down the game itself. Also, building and running a game like this is pretty         complicated. There's also the whole question of how gambling laws apply to these NFT games, which is something that's still being figured out.

  Overall, decentralized blackjack with NFTs is a pretty new idea with a lot of potential to change the way we gamble online. It's like having a casino that's open to everyone, everywhere, and   where you actually own a piece of the action. But there are some hurdles to overcome before it becomes mainstream.

# DApp
![dapp](./screenshort/1.png)
## Marketplace
![dapp2](./screenshort/2.png)
![dapp3](./screenshort/3.png)
![dapp4](./screenshort/4.png)
![dapp5](./screenshort/5.png)
## Mint
![dapp6](./screenshort/6.png)

# Smart Contract
My smart contract is on Binance smart chain testnet. I have used hardhat to deploy teh contract.

Example transaction
https://testnet.bscscan.com/token/0xe97bd2b6b71647f0c3517613f19f8c561b98a7e8

# How to get start
```
(Note Game)
You should get Moralis API server from moralis.io with binance testnet then open Godot(v.3.4) go to Login Screen Click Login Node You'll see Server Url and App Id from the right side change it if you not see you can open Login script and update it.
PS.You should check the Nakama connect to the your ip (ServerConnect.gd line 3)

(Note Metamask)
if you want 1 BNB go to
https://testnet.binance.org/faucet-smart

(Note Smart contract)
if you want to deploy and get you own smart contract you can do this
1. change the key at secret.json (key is Metamask private key you will get 92b99... then you just add 0x before your private key)
2. npm i
3. npm run deploy:binance

How to run
(you should have docker first)
1. docker-compose up

App: http://localhost
```
