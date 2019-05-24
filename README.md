


About
-----

FutureWorkshops fork of **Smack** to fix internationalisation features.

Version
-----

The `fw_master` branch uses the code from `4.3` tag because  the original master branch updated jxmpp versions to 0.7-alpha whitch causes breaking changes in the code.


Getting started
---------------

1. Clone repository
2. Open terminal window and navigate to repository location(ex: `cd /Users/repositories/Smack` )
3. Run `./gradlew idea`
4. Open InteliJ and choose `File -> Open` to open the project.
5. Open `local.properties` and make sure the value of `sdk.dir` points to your `.../Android/sdk/` folder.

The project should be imported and gradle-synced successfully.


Exporting modules
---------------

If you get a permission error when trying to run `./gradlew` commands, execute the following: 
```
chmod +x gradlew
```

You can export modules individually from the Terminal:

```
./gradlew :smack-core:assemble
```


Please see [original  README](/README_old.md) for details about the library.

