# Azure NetApp Files CLI

Performs management CRUD operations for Microsoft.NetApp resource provider using GoLang.

Source of Example [Microsoft Example](https://github.com/Azure-Samples/netappfiles-go-sdk-sample).

- Creation
    - NetApp Files Account
    - Capacity Pool
    - Volumes (one NFSv3 and one NFSv4.1)
    - Snapshot NFSv3 volume
    - Volume from Snapshot (NFSv3)
- Updates
    - Change the NFSv4.1 Volume size
- Deletions (when cleanup variable is set to true)
    - Snapshot
    - Volumes
    - Capacity Pools
    - Accounts

