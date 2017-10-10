# VirtualSign

### Dataset format:
Datasets consist of 15 columns. The first 14 correspond to the data gloves sensors input. The last one determines the hand configuration. Each hand configuration is measured 10 times.

### TODO list:
- [x] review architecture (add multiple filters)
- [x] Visualise w/ tf.tensorboard
- [x] create inferring script
- [x] transfer model building function to utils.py
- [x] k-fold cross validation test
- [x] create a model with an intermediate numper of parameters to 25k - 275k
- [x] rounding script for datasets
- [x] name columns appropriately 
- [ ] insert new dataset
- [ ] decide stopping strategy (try early stopping)
- [ ] train-val-test
- [ ] hyper-parameter search script
- [ ] batch evaluation script
- [ ] consider separating the knukle inputs with the finger inpits
- [ ] upload a graph of the model
- [ ] integrate in Virtual Sign
