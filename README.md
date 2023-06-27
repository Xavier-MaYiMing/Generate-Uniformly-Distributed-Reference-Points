### Generate Uniformly Distributed Reference Points

##### Reference: Das I, Dennis J E. Normal-boundary intersection: A new method for generating the Pareto surface in nonlinear multicriteria optimization problems[J]. SIAM Journal on Optimization, 1998, 8(3): 631-657.

This is the python implementation of generating uniformly distributed reference points, which are essential to decomposition-based multi-objective evolutionary algorithms (MOEAs).

#### Example

Generate approximately 15 uniformly distributed reference points on 3 dimension.

```python
if __name__ == '__main__':
    print(reference_points(15, 3))
```

#### Output

```python
[[0.   0.   1.  ]
 [0.   0.25 0.75]
 [0.   0.5  0.5 ]
 [0.   0.75 0.25]
 [0.   1.   0.  ]
 [0.25 0.   0.75]
 [0.25 0.25 0.5 ]
 [0.25 0.5  0.25]
 [0.25 0.75 0.  ]
 [0.5  0.   0.5 ]
 [0.5  0.25 0.25]
 [0.5  0.5  0.  ]
 [0.75 0.   0.25]
 [0.75 0.25 0.  ]
 [1.   0.   0.  ]]

```

