```c
#include <iostream>
using namespace std;
void FastIO (){
    #ifndef ONLINE_JUDGE
    ios_base::sync_with_stdio(false) ,cin.tie(0) , cout.tie(0);
    freopen("input.txt", "r", stdin) , freopen("output.txt", "w", stdout);
    #endif
}
 
int main () {
    FastIO ();
    //int, long long, char, float and double
    int a;
    long long b;
    char c;
    float d;
    double e;
 
    cin >> a >> b >> c >> d >> e;
    cout << a << " " << b << " " << c << " " << d << e;
    return 0;
}
```
