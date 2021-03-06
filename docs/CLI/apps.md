## Applications
Applications are how the MATRIX OS interfaces with the MATRIX Creator hardware. Applications are a top-level abstraction of MALOS interface. Applications are developed primarly in Javascript (supported), and can leverage other languages (like Python) with non-standard implementations.


### Search

```
# Find MatrixOS apps for a keyword
matrix search keyword
```

**All the following commands require an active MatrixOS to be specified with `matrix use`.**

### Install

```
# Install an app from the store to MatrixOS
matrix install appName
```

### Uninstall
```
# Uninstall an app from your device
matrix uninstall appName
```


### Create
```
#creates a folder with a base matrix app template
matrix create appName
```
See [Matrix OS > API](../API/overview.md) for more information about writing MatrixOS apps.

### Deploy
```
# uploads app folder to MatrixOS
matrix deploy appName
```
### Run
```
matrix start appName
```

### Stop
```
matrix stop appName
```

### Restart
```
matrix restart appName
```
