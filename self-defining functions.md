- this pattern is useful when your function has some initial preparatory work to do and it need to do it only once.
- a portion of the function may no longer be required.
- a self-defining function can update its own implementation.
- another name for this pattern *lazy function definition* because a function is not properly defined until the first time it's used.
- a drawback of the pattern is that any properties you've previously added to the original function will be lost when it redefines itself.