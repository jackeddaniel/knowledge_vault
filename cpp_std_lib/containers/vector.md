# vector

## This is basically a dynamic array, extremely common for dsa type problems. Most used container in the std_lib.

```cpp 
vector<int> v;
```

Memory - Sequential like an array
Random access - O(1)
Insertion/Deletion at the end - O(1)
Insertino/Deletino in the middle - O(n)

### Construction

```cpp 
vector<int> v;

vector<int> v(5);

vector<int> v(5, 10); // every entry is the number 10

vector<int> v = {1,2,3};

vector<int> copy(v);
```

### Access

```cpp 
v[0]

v.at(0)

v.front() // first element

v.back() // last element
```

### Capacity

```cpp
v.size()

v.empty()

v.capacity()

v.reserve(100)

v.resize(20)

v.clear()
```

### Insert

```cpp
v.push_back(5); // last element O(1)

v.emplace_back(5);

v.insert(v.begin()+2, 100);

v.insert(v.begin(), 3, 7); // 7 7 7
```

### Delete

```cpp
v.pop_back(); // last element O(1)

v.erase(v.begin());

v.erase(v.begin()+2);

v.erase(v.begin()+2, v.begin()+5);

v.clear();
```

