#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;

int main() {
    int N, j=0, z=0, h=0, l=0;
    cin >> N;
    int nr[N];
    for (int i=0; i<N; i++){
        cin >> nr[i];
    }
    while (j<N){
        if (nr[j]>0){
            h++;
        }
        if (nr[j]<0){
            l++;
        }
        else if (nr[j]==0) {
            z++;
        }
        j++;
    }
    cout << (float)h/N << endl << (float)l/N << endl << (float)z/N;
    return 0;
}
