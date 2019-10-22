# bs-modules-example

This repo demonstrates a breaking change between bs-platform 5.1.0 and 5.2.0.

To install and run the example:
```
npm i -g @ryb73/bs-51-52-interop-b
bs-51-52-interop-b
```

The expected output is:
```
-- 100 --
```

However, due to mismatched bs-platforms between @ryb73/bs-51-52-interop-b and its dependency, @ryb73/bs-51-52-interop-a, the output is:
```
-- undefined --
```
