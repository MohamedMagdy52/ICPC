### A Say Hello With C++

```c
#include <iostream>
#include <iomanip>
#include <string>
#include <cmath>
#include <algorithm>
#include <stdio.h>
 
using namespace std;
 
#define ll long long
#define sz(x) int(x.size())
#define all(vec) vec.begin(),vec.end()
#define rall(vec) vec.rbegin(),vec.rend()
 
 
void FastIO (){
    #ifndef ONLINE_JUDGE
    ios_base::sync_with_stdio(false) ,cin.tie(0) , cout.tie(0);
    freopen("input.txt", "r", stdin) , freopen("output.txt", "w", stdout);
    #endif
}
/*
 
*/
```
mainly the solution is in solve function

```c
void solve()
{
    string name;
    cin >> name;
    cout << "Hello, "+name ;
}
```

```c
int main () {
    FastIO ();
    int t=1;
    //cin >> t;
    while(t--)
       solve();
    return 0;
}
```
