# bnbchainproposal
bnbchain poposal


Hey BNBChain Community!

I hope you're doing well. I'm reaching out to propose the addition of the [Greenfield Rust SDK Proto](https://github.com/KRakenoZavr/greenfield-sdk-rust-v2) to the [awesome BNBChain](https://github.com/bnb-chain/awesome). As a part of the bnb hackathon we had a task to write Greenfield-cmd in any different language other than GO for obvious reasons. We as a team of full Gopher devs decides to rewrite it in Rust with some benefits in mind like improved reliability, safety, performance, and also what is more important get experience with rust.
 We've noticed that while there is Greenfield SDKs writen in GO and JavaScript, there's no Rust SDK available yet. We spent a LOT of time to try figure out how to AVOID rewriting Greenfield SDK and cosmos SDK to rust by hands for our task specifically. We wasted so much time on that problem so not many time left to do main task... any way at the end we did build Protobufs defined by the greenfield SDK and proof it's working in our project [Greenfield Rust CMD](https://github.com/ive663/ChainSauce_task1) (our project is not complete yet)... but anyone already can use Greenfield-Rust-SDK easy just by  importing it in your project as a dependency inside cargo.toml file:
```
greenfield-sdk-proto = { git = "https://github.com/KRakenoZavr/greenfield-sdk-rust-v2", branch = "main" }
```  

I just wanted to add [Greenfield Rust SDK Proto](https://github.com/KRakenoZavr/greenfield-sdk-rust-v2) so other junior/mid devs can easily find solution and spent more time on building dapps on rust. I did a [PR](https://github.com/bnb-chain/awesome/pull/7) to https://github.com/bnb-chain/awesome two weeks ago but main [contributor](https://github.com/huangsuyu) of that repo is not active anymore...  i went to discord BNBchain/dev-support and I was told to do a proposal here... 

So can anyone help me to add our project to the [awesome list](https://github.com/bnb-chain/awesome/pull/7) if its worse it? or any advice?

Let's make the BNBChain community even more awesome with Rust! 

Thanks 


sources:

https://github.com/KRakenoZavr/greenfield-sdk-rust-v2 - Our Greenfield Rust SDK Protobufs

https://github.com/ive663/ChainSauce_task1 - Our project for hackathon Greenfield Rust CMD we use greeenfield-rust-sdk as external dependency

https://github.com/bnb-chain/awesome - A list of awesome projects in BNB Chain Ecosystem

https://github.com/bnb-chain/awesome/pull/7 - my PR to add Greenfield-Rust-SDK to the list of BNBChain Ecosystem projects


