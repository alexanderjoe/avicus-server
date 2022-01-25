# avicus-server
- This folder is setup to run an Atlas server from [Avicus](https://avicus.net) with a few additional plugins.
- All credit goes to the original Avicus Development team and the work can be found on their [GitHub](https://github.com/Avicus).

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
