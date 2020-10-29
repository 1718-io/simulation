# Initialization

```bash
git clone git@github.com:1718-io/simulation.git culture-ric/
cd culture-ric/
git flow init --defaults
git push -u origin --all
export FEATURE_ALIAS='github_org_mgmt_policy'
git flow feature start ${FEATURE_ALIAS}
git push -u origin --all
atom .

```

# Resume work

```bash
# git clone git@github.com:1718-io/simulation.git culture-ric/
cd culture-ric/
# git flow init --defaults && git push -u origin --all
export FEATURE_ALIAS='github_org_mgmt_policy'
# git flow feature start ${FEATURE_ALIAS} && git push -u origin --all
export COMMIT_MESSAGE="feat.(${FEATURE_ALIAS}) : adding a first example policy"
git add --all && git commit -m "${COMMIT_MESSAGE}" && git push -u origin HEAD
atom .
```
