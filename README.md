# 1-lab
1 задание по информатике
#include <iostream>
using namespace std;
int main(){
    int n;
    cin>>n;  
    int m=n,p=0;  
    while (m>0){ 
        p = 10*p + m%10;  
        m = m/10;
    }
    if (m=n){          
        cout<<"yes";
    } 
    else {
        cout<<"no";
    };
    cout<<"\n";
    system("pause");
    return 0;
}
