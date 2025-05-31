# CP
Competitive Programmer's HandBook by Antti Laaksonen
---
## Basic techniques

<details>
  <summary> <h3> 1.Intro </h3></summary>

>**to make input and output more efficient:**
>```c++
>ios::sync_with_stdio(0)
>cin.tie(0)
>```

>**reads from input.txt and writes on output.txt:**
>```c++
>freopen("input.txt", "r", stdin);
>freopen("output.txt", "w", stdout);
>```

>**input:**
>```c++
>int a, b;
>string x;
>cin >> a >> b >> x;
>//alternative
>scanf("%d %d", &a, &b)
>// reading a hole line from input (including spaces)
>string s;
>getline(cin, s);
>// if the amount of data is unknown
>while(cin >> x){
>    //code
>}
>```


>**output:**
> ```c++
>int a = 123, b = 467;
>string x = "monkey";
>cout << a << " " << b << " " << x << "\n";
>//
>printf("%d %d\n", a, b)
>```

\n works faster than endl

>**working with numbers:**
<br>
int(32-bit)
<br>
long long (64-bit)
<br>

>**modular arithmetic:**
>```c++
>//to calculate n! 
>long long x = 1;
>for (int i = 2; i <= n; i++){
>    x = (x*i)%m;
>}
>cout << x%m << "\n";
>// if we dont want negative remainders
>x = x%m;
>if(x<0) x += m;
>```

>**floating point numbers**
> <br> double(64-bit)
> <br> long double(80-bit)
> ```c++
>   //prints the value of x with 9 decimal places:
> printf("%.9f\n", x);
> // floating point numbers are equal if the difference between them is less than e (1e-9)
> if(abs(a-b)<1e-9){
>   // a and b are equal
> }
> ```

>### Shortening code:
> <br> to write as fast as possible
> 
>```c++
>//type names: typedef
>typedef long long ll;
>ll a = 12345677;
>ll b = 987654321;
>typedef vector<int> vi;
>typedef pair<int, int> pi;
>
>//macros: #define
>#define F first
>#define S second
>#define PB push_back
>#define MP make_pair
>v.PB(MP(y1,x1));
>int d = v[i].F+v[i].S;
>//it can also have parameters
>#define REP(i,a,b) for (int i = a; i <=b; i++)
>REP{
>   search(i);
>}
>#define SQ(a) (a)*(a)
>```

>### Mathematics:
> ***arithmetic progression:*** 
> <br>sequence of numbers where the jumps are constant. (3,7,11,15)
> <br>a+...+b=n(a+b)/2
> <br>
> ***geometric progression:***
> <br>sequence of numbers where the ratio of the jumps is constant.(3, 6, 12, 24)
> <br> a+ak+ak^2+...+b=(bk-a)/k-1
> <br>
> ***harmonic sum:***
> <br>1+1/2+1/3+...+1/n.

>### Set Theory:
> A set is a collection of elements. 
> - X = {2,4,8}
> - ∅ empty set
> - |X| size of the set X
> - 4  ∈ X and 5 ∌ X
> - Intersection: elements both in A and B
> - Union: elements in A or in B or in both.
> - Complement: elements not in A.
> - difference: elements in A but not in B.
> - If each element of A also belongs to S, A is a subset of S.
> - subsets of X = ∅, {2}, {4}, {8}, {2,4}, {2,8}, {4,8} and {2,4,8}
> - X = {2n: n ∈ Z} the set contains all even integers.

>### Logic:
> ![img.png](img.png)
> quantifiers!!

>### Functions:
>  - ⌊ ⌋ round down
>  - ⌈ ⌉ round up
>  - min(x,y,z) gives the smallest value
>  - max(x,y,z) gives the largest value
>  - n! = 1*2*3*...*n
>  - fibonacci: f(n) = (1+√5)^n-(1-√5)^n/2^n√5

>### Logarithms:
>- log_k(x) = a == k^a = x
>- log_k(x): number of times we have to divide x by k before we reach 1. the base is k
>- log_k(ab)   = log_k(a) + log_k(b)
>- log_k(x^n)  =  n * log_k(x)
>- log_k(a/b)  = log_k(a) - log_k(b)
>- log_u(x)    =  log_k(x)/log_k(u)
>- ln(x) log whose base is e=2.71828

</details>
<details>
  <summary><h3> 2. Time complexity </h3></summary>

<!-- Add your notes or content for Time complexity here. -->

</details>

<details>
  <summary><h3>3. Sorting</h3></summary>

<!-- Add your notes or content for Sorting here. -->

</details>

<details>
  <summary><h3>4. Data Structures</h3></summary>

<!-- Add your notes or content for Data structures here. -->

</details>

<details>
  <summary><h3> 5. Complete Search </h3></summary>

<!-- Add your notes or content for Complete search here. -->

</details>

<details>
  <summary><h3>6. Greedy algorithms</h3></summary>

<!-- Add your notes or content for Greedy algorithms here. -->

</details>

<details>
  <summary><h3> 7. Dynamic Programming </h3></summary>

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