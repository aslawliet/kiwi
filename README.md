# tKiwi
## Key Highlights
- long Chain-Of-Thought
- inference time tree-search
- use of Q-Value

## Data Preparation (Kiwi)
- ***Creating Reasoning Tree*** -> sampling N nodes for each selected path (stop condition - all terminal nodes)
- ***Pruning Reasoning Tree*** -> based on Monte-Carlo Estimate for each node in tree
- ***Data For Q-Value***
  -> __Outcome Q-Value__ -> save the Monte-Carlo rollouts and all the paths in tree, with binary labels (whether the rollout or path achieved correct answer)
  -> __Process Q-Value__ -> save only the Monte-Carlo rollouts with Monte-Carlo Estimates
- ******

-----
# testKiwi
