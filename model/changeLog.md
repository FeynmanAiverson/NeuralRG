### V 0.2

1. Vars naming changes: Nvars -> numVars, etc.
2. Create templates for layers and realNVP for flexibile use in future.
   - you can now use customized torch module as coupling layers.
   - you can use customized mask.
3. Use created templates to re-write realnvp.py (now is realnvp_.py).
4. Use new class for NN instead of list of torch.nn.*, so that we can save
  trained NN.