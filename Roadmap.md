# Challenges

To achieve the industrial level quality, we need to increase our dataset 
by several orders.  Present NN architectures do not offer enough accuracy. 
Hence we have to launch a wide exploration of space of potential architectures.

This will require an amount of GPU/TPU power that's far beyond the reach 
of our small research team.

At the moment there is only a limited understanding of what can be achieved 
down the road. So we do not set a fuzzy goal of finding a perfect solution. 
Instead, we strive to bring together the best team to offer the best solutions 
possible.

# Roadmap

To solve these challenges, we are planning to do an early launch of 
an ecosystem where we can bring together:  

- software developers, willing to try out a new tool,
- owners of GPU who want to help research, and
- deep learning practitioners

We need software developers using AI to give a steady stream of tasks 
and correct solutions to them.

We need GPU operators to have vector processing power 
to run neural networks on.

We need deep learning practitioners to add new promising NN architectures 
to the search space.

To incentivize each party, we're launching an ERC20 token 
on the Ethereum network.

We will start by deploying a federated distributed deep learning system. 
It will require the GPU providers to post a collateral and earn rewards 
for performing deep learning tasks.

Later, we plan to focus on developing and deploying a homomorphic encryption 
module for deep learning, so both AI and data providers can keep their parts 
private (encrypted).

Since this is mostly R&D, we can't give any expected launch dates.  We will 
deploy updates as soon as they will be available in a quality shape.

# Integrations

Our goal is to make DevNullAI useful in a real life.
We envision a simple and generic framework for managing a work breakdown 
structure ([WBS](https://en.wikipedia.org/wiki/Work_breakdown_structure)).

> WBS is a hierarchical and incremental decomposition of the project
> into phases, deliverables, and work packages. It is a tree structure,
> which shows a subdivision of effort required to achieve an aim

Within, there will be a project, attached to a git repository and a list 
of tasks.  If capable, AI will then offer the developer a pull request 
with suggested changes. Otherwise, it will ask the human to break down 
the problem into smaller chunks.

After implementation, this framework will have open API allowing 
the integration into a widely used project management system, 
like Trello, Asana, Jira or private ones, like KavaHQ in 42 Coffee Cups.