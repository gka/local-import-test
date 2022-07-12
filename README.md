# local-import-test

run 

```
git clone git@github.com:gka/local-import-test.git
cd local-import-test
(cd services/app && pnpm i)
node services/app
```
to see the code working

for comparison, try `npm` with the same setup

```
git clone git@github.com:gka/local-import-test.git
cd local-import-test
(cd services/app && npm i)
node services/app
```

to see it the local dependencies not being installed
