# Back-Propagation Experiment Results

| Run | useCrossEntropy | weightDecay | Train Accuracy | Test Accuracy |
|---|---|---|---|---|
| 1 (baseline) | false | 0.0 | 0.9900 | 0.9800 |
| 2 | true | 0.0 | 0.9675 | 0.9550 |
| 3 | true | 0.0001 | 0.9425 | 0.9550 |
| 4 | true | 0.001 | 0.9525 | 0.9300 |
| 5 | true | 0.01 | 0.8888 | 0.8700 |

**Fixed settings for all runs:** maxEpochs = 1000, learnRate = 0.05, momentum = 0.01, network = 4-5-3, seed = 1.