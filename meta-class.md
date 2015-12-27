# Meta-Class

###Meta class 
###有一個Method __prepare__
在Python中 METACLASS 是個 Class Factory, 就像是一般 Class用法。

```
def IntContainer():
    class Int:
        def __init__(self):
            self.content_int = ""
        def len(self):
            numberlength=str(self.content_int)
            return len(numberlength)
    return Int
#create The class definition
container_class = IntContainer()
# 建立 instane
wrapped_int= container_class()
wrapped_int.content_int = 123334 
print(wrapped_int.len())


```




```
```