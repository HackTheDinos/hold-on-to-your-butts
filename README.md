<iframe width="420" height="315" src="https://www.youtube.com/embed/-W6as8oVcuM" frameborder="0" allowfullscreen></iframe>

# Taxonomy Cleanup

This [taxonomy.json](taxonomy.json) file semantically remaps the [original API response](https://paleobiodb.org/data1.2/taxa/list.json?datainfo&rowcount&base_name=Dinosauria&show=full&textresult) from the [Paleobiology Database](https://paleobiodb.org) for all taxonomies under Superorder Dinosauria. Keys are more meaningful, and ID codes for parent taxonomies are now presented alongside an index that can be used to look them up efficiently within the records array. For the most part, the [documentation](https://paleobiodb.org/data1.2/taxa/list_doc.html) should no longer be necessary.
