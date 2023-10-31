#include<iostream>

using namespace std;

void Array_with_static_length()
{
    int arr[5];
    int arr_length = sizeof(arr) / sizeof(0);

    cout << " Enter Five Integer Numbers For Array : " << endl;

    for(int i = 0; i < arr_length; i++)
    {
        cout << " Enter Value For Index  " << i << " : ";
        cin >> arr[i];
    }

    cout << " Five Integer Numbers That You Entered : " << endl;

    for(int i = 0; i < arr_length; i++)
    {
        cout << " Value Of Index  " << i << " : ";
        cout << arr[i] << endl;
    }
}

void Arry_with_dynamic_length()
{
    int *arr, arr_length;

    cout << " How Many Size Of your Array Would Be? : " ;
    cin >> arr_length;
    cout << " Selected Length " << arr_length << endl;
    cout << " Now Enter " << arr_length << " Integer Numbers. " << endl;

    arr = new int[arr_length];

    for(int i = 0; i < arr_length; i++)
    {
        cout << " Enter Value For Index  " << i << " : ";
        cin >> arr[i];
    }

    for(int i = 0; i < arr_length; i++)
    {
        cout << " Value Of Index  " << i << " : ";
        cout << arr[i] << endl;
    }
}

int main()
{
    string option;

    while(option != "3")
    {
        cout << " 1. Array With Static Length. " << endl;
        cout << " 2. Array With Dynamic Length. " << endl;
        cout << " 3. Exit The Program. " << endl;
        cout << " What Do You Want To Do? " << endl;
        cin >> option;

        if(option == "1")
        {
            Array_with_static_length();
        }

        else if(option == "2")
        {
            Arry_with_dynamic_length();
        }

        else if(option == "3")
        {
            cout << " SUCCESSFULLY EXITED THE PROGRAM. " << endl;
            break;
        }

        else
        {
            cout << " You Entered Wrong Number " << endl;
        }
    }
}
