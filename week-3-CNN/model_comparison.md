# Week 3 - Part 2 Model Comparison
| Model           | Accuracy |
| --------------- | -------- |
| Baseline CNN    | 68.59%   |
| CNN + BatchNorm | 68.01%   |
| Deep CNN        | 77.34%   |
| ResNet          | 71.29%   |

How much did BatchNorm help?
In this experiment, BatchNorm did not significantly improve final accuracy, though it generally stabilizes training.

Why can deeper networks perform worse?
Gradients become harder to optimize and training may suffer from degradation.

How do skip connections help?
They provide a direct path for gradients, making optimization easier.
