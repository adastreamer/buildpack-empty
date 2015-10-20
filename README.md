# An empty dokku buildpack

Add to the root of your project these files:

- An empty file `.empty`

- File `.env` with content:                                          
```
export BUILDPACK_URL=https://github.com/adastreamer/buildpack-empty.git
``` 

- File `DOKKU_SCALE` with content:
```
web=0
worker=0
```
