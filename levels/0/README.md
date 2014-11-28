# Level 0

We'll start you out with Level 0, the Secret Safe. The Secret Safe is
designed as a secure place to store all of your secrets. It turns out that
the password to access Level 1 is stored within the Secret Safe. If only you
knew how to [crack safes](http://en.wikipedia.org/wiki/Safe-cracking)...

# Running

- Install node and npm (see http://nodejs.org/)
- `fig build`

```
fig run web node -v
v0.10.33
fig run web npm -v
2.1.9
```

- `fig run web npm install .` # the docker npm install doesn't install to current dir somehow, this works for now
- Run `npm install` from this directory to install dependencies
- Run `fig up` to start the server on port 3000
- Go to [http://localhost:3000](http://localhost:3000) in your browser
