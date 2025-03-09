### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Clear the Hay Bales

## Step 1
Очисти тюки сена


```ghost
    agent.move()
    agent.destroy()
```
```template
    agent.destroy(UP)
    agent.move(LEFT, 1)
    agent.destroy(FORWARD)
```

```package
\\
```