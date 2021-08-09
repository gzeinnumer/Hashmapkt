# Hashmapkt
 
```java
val hashMap: HashMap<Int, String> = HashMap()
val hashMap2: HashMap<String, String> = HashMap(2) // only 2 capacity

hashMap.put(1, "M")
hashMap.put(2, "Fadli")
hashMap.put(3, "ZEIN")
hashMap.put(4, "ZEIN")
hashMap.put(5, "M. Fadli Zein") // 5 as index

hashMap2.put("index1", "M") // index1 as index

println(hashMap[2])
println(hashMap[5])

println("String "+hashMap2["index1"])

for (key in hashMap.keys){
   println("for1 "+hashMap.get(key))
}
```

---

```
Copyright 2021 M. Fadli Zein
```
