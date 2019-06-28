# Results

## LSA16

### Prototypical Networks

| Min Loss Accuracy    | 95.09%             | 94.99%              | 96.04%              | 95.72%             | 95.82%             | 95.92%             | 95.43%             |
|----------------------|--------------------|---------------------|---------------------|--------------------|--------------------|--------------------|--------------------|
| Min Loss             | 0.3599889278411865 | 0.38138437271118164 | 0.22392521798610687 | 0.2183479517698288 | 0.2170957326889038 | 0.2539535462856293 | 0.2288980633020401 |
| train way            | 5                  | 5                   | 5                   | 5                  | 5                  | 17                 | 17                 |
| train n support      | 1                  | 1                   | 5                   | 5                  | 5                  | 5                  | 5                  |
| train n query        | 1                  | 15                  | 5                   | 5                  | 5                  | 25                 | 5                  |
| test way (val)       | 5                  | 5                   | 5                   | 5                  | 5                  | 5                  | 5                  |
| test n support (val) | 1                  | 1                   | 5                   | 5                  | 5                  | 5                  | 5                  |
| test n query (val)   | 1                  | 1                   | 5                   | 5                  | 5                  | 5                  | 11                 |
| train episodes       | 100                | 100                 | 100                 | 100                | 100                | 100                | 100                |
| epochs               | 200                | 200                 | 200                 | 200                | 200                | 200                | 200                |
| lr                   | 0.001              | 0.001               | 0.001               | 0.001              | 0.001              | 0.001              | 0.001              |
| patience             | 100                | 100                 | 100                 | 100                | 100                | 100                | 100                |
| rotation range       | 0.0                | 0.0                 | 0.0                 | 25.0               | 25.0               | 0.0                | 0.0                |
| width shift range    | 0.0                | 0.1                 | 0.1                 | 0.1                | 0.1                | 0.1                | 0.1                |
| height shift range   | 0.0                | 0.1                 | 0.1                 | 0.1                | 0.1                | 0.1                | 0.1                |
| horizontal flip      | false              | true                | false               | true               | false              | true               | false              |