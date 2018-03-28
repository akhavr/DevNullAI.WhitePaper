# Token Economy

## Token supply

ERC20 token, emulating PoS

Total number: ~100mln (? have to recalculate)
Team premine: 450'000 (450k)
Min amount for PoS reward: 10k (later will become a node collateral)

Holders of 10k+ tokens get a vote in a governance system.

Masternodes will orchestrate the incoming stream of programming tasks and learning.
Renting of GPU's/TPU's is paid via our token, which they can hold or exchange (see below)

Initial PoS reward, MoM: 32%
MoM PoS reward declines by 5.5% each month:

* 2018/03/01	450,000	32.00%	144,000	 594,000
* 2018/04/01	594,000	30.24%	179,626	 773,626
* 2018/05/01	773,626	28.58%	221,077	 994,703
* 2018/06/01	994,703	27.01%	268,620	1,263,323

PoS reward distribution:

- collateral holder
- project treasury

* 1st year: holder 10% treasury 90%
* 2nd year: holder 20% treasury 80%
* ...
* 9th year and beyond: holder: 90% treasury 10%

Treasury funds are spent on projects in a dash treasury manner [1].
Any unspent funds are burned (not created).

Constants could be changed using governance system

Exchange and liquidity pool.

ETH<->token exchange is facilitated via contract in Bancor-style (CRR) [2].
To limit security issues due to potential hacking, the amount of ETH stored
in a smart contract would be limited.  Any excesive amount would be shared
with holders of 10k+ tokens.  The limit will increase by 10% monthly.
This also could be changed using governance system

References:
1. https://www.dash.org/2017/09/07/dashdecentral.html
2. https://drive.google.com/file/d/0B3HPNP-GDn7aRkVaV3dkVl9NS2M/view

## Token usage

Token would be used in three ways.

1. Token, used as a payment for the development service.

We're creating an open ecosystem for the AI developers.  Therefore,
the request for the development won't be implemented as a call in a token
smart contract, but instead it would be a call to a separate contract,
deployed by the provider, for example our team.

This call would take an ipfs hash with the task specification (source code,
task to do) and a payment.

Each provider makes their own decision on how the payment would be used.

We initially plan to split the payment the following way:

- 10% towards running the model to provide the requested result
- 90% towards improving the model.

The amount of work to be performed depends on the price of workers: we will
fill them with work, starting with the cheapest with best reputation.

2. Token, used as a workers' stake.

Until the launch of [Pandora](https://pandoraboxchain.ai/) we're
resorting to a simpler way to manage the quality of the workers'
output: we require them to hold a collateral in a smart contract and
will run a random crosscheck.  If a worker would supply an invalid
result, it will lose not just the payment, but a part of the
collateral too.

3. Token, used as a stake in a governance system.

If you're committed to the development of the DevNullAI, your voice has
to be counted.  As mentioned above, holding 10k tokens would be required
to run a masternode and have a formal vote towards proposals in
the budgeting system.
