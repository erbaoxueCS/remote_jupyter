# remote_jupyter

**Server:**

```
jupyter notebook --no-browser 
```

You will get the **port** and **token** from the command line.

**User:**

```
ssh -N -f -L localhost:8888:localhost:8889 username@serverIP 
```

the first port is local port, the second is server port.

`username@serverIP` can be simplify if your ssh config has that connection:

https://github.com/erbaoxueCS/remote-keys

Then we can use jupyter locally:

```
http://localhost:8888/
```

