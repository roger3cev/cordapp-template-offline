![Corda](https://www.corda.net/wp-content/uploads/2016/11/fg005_corda_b.png)

# CorDapp Template: Offline Version

Versions supported: `M10.1`

This is a version of the CorDapp template which has been adapted for use on networks with limited
connectivity to the outside World!

Pre-requisites:

* You'll still need Oracle JDK 1.8
* You'll still want to download the latest version of IntelliJ IDEA CE (2017.1 at the time of writing)
* git

Changes made:

* Adapted `build.gradle` file which looks for all the Corda dependencies in the `/lib/dependencies` folder, there is a 
  `README.txt` file that enumerates all the dependencies required to run the template
* Adapted `gradle-wrapper.properties` file which looks for `gradle-3.4.1-all.zip` in the `/gradle` folder, there is a
  `README.txt` file that shows you where you can find the gradle zip on your machine
  
**Note:** Clearly we cannot distribute the dependencies, therefore it's up to you to find them yourselves. As, such the
resulting repository *with* the dependencies would be for internal distribution only.