mvn org.ops4j:maven-pax-plugin:create-bundle -Dpackage=demo.service -DbundleGroupId=com.katdc.mediawalker2.demo.service -DbundleName=demo.service-bundle -Dversion=0.1
=======
demo.service-bundle
===================

one of the two bundles in tutorial-osgi-camel-part1 (http://camel.apache.org/tutorial-osgi-camel-part1.html)

## sucessfully run on karaf 2.3.2

karaf@root> list
START LEVEL 100 , List Threshold: 50
   ID   State         Blueprint      Spring    Level  Name
[  54] [Active     ] [            ] [Started] [   80] demo.service-bundle [demo.service] (0.1)
[  55] [Active     ] [            ] [Started] [   80] demo.camel-bundle [demo.camel] (0.1)
[  62] [Active     ] [            ] [       ] [   50] camel-core (2.11.1)
[  63] [Active     ] [Created     ] [       ] [   50] camel-karaf-commands (2.11.1)
[  77] [Active     ] [            ] [       ] [   50] geronimo-jta_1.1_spec (1.1.1)
[  78] [Active     ] [            ] [       ] [   50] camel-spring (2.11.1)
karaf@root> >> call >> MyTransform set body:  Fri Aug 02 17:40:58 CST 2013

