# Three-Pillars-Project
“Three Pillars Project” for better validator operation of Tendermint/Cosmos-SDK based blockchains

--------------------

*Summary*

- title : “Three Pillars Project” for better validator operation of Tendermint/Cosmos-SDK based blockchains 
- grant proposer(validator operator) : B-Harvest(cosmosvaloper10e4vsut6suau8tk9m6dnrm0slgd6npe3jx5xpv)
- grant recipient address : cosmos10e4vsut6suau8tk9m6dnrm0slgd6npe3hjqndl
- grant proposer(keybase identity) : BFAAF68BD473D23958D452708957C5091FBF4192
- contact : telegram @dlguddus, email contact@bharvest.io
- proposed work : 3 projects(2 on Tendermint, 1 on Cosmos-SDK)
- work status(2019-12-18) : 1 project PR finished, 2 projects under implementation
- definition of work completion : Pull Request accepted by Tendermint team
- expected period of work : 12 weeks(subjective to be shorter or longer, depend on review process with Tendermint team)
- requested grant amount : 6,000 atoms in total
- refund policy : if any project is not completed until 18 weeks after beginning date caused by due dilligence of B-Harvest, B-Harvest has responsibility to refund related grant back to community fund

--------------------

*Projects detail*

B-Harvest is working on 3 consecutive projects to strengthen the validator operation of Tendermint/Cosmos-SDK based blockchains. We want to share some progress on those projects.

1) Tendermint ADR 50 : [Improved Trusted Peering](https://github.com/tendermint/tendermint/blob/master/docs/architecture/adr-050-improved-trusted-peering.md)

- brief introduction : strengthening trusted, internal, persistent peers by introducing `unconditional_peer_ids` and `persistent_peers_max_dial_period`
- status : spec PR accepted, implementation PR accepted
- workloads : about 4 weeks
- grant : 1,200 atoms

2) Cosmos-SDK ADR 16 : [Validator Consensus Key Rotation](https://github.com/b-harvest/cosmos-sdk/blob/master/docs/architecture/adr-016-validator-consensus-key-rotation.md)
- brief introduction : allow validators to replace their consensus key
- status : spec PR in discussion, implementation on the way
- workloads : about 8 weeks
- grant : 2,400 atoms

3) Tendermint ADR 51 : [Double Signing Protection with Tendermint Mode](https://github.com/b-harvest/tendermint/blob/master/docs/architecture/adr-051-double-signing-protection-with-tendermint-mode.md)
- brief introduction : prevent double signing of validators by checking recent block data to check the existence of the validator's consensus key, and introducing "Tendermint Mode"
- status : spec on the way, implementation on the way
- workloads : about 8 weeks
- grant : 2,400 atoms


--------------------

*Why contribute?*

From validator operation experience, B-Harvest explored the most pain points of operating validators and we decided to move forward for ourselves to advance the functionality of Tendermint and Cosmos-SDK, especially for validators.
We are very confident that each of above three projects will significantly improve the validator operation quality and security, hence resulting in stronger, safer and more stable network.
Soon, we want to propose community fund grants for above spec design and actual codebase implementation including full PR process with Tendermint team. Before we propose, we want to hear community's opinions about our move.
\
\
*Reasoning of grant proposal*

The reasoning why we propose grants is that B-Harvest want to become a "sustainable contributor" of Cosmos Network and we simply need to cover the human resource to continue our contribution. Our knowledge, experience, and technical skill are becoming mature weeks by weeks, so we are very confident that B-Harvest will become one of the most efficient, highest quality, most sustainable contributor of Cosmos Network.
\
\
*Why community grant?*

Why we ask grant from community? We want full support from the community, not solely by Tendermint team or ICF. We are helping Cosmos but eventually we are a possession of delegators. Our owner is delegators, not Tendermint nor ICF. So it is the reason why we are asking community fund grant. We want to be financially independent from ICF so that we can properly, independently represent the interest of delegators.
\
\
*For the price calculation of our grant proposal*

Our projects are usually devoted by 2 people, each of person devoting about 30%~50% of full time. As a team, we conservatively estimate 4 week contribution as $5,000, which is less than a month salary of any of our team member(it means the price is deficit for B-Harvest!). Total proposed grant is $25,000 for entire three projects.(about 6k atoms)

*Reference*
- forum post : https://forum.cosmos.network/t/three-pillars-project-for-better-validator-operation-of-tendermint-cosmos-sdk-based-blockchains/3066
- projects documentation :
  - [Improved Trusted Peering](https://github.com/tendermint/tendermint/blob/master/docs/architecture/adr-050-improved-trusted-peering.md)
  - [Validator Consensus Key Rotation](https://github.com/b-harvest/cosmos-sdk/blob/master/docs/architecture/adr-016-validator-consensus-key-rotation.md)
  - [Double Signing Protection with Tendermint Mode](https://github.com/b-harvest/tendermint/blob/master/docs/architecture/adr-051-double-signing-protection-with-tendermint-mode.md)