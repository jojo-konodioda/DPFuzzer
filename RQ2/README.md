## Data Structure

```bash
tree data -L 3
data
├── D-GA    #algorithm
│   ├── ......
├── Ours    #algorithm
│   ├── Ego-Planner    #path planner under test
│   │   ├── S1    #scenario
│   │   ├── S2
│   │   ├── S3
│   │   └── S4
│   └── Ego-Planner-Swarm    #path planner under test
│       ├── S1
│       ├── S2
│       ├── S3
│       └── S4
└── Rand    #algorithm
    └── ......


tree data/Ours/Ego-Planner/S1/ -L 2
S1
├── 1    #replicates experiments, 5 runs
│   ├── misbehaviour    #scenarios which trigger misbehaviours
│   └── scenarios    #all the generated scenarios
├── 2
│   ├── misbehaviour
│   └── scenarios
├── 3
│   ├── misbehaviour
│   └── scenarios
├── 4
│   ├── misbehaviour
│   └── scenarios
└── 5
    ├── misbehaviour
    └── scenarios

```
