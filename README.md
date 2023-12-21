# Test-cc
clean code and Comparison of complexity between my code and Mayah's code:

## If we compare the addRice() method:

### Time complexity:

    . For me: 1 comparison, 1 assignment, always returns 1. Total: 3=O(1).
    . For Myah: 1 comparison, 1 assignment, always returns 1. Total: 3=O(1).

### Space complexity:

    . For me: the stored variable is ricePresente, 1=O(1).
    . For Myah: the stored variable is ricePresente, 1=O(1).

## If we compare the cookRice() method:

### Time complexity:

    . For me: 2 comparisons, 1 return, and a call to delaySync() of O(n-p), 1 assignment, and 1 return. Total: 3+O(n-p)+4=O(n-p).
    . For Myah: Same as for me.

### Space complexity:

    . For me: the stored variables are ricePresente and riceCooked with a method call returning an integer K. Total: 3=O(1).
    . For Myah: Same as for me.

## If we compare the steam() method:

### Time complexity:

    . For me: 2 comparisons, 2 returns, and a call to delaySync() of O(n-p), 2 assignments. Total: 4+O(n-p)+4=O(n-p).
    . For Myah: Same as for me.

### Space complexity:

    . For me: the stored variables are ricePresente and steamingInProgress with a method call returning an integer K. Total: 3=O(1).
    . For Myah: Same as for me.

## If we compare the keepWarm() method:

### Time complexity:

    . For me: 1 comparison, 1 return; 1 comparison, 1 return; 1 comparison, 1 return; 1 assignment. Total: 7=O(1).
    . For Myah: 2 comparisons, 1 return, 1 assignment; 1 comparison, 1 return; 1 comparison, 1 return. Total: 8=O(1).

### Space complexity:

    . For me: the stored variables are ricePresente, riceCooked, and heatingInProgress. Total: 3=O(1).
    . For Myah: Same as for me.

## If we compare the removeRice() method:

### Time complexity:

    . For me: 2 comparisons, 4 assignments, and 1 return. Total: 7=O(1).
    . For Myah: Same as for me.

### Space complexity:

    . For me: the stored variables are ricePresente, riceCooked, steamingInProgress, and heatingInProgress. Total: 4=O(1).
    . For Myah: Same as for me.

## If we compare the simulateRiceCooker() method:

### Time complexity:

    . For me: n length and a call to the displayMenu method of O(n), 1 assignment, 1 comparison, 1 assignment, 2 comparisons, 1 comparison, and 1 return. Total: n(O(n)+7)=7n+nO(n).
    . For Myah: 2 assignments, n length and a call to the displayMenu method of O(n), 1 assignment, 1 comparison, 1 assignment, 1 comparison, 1 comparison, a method call to addRice() of O(1), 5 comparisons, 2 method calls of O(1), 2 method calls of O(n-p), 1 return. Total: 14n+nO(n)+2nO(n-p)+3nO(1).

### Space complexity:

    . For me: 3 stored variables. Total: 3=O(1).
    . For Myah: Same as for me.

