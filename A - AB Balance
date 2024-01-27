#include<bits/stdc++.h>
using namespace std;
#define optimized() ios_base::sync_with_stdio(0);cin.tie(0);cout.tie(0);
#define endl '\n'

int main() {
    optimized();
    int t;
    cin>>t;
    while(t--){
        int ab=0,ba=0;
        string s;
        cin>>s;
        map<string,int>mp;
        for(int i=0;i<s.size();i++){
            if(s[i]=='a'&& s[i+1]=='b'){
                    ab++;
            }
        }
        for(int i=0;i<s.size();i++){
            if(s[i]=='b'&& s[i+1]=='a'){
                    ba++;
            }
        }
        if(ab==ba){
            cout<<s<<endl;
        }
        else if(ab>ba){
                s[0]='b';
                cout<<s<<endl;
            }
        else {
            s[0]='a';
            cout<<s<<endl;
        }
    }
    return 0;
}

