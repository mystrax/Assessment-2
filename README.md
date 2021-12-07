# Assessment-2

    #include <iostream> 
    #include <string>
    #include <cmath>
    using namespace std;
    int main()
    {
        int input{};
        string name{};
        long double factorial = 1.0;
        cout << "Enter your name: ";
        cin >> name;
        getline(cin, name);
        cout << "Enter a number: ";
        cin >> input;
        {
            int i = 1;
            while (i <= 10)
            {
                cout << input << " * " << i << " = " << input * i << "\n";
                i++;
            }
        }
        for (int i = 1;i <= input;i++) {
            factorial *= i;
            cout << "Factorial of " << input << " = " << factorial << "\n";
            break;
        }
        {
            int j = 1;
            do {
                cout << input << " to the power of " << j << " is: " << pow(input, j) << "\n";
                j++;
            } while (j < 11);
            return 0;
        }
    }
