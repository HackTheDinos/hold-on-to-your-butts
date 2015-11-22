![jurassic-park](https://cloud.githubusercontent.com/assets/3488572/11323294/14a03354-90dd-11e5-9fe3-7868fd70e9d2.png)

# Taxonomy Cleanup

This [taxonomy.json](taxonomy.json) file semantically remaps the [original API response](https://paleobiodb.org/data1.2/taxa/list.json?datainfo&rowcount&base_name=Dinosauria&show=full&textresult) from the [Paleobiology Database](https://paleobiodb.org) for all taxonomies under Superorder Dinosauria. Keys are more meaningful, and ID codes for parent taxonomies are now presented alongside an index that can be used to look them up efficiently within the records array. For the most part, the [documentation](https://paleobiodb.org/data1.2/taxa/list_doc.html) should no longer be necessary.
