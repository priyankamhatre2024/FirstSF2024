Apex
Maps:used to store key value pairs data
Map<Integer,String> coleMap = new Map<Integer,String>();
coleMap.put(1001,"Priyanka"); //to add data to a map
**Usage: **
List<String> product = new List<String>{'Coke','Sprite'};
List<String> size = new List<String>{'200ml','500ml'};
Map<String,List<String>> masterData = new Map<String,List<String>>();
masterData.put('Product',product);
masterData.put('Size',size);
System.debug(masterdata.values());
