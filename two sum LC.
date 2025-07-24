#include<bits/stdc++.h>
using namespace std;
int main()
{
    int n;
    cin>>n;
    if(n>=2 && n<=1e4)
    {
        int arr[n],t;
        for(int i=0;i<n;i++)
        cin>>arr[i];
        cin>>t;
        if(t>=-1e9 && t<=1e9)
        {
        for(int i=0;i<n;i++)
        {
            for(int j=0;j<n;j++)
            {
                if(i!=j)
                {
                    if(arr[i]+arr[j]==t)
                    {
                    cout<<i<<" "<<j<<endl;
                    break;
                    }
                }            
        }
        }

    }
}
return 0;
}
