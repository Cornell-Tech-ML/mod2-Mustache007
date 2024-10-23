[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py


## Task 2.5

### Task 2.5.1 Simple Dataset:
Parameters: \
PTS = 50\
HIDDEN = 3\
RATE = 0.1\
EPOCHS = 475\
Time per epoch: 0.103s

![Alt text](./images/simple_log.png)

![Alt text](./images/simple_classification.png)

![Alt text](./images/simple_loss.png)


### Task 2.5.2 Diag Dataset:
Parameters: \
PTS = 50\
HIDDEN = 2\
RATE = 0.1\
EPOCHS = 1000\
Time per epoch: 0.067s

![Alt text](./images/diag_log.png)

![Alt text](./images/diag_classification.png)

![Alt text](./images/diag_loss.png)

### Task 2.5.3 Split Dataset:
Parameters: \
PTS = 150\
HIDDEN = 9\
RATE = 0.1\
EPOCHS = 500\
Time per epoch: 1.191s

![Alt text](./images/split_log.png)

![Alt text](./images/split_classification.png)

![Alt text](./images/split_loss.png)


### Task 2.5.4 XOR Dataset:
Parameters: \
PTS = 150\
HIDDEN = 10\
RATE = 0.05\
EPOCHS = 1200\
Time per epoch: 1.400s

![Alt text](./images/xor_log.png)

![Alt text](./images/xor_classification.png)

![Alt text](./images/xor_loss.png)
