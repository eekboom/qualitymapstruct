Demo project that shows how spotbugs exclusion of generated classes / files does not work with gradle quality plugin.

Running `./gradlew build` fails with a SpotBug violation, even though the quality plugin is configured to exclude the specific class.
 