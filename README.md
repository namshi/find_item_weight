Find item weight from shipment weights

- Lets say, a warehouse, measures weight of shipments that are going out
- A shipment contains one or more items
- We want to find the weight of each item in the warehouse


## input 
```
data = [{'skus':['a','b'], 'weight':3}, {'skus':['b'], 'weight':1},{'skus':['b'], 'weight':2}, {'skus':['a','b','c','d'], 'weight':10}, {'skus':['a','d'], 'weight':5}, {'skus':['a','b'], 'weight':4}]
```

## output
```
weight of b is 1.5
weight of a is 2.0
weight of d is 3.0
weight of c is 3.5
```

