# unordered_map

## This is basically a hashmap, extremely common for hashmap use cases 

The core hash map used for constant time operations

Every operation - O(1)

### Construction
```cpp
unordered_map<int, int> m;

unordered_map<int, int> m(16); // reserves space for atleast 16 buckets

unordered_map<int, int> m = {{1, 1}, {3, 4}, {5, 18}};

unordered_map<int, int> copy(m);

unordered_map<int, int> range(diff_map.begin(), diff_map.end());
```

### Insert
```cpp
m["one"] = 1;

m.insert({"two", 2});

m.emplace({"three", 3});
```

### Access

```cpp
m["one"];

m.at("one");
```

### Search

```cpp
find()

count()

contains()

```

### Delete

```cpp
erase(key);

erase(iterator);

clear();

```


