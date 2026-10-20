# -program-to-count-positive-negative-and-zero-elements-in-an-array.
#include<iostream>
  using namespace std;
    int main(){
        int n;
        cout<<"enter the size of array ";
        cin>>n;
        
        int arr[n];
        for(int i=0;i<n;i++){
            cout<<"enter the elements of array"<<i+1<<" : ";
            cin>>arr[i];
        }
        
        cout<<"elements are : "<<"\n";
        for(int i=0;i<n;i++){
            cout<<arr[i]<<" "<<"\n";
        }
        
            for(int i=0;i<n;i++){
                if(arr[i]>0){
                    cout<<"positive"<<"\n";
                }
                else if(arr[i]<0){
                    cout<<"negative"<<"\n";
                }
                else
                cout<<"zero"<<"\n";
            }
            
            return 0;
            
        }
