## Task
Train a feedforward CNN and a recurrent CNN on CIFAR-10, then evaluate whether the recurrent model is more 'brain-like' using the texture-vs-shape bias test.

## Context

Lorem ipsum....


## Code Structure
```
project/
│
├── data/                   # CIFAR-10 downloads here automatically
├── models/
│   ├── feedforward.py      # Your standard CNN
│   └── recurrent.py        # Your recurrent CNN
├── train.py                # Training loop, same for both models
├── evaluate.py             # Accuracy + texture/shape bias test
├── analysis/
│   └── plot_results.py     # Figures: accuracy curves, bias bar charts
├── results/                # Saved model weights, plots
└── README.md               # Explains everything clearly
```
