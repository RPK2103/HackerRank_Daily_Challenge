#include <bits/stdc++.h>
using namespace std;
typedef long long ll;
int main(){
    ll arr[5],sum,mn,mx,cur;
    sum=0;
    mn=LLONG_MAX;
    mx=LLONG_MIN;
    for(int i=0;i<5;i++)
    {
        cin>>arr[i];
        sum+=arr[i];
    }
    for(int i=0;i<5;i++)
    {
        cur=sum-arr[i];
        mn=min(mn,cur);
        mx=max(mx,cur);
    }
    cout<<mn<<" "<<mx<<endl;
}
