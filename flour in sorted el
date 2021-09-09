#include<bits/stdc++.h>
using namespace std;
int bt(int a[],int l,int r,int s)
{
     
    int m=l+(r-l)/2;
    
    if(l<r){
        
        if(a[m]<s&&a[m+1]>s)
         return m;
        else if(s<a[m])bt(a,l,m-1,s);
        else bt(a,m+1,r,s);
        
    }
    
    
    
}




int main()
{
    
    int n;cin>>n;int s;cin>>s;int a[n];
    for(int i=0;i<n;i++)
    {
        cin>>a[i];
    }
    
    // for(int i :a)cout<<i<<" ";
   
  
    
    cout<<a[bt(a,0,n-1,s)];
 }
