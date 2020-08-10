# Family Science
### Code of getting your input:
```javascript
  var input = document.getElementById("input").value;
```
### Code for refreshing to a website:
```javascript
  window.location.href = input;
```
```html
<meta http-equiv="refresh" content="30;https://www.example.com"/>
```
```c++
#include <iostream>
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <time.h>
using namespace std;
int main(){
    cout <<"Enter the URL:";
    string url;
    cin >> url;
    const char* Url = url.c_str();
    ShellExecute ("open", Url, NULL, NULL);
    return 0;
}
```
