# Gaussion-Eliminiertation-Method
Sample Code to get a Matrix in the triangle format

This isn't finished, but just a code sample, build from skretch.

Visit the site here:
[Demo](https://rawgit.com/xremix/Gaussion-Eliminiertation-Method/master/gaussion-elimination.html)

## Usage
Enter your Matrix space seperated into the textfield, including the result vector.

Your Matrix must have the form:
`Ax=B`
While `A` must be a `n * n` Matrix.
The input must have `n+1` columns and `n` rows.

If you want to calculate a matrix like this:
```
1a + 2b + 3c = 2
1a + 1b + 1c = 2
3a + 3b + 1c = 0
```

Your input into the tool would be:
```
1 2 3 2
1 1 1 2
3 3 1 0
```

The result of the tool then would be:
```
a = 5
b = -6
c = 3
```