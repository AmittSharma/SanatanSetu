# 🌿 SanatanSetu Branch Rules

| Branch | Purpose | How to Merge |
|---------|----------|--------------|
| main | Stable release | Only via PR from release/* or hotfix/* |
| develop | Active development | Only via PR from feature/* or bugfix/* |
| feature/* | New features | Merge → develop |
| bugfix/* | Non-critical fixes | Merge → develop |
| release/* | Preparing new version | Merge → main + develop |
| hotfix/* | Urgent production fix | Merge → main + develop |

All merges must go through Pull Requests with at least one approval 🙏