mvn org.ops4j:maven-pax-plugin:create-bundle -Dpackage=demo.service -DbundleGroupId=com.katdc.mediawalker2.demo.service -DbundleName=demo.service-bundle -Dversion=0.1
=======
demo.service-bundle
===================

one of the two bundles in tutorial-osgi-camel-part1 (http://camel.apache.org/tutorial-osgi-camel-part1.html)

## sucessfully run on karaf 2.3.2
karaf@root> >> call >> MyTransform set body:  Fri Aug 02 17:38:38 CST 2013
>> call >> MyTransform set body:  Fri Aug 02 17:38:48 CST 2013
>> call >> MyTransform set body:  Fri Aug 02 17:38:58 CST 2013
>> call >> MyTransform set body:  Fri Aug 02 17:39:08 CST 2013
>> call >> MyTransform set body:  Fri Aug 02 17:39:18 CST 2013
>> call >> MyTransform set body:  Fri Aug 02 17:39:28 CST 2013
>> call >> MyTransform set body:  Fri Aug 02 17:39:38 CST 2013
>> call >> MyTransform set body:  Fri Aug 02 17:39:48 CST 2013

