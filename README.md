// Using-bool-to-check-a-prime-number-in-C++

#include<iostream>

using namespace std;

// 0 -> not a prime number
// 1 -> a prime number

bool isPrime(int n)
{
    for(int i=2;i<n;i++)
    {
        if(i%2==0)
        {
            return 0;
        }
    }
    return 1;
}

int main()
{

    int n;
    cin >> n;
    if(isPrime(n))
    {
        cout<<"Is a prime Number " <<endl;
    }
    else
    {
        cout<<"Not a prime Number "<<endl;
    }

}

