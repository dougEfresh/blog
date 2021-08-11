# What exactly is bitcoin?

### A consensus breakdown.

I'm having a discussion with my friend, Dylan, about bitcoin when he links me a video of Nassim's [black paper](). 
I respect Nassim very much and enjoy his book Black Swan. 

But his criticism of bitcoin are misguided. I want to purpose an alternative criticism that suits his immense knowledge of maths and statistics. 

---

## A Simple Contract

Let's start by examining a simple futures contract between my above mention friend, Dylan.
I will give him $40,000 now and on January 1st 2022 he'll give me one bitcoin. Simple enough right?
But let's put on our lawyer hat on; this is some serous money we're talking about.
We both want a non-ambitious contract.

$40,000 is rather clear. To be more specific we both agree that this is notes issued by the U.S. Federal Reserve system, aka a U.S. Federal Note. 
January 1st is also well-defined. We can add a specific time in UTC with a public military atomic clock as our reference. 

But what exactly is bitcoin? How do we define it in this contract?

* The ticker symbol BTC on XYZ exchange. 

Seems reasonable. But both parties of the contract are at the mercy of whatever definition that XYZ gives BTC.
What if there's a soft/hard fork between now and Jan 1st? What if XYZ decides to BTC is now the new forked network? Either party could be screwed. 

* Predefined public address: XXXXXXXXXXXXX

But what if some group of people fork bitcoin-core to run their own chain and supports all address forms of current bitcoin? 
Dylan could just send one unit on whatever chain supports this address. I.e. the adress is just a hash number, it doesn't define bitcoin. 

* Binary version from https://bitcoincore.org/en/download/ signed by this PGP 01EA5486DE18A882D4C2684590C8019E36C2E964

This seems better. But what if the owner doesn't sign or the PGP is changed? Also, do we have to specify a running config? What if Dyan specifies a bootstrap seed that connects to a different chain (e.g. testnet)?

* I provide Dylan with a DNS/IP of a node I control

This works for me. But that's a little unfair to Dylan. I'm defining what bitcoin is.
There isn't a mutual agreement between us.

* We agree upon a 3rd party node

Better but it's like the exchange senario above. Either one of use could get screwed. Or the 3rd party is shut down or blocks incoming connections.
We can go on and maybe find a consensus. But our agreement isn't universal. Someone else could have a similar contract with a slightly different consenus. 
I may want to sell this contract before Jan 1st. The buyer has to be fully aware the definition. 
This doesn't scale, and we have ourselves a market inefficiency.

---

## The Big Players

Let's look at this from the big financial players' perspective: insurance, pension funds, soverign funds...etc

Suppose I want to start a bitcoin bank to provide basic loans and deposits with interest. 
I would want to get some insurance as my competitors would do the same. 
I call up insurance ABC and they set terms of this insurance. This includes defining bitcoin (the chain) with their own nodes. 
Going further, ABC is going to want re-insurance as well. The re-insurance company also runs their own nodes. 
Most likely though, the insurance industry will just agree on a definition of bitcoin as a whole. Saving costs and allowing these insurance contracts 
to be traded in a secondary market.

Seems like (potentially) the insurance industry could define bitcoin, not the worldwide nodes on the network.

The above is what I want Nassim to write/talk about: The risk of a total consensus breakdown, technical or human (not sure what word to us). 
What if there is a "Black Swan" event that results in an unclear definition for bitcoin? 
What's the probability of this happening? 
How would various parties (exchanges, banks, pensions, sovereign) react when they believe bitcoin is X but insurance thinks it is Y?

In the book [Ascent of Money](https://en.wikipedia.org/wiki/The_Ascent_of_Money) a critical characteristic of a monetary system is easy agreement without ambiguity on the unit of account being exchanged.
Clear consensus is very important and I fear that despite bitcoin's wonders from a technical consensus achievement, the humans will get confused and exit this market entirely. 

Finally, what if someone creates another crypto such that there is a clear governance model with unambiguous definition of the unit of account? - (take this sentence out?)


