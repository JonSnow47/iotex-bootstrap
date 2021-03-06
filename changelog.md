- We have upgraded testnet and mainnet to `v1.0.0`. The breaking changes which will be activated on mainnet at block height 5157001.
- We have upgraded testnet to `v1.0.0-rc`. This version introduces native staking on IoTeX chain.
- We have upgraded testnet and mainnet to `v0.11.1`. A blocker indexer racing issue is fixed. The breaking changes which will still be activated on mainnet at block height 4478761.
- We have upgraded testnet and mainnet to `v0.11.0`. This version introduces delegates probation. It contains breaking changes which will be activated on mainnet at block height 4478761.
- We have upgraded testnet to `v0.11.0-rc`. This version introduces probation.
- We added auto upgrade feature in our upgrader. Auto upgrade will check if there is an avilable upgrade every 3 days and automactilly doing the upgrade.
- We have upgraded testnet and mainnet to `v0.10.3`. This version improve stability on reading native staking buckets.
- We have upgraded mainnet to `v0.10.2`. It contains breaking changes which will be activated on block height 3238921. Delegates must upgrade your node to the new version before that.
- We have upgraded testnet to `v0.10.2`. This version correct a gas limit issue for reading native vote bucket.
- We have upgraded mainnet to `v0.10.0`. It contains breaking changes which will be activated on block height 1816201. Delegates must upgrade your node to the new version before that.
- We have upgraded testnet to `v0.10.0`. This version reduce block interval to 5s.
- We found a bug in `v0.9.0` which may cause the nodes not agree on the delegates list. We already pushed out a build `v0.9.2` to address this issue.
- `v0.9.0` is released, so that delegates should upgrade their softwares to this new version. The fork will happen at block height 1641601. Before restarting with `v0.9.0` docker image, please re-pull the up-to-date mainnet genesis config file first. It's a MUST step for this upgrade. In addtion, note that this upgrade will result in db migration upon restart which could takes 30min to 1hr to complete. Therefore, please upgrade when the delegate node is not in the active consensus epoch.
- We have reset testnet, and deployed `v0.8.3`, and finally upgraded it to `v0.9.0`. The genesis config file has been updated as well.
- We have upgraded mainnet to `v0.8.3`. It contains breaking changes which will be activated on block height 1512001. Delegates must upgrade your node to the new version before that.
- We have upgraded testnet to `v0.8.4`.
- We have upgraded testnet to `v0.8.3`, which contains the new error code, and consensus improvement.
