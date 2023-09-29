
#include <iostream>

using namespace std;

int main()
{
    cout<<"Hello World\n";
    int n;
    cin>>n;
    int arr[n][n];
    int count = 1;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=n;j++){
            arr[i][j]=count;
            count++;
        }
        cout<<"\n";
    }
    cout<<"resultant array\n";
     for(int i=1;i<=n;i++){
        for(int j=1;j<=n;j++){
           cout<<arr[i][j]<<"  ";
        }
        cout<<"\n";
    }
    int sum = 2;
    while(sum <= 2*n) {
        for(int i=1;i<sum;i++){
            if (i>=1 && i <=n){
            int j = sum-i;
            if (j>=1 && j <=n) {
            if (sum % 2 != 0){
            cout<<arr[i][j]<<" ";
                
            } else {
                cout<<arr[j][i]<<" ";
            }
            }
                
            }
        }
        sum=sum+1;
        
    }
    return 0;
}
