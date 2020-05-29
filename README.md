# Evolution-Strategies-RL
### TODO:
- [ ] Solve "Connect Four" game available in <a href="https://github.com/deepmind/open_spiel">OpenSpiel</a>, using ES algorithms.

**How to run the code?** <br>
`python experiment_runner_modified.py --mutation SM-G-SO --mutation_mag 0.01 --display --domain connect_four  --max_evals 500  --pop_size 150` <br>
For using convolutional layer <br>
`python experiment_runner_modified.py --mutation SM-G-SO --mutation_mag 0.001 --display --domain connect_four_CNN  --max_evals 500 --pop_size 150` <br>
To find about all the arguments use: <br>
`python experiment_runner_modified.py --help` <br>

