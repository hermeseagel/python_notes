# Meta-Class

###Meta class 
###有一個Method __prepare__
在Python中 METACLASS 是不Class Factory 

```
def IntContainer():
    class Int:
        def __init__(self):
            self.content_string = ""
        def len(self):
            return len(self.content_string)
    return Int
#create The class definition
container_class = IntContainer()
# 建立 instane
weapped_int= container_class()
wrapped_int.content_int = 123334 
wrapped_int.len()

```




```
```