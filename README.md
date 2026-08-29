# Boardwalk

Game Name: Bodacious Boardwalk

Engine: Unreal Engine 5.6.1 

## Required Tools

- Unreal Engine `5.6.1`
- https://git-scm.com/ - Git for version control
- https://git-lfs.com/ - Git lfs for large files

### Optional Tools
- Visual Studio 2022, with the **Game development with C++** workload

### One Time Setup

```sh
# 1. One-time, per machine
git lfs install

# 2. Clone
git clone https://github.com/terrytkato8/boardwalk.git
cd boardwalk

# 3. Optional once per clone
git config lfs.fetchrecentrefsdays 7 # keeps LFS from pulling every historical asset version
git config lfs.fetchrecentcommitsdays 0
git config lfs.setlockablereadonly false

# 4. Verify the assets came down as real files
git lfs ls-files | head
```
