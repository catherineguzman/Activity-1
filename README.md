# Activity 1-3

#include <iostream>
using namespace std;

int main() {
    
    int i = 0;
    while (i <= 10) {
        cout << i << endl;
        i++;  
    }

    
    int j = 10;
    while (j >= 0) {
        cout << j << endl;
        j--;  
    }

    return 0;
}


#include <iostream>
using namespace std;

int main() {
    int num, sum = 0;

    cout << "Enter integers (enter 0 to stop):" << endl;
    cin >> num;

    while (num != 0) {
        if (num > 0) {
            sum += num;  // add only positive numbers
        }
        cin >> num;
    }

    cout << "Sum of positive integers: " << sum << endl;

    return 0;
}


#include <iostream>
using namespace std;

int main() {
    int product = 1;
    int i = 1;

    while (i <= 5) {
        product *= i;  // Multiply product by i
        i++;           // Increment i
    }

    cout << "The product of numbers from 1 to 5 is: " << product << endl;

    return 0;
}
