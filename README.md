# swizzle

```haskell
import Data.Swizzle qualified as Swz

foo :: (Int, Int, Int, Int)
foo = Swz.zyxw (0, 1, 2, 3, 4, 5, 6, 7, 8, 9) -- (3, 2, 1, 0)
```
