# EBS Snapshots

- Make a point in time backup (snapshot) of your EBS volume
- Not necessary to detach volume to do snapshot, but recommended
- Can copy snapshot across AZ or Region
- EBS Snapshot Archive
  - Archive tier is 75% cheaper
  - Takes 24-72 hours to restore archive
- Recycle bin for snapshots
  - Rules can be setup to retain deleted snapshots 
- Fast Snapshot Restore
  - Force full initialization of snapshot to have no latency on first use
    - Costs $$