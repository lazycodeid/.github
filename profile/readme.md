```python
from github.profile import ReadMe
class lazy ( ReadMe ) :
    def __init__ ( self ) :
        self.name  = "lazycodein"
        self.location  = "Indonesia"
    def about ( self ) :
        print( f"{self.name} Developer Team." )
me = lazy()
me.about()
```
