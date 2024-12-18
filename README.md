# finding-index-of-multiply-elements
this program will show you the index of same elements in array
#include <iostream>
using namespace std;

int main() {
    string letter[]={"h","k","l","k","g","i","k","o","k"};
    int size=sizeof(letter)/sizeof(letter[0]);
    string target="k";
    bool found=false;
    
    for(int i=0;i<size;++i){
        if(letter[i]==target){
            cout<<i;
            found=true;
        }
    }
    if(!found){
        cout<<"elements not found";
    }
    cout<<endl;
     

    return 0;
}
