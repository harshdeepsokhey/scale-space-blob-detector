# Scale-Space blob detector

## The goal of this assignment is to implement a Laplacian Blob detector. 

## Algorithm
1. [ ] Generate a Laplacian of Gaussian Filter
2. [ ] Build a Laplacian scale space, starting with some initial scale and going for 'n' iterations
    1. [ ] Filter image with scale-normalized Laplacian at current scale
    2. [ ] Save square of Laplacian response for current level of scale space
    3. [ ] Increase scale by a factor of k
3. [ ] Perform non-maximum suppression in scale space
4. [ ] Display resulting circles at their characteristics scales.

## Testing
- TODO

## References
- TODO