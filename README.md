#include<iostream>  
#include <iomanip>  
using namespace std;  
   
int main() //執行結束時, 會傳回一個整 數值到作業系統 
{  
    int n; //聲明n這個變量 
    while(cin>>n){  //將輸入的數值傳至n
    double ans=n*1.6; //將n乘上1.6之後存到ans   
    cout<<fixed<<setprecision(1)<<ans<<"\n"; //將ans的值輸出到控制台，且設置輸出為小數點後一位  
    }  
       
    return 0; //結束程式返回0     
}  
