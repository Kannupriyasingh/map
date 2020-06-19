#include <iostream>
#include<bits/stdc++.h>

using namespace std;

int main()
{ int n;
  cin>>n;
  map<int ,int>m;
  for(int i=0;i<n;i++)
  {   int a;
      cin>>a;
      m[a]++;
  }
  for(auto i:m)
  {
      cout<<i.first<<":"<<i.second<<" ";
  }
    return 0;
}
