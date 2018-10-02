## Devconnector compiler 


## Pull in projects updates 

Once you have pushed up your projects updates you can pull down the latest of both repos by running the following:

```
git submodule update --recursive --remote
git submodule foreach git pull origin develop
```

### Links (Resources)
https://blog.github.com/2016-02-01-working-with-submodules/