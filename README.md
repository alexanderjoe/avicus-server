# avicus-server
This folder is setup to run the Avicus server with a few additional plugins.

# Requirements
- Java 1.8 (required to support legacy plugins)
- Recommended at least 4GB of ram

# Maps
- Create a `/maps` folder and load the maps you want to play inside
- Inside of `/plugins/Atlas` create a `rotation.xml` file

## Example `rotation.xml` file
```xml
<?xml version="1.0" encoding="UTF-8"?>
<rotations shuffle="true">
    <map>[Map Name]</map>
</rotations>
```

# Running the Server
Run the `run.sh` file.
