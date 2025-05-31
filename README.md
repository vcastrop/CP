# CP
Competitive Programmer's HandBook by Antti Laaksonen
---
## Basic techniques

<details>
  <summary> <h3> 1.Intro </h3></summary>

**to make input and output more efficient:**
```c++
ios::sync_with_stdio(0)
cin.tie(0)
```

**reads from input.txt and writes on output.txt:**
```c++
freopen("input.txt", "r", stdin);
freopen("output.txt", "w", stdout);
```

**input:**
```c++
int a, b;
string x;
cin >> a >> b >> x;
//alternative
scanf("%d %d", &a, &b)
// reading a hole line from input (including spaces)
string s;
getline(cin, s);
// if the amount of data is unknown
while(cin >> x){
    //code
}
```

**output:**
```c++
int a = 123, b = 467;
string x = "monkey";
cout << a << " " << b << " " << x << "\n";
//
printf("%d %d\n", a, b) 
```
\n works faster than endl

**working with numbers:**

</details>

<details>
  <summary><h3> 2. Time complexity </h3></summary>

<!-- Add your notes or content for Time complexity here. -->

</details>

<details>
  <summary>### 3. Sorting</summary>

<!-- Add your notes or content for Sorting here. -->

</details>

<details>
  <summary>### 4. Data structures</summary>

<!-- Add your notes or content for Data structures here. -->

</details>

<details>
  <summary>### 5. Complete search</summary>

<!-- Add your notes or content for Complete search here. -->

</details>

<details>
  <summary>### 6. Greedy algorithms</summary>

<!-- Add your notes or content for Greedy algorithms here. -->

</details>

<details>
  <summary>### 7. Dynamic Programming</summary>

<!-- Add your notes or content for Dynamic Programming here. -->

</details>

<details>
  <summary>### 8. Amortized analysis</summary>

<!-- Add your notes or content for Amortized analysis here. -->

</details>

<details>
  <summary>### 9. Range queries</summary>

<!-- Add your notes or content for Range queries here. -->

</details>

<details>
  <summary>### 10. Bit manipulation</summary>

<!-- Add your notes or content for Bit manipulation here. -->

</details>

---
## Graph Algorithms
---
## Advanced topics