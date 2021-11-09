# s1_Jake-Laurence-De-Guzman-Paz-Resubmission

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        char choice;
        string input;
        cout << "Please enter your full name:" << endl;
        getline(cin, input);

        int num;
        cout << "Please enter your age: From 16-30 only." << endl;
        cin >> num;

        while (cin.fail()) {
            cin.clear();
            cin.ignore(31, '\n');
            cout << "You are above the age limit, please try again." << endl;
            cin >> num;
        }

        switch (num) {
        case 16:
            cout << "Do you wanna go to the mall?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 17:
            cout << "Do you wanna go to the mall?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 18:
            cout << "Do you wanna go to the mall?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 19:
            cout << "Do you wanna go to the theme park?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 20:
            cout << "Do you wanna go to the theme park?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 21:
            cout << "Do you wanna go to the theme park?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 22:
            cout << "Do you wanna go to on a trip to Istanbul?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 23:
            cout << "Do you wanna go to on a trip to Istanbul?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 24:
            cout << "Do you wanna go to on a trip to Istanbul?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 25:
            cout << "Do you wanna go to on a trip to Istanbul?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 26:
            cout << "Do you wanna go on a trip to Hawaii?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 27:
            cout << "Do you wanna go on a trip to Hawaii?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 28:
            cout << "Do you wanna go on a trip to Hawaii?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 29:
            cout << "Do you wanna go on a trip to Hawaii?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        case 30:
            cout << "Do you wanna go on a trip to Hawaii?" << endl;
            cout << "Please press 'y' to enjoy and please press 'n' to cancel." << endl;
            cin >> choice;
            break;

        default:
            cout << "Invalid" << endl;
            break;

        }

        if (choice == 'Y' || choice == 'y') {
            cout << "Enjoy.\n" << endl;

        }
        else if (choice == 'N' || choice == 'n') {
            cout << "Cancelled.\n" << endl;

        }else{
            cout << "Invalid" << endl;

        }
        return 0;



    }
