#Haskell #CategoryTheory #DataStructures

Makes [[Endomorphism]] a [[Monoid]] with `.` as mappend, and `id` as a mempty
```haskell
> import Data.Monoid
> greets = appEndo $ Endo ("Hello "++) <> Endo (++"!")
> greets "Oleksii"
"Hello Oleksii!"
```
