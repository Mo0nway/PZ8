# PZ8
<img width="1912" height="1081" alt="2026-03-19_11-01-04" src="https://github.com/user-attachments/assets/5cba088b-781c-4443-8d2d-192ce686029f" />

Задание 1

#include <iostream>

using namespace std;

int main() {
    setlocale(LC_ALL, "Russian");

    int number; 
    cin >> number; 

    if (number > 0) {
        cout << "Положительное" << endl;
    }

    return 0;
}


Задание 2

#include <iostream>

using namespace std;

int main() {
    int number; 
    cin >> number; 

    if (number == 10) {
        cout << "Число равно 10" << endl;
    } else {
        cout << "Число не равно 10" << endl;
    }

    return 0; 
}


Задание 3

#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    if (number < 0) {
        cout << "Число отрицательное" << endl;
    } else {
        cout << "Число не отрицательное" << endl;
    }

    return 0;
}


Задание 4

#include <iostream>

using namespace std;

int main() {
    int a, b; 
    cin >> a >> b; 

    if (a > b) {
        cout << "Большее число: " << a << endl;
    } else if (a < b) {
        cout << "Большее число: " << b << endl;
    } else {
        cout << "Числа равны" << endl;
    }

    return 0;
}


Задание 5

#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    if (number >= 1 && number <= 10) {
        cout << "Число принадлежит диапазону" << endl;
    } else {
        cout << "Число не принадлежит диапазону" << endl;
    }

    return 0;
}


Задание 6

#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    if ((number >= 1 && number <= 5) || (number >= 10 && number <= 15)) {
        cout << "Число принадлежит одному из диапазонов" << endl;
    } else {
        cout << "Число не принадлежит указанным диапазонам" << endl;
    }

    return 0;
}


Задание 7

#include <iostream>

using namespace std;

int main() {
    int number;
    cin >> number;

    if (number > 0 && number % 2 == 0 && number < 100) {
        cout << "Подходит" << endl;
    } else {
        cout << "Не подходит" << endl;
    }

    return 0;
}
