### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Free Cornelius

## Step 1
Освободи Корнелиуса за тюками сена


```ghost
    agent.move()
    agent.destroy()
```
```template
    agent.destroy(FORWARD)
    agent.move(FORWARD, 1)
    agent.destroy(UP)
```

```package
\\
```