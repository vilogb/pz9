# pz9
![Alt text](URL to image "Optional title").
<img width="1646" height="745" alt="Снимок экрана 2026-03-19 134329" src="https://github.com/user-attachments/assets/a25ec8a5-fcc6-46ac-bcbf-03bdfd73b3d6" />
Задание 1

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    if (n == 1) {
        cout << "Один" << endl;
    } else if (n == 2) {
        cout << "Два" << endl;
    } else if (n == 3) {
        cout << "Три" << endl;
    } else {
        cout << "Ошибка" << endl;
    }

    return 0;
    }

   Задание 2

     #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    if (n == 1) {
        cout << "Понедельник" << endl;
    } else if (n == 2) {
        cout << "Вторник" << endl;
    } else if (n == 3) {
        cout << "Среда" << endl;
    } else if (n == 4) {
        cout << "Четверг" << endl;
    } else if (n == 5) {
        cout << "Пятница" << endl;
    } else if (n == 6) {
        cout << "Суббота" << endl;
    } else if (n == 7) {
        cout << "Воскресенье" << endl;
    } else {
        cout << "Неверный день" << endl;
    }

    return 0;
    }
  Задание 3

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    if (n == 12 || n == 1 || n == 2) {
        cout << "Зима" << endl;
    } else if (n >= 3 && n <= 5) {
        cout << "Весна" << endl;
    } else if (n >= 6 && n <= 8) {
        cout << "Лето" << endl;
    } else if (n >= 9 && n <= 11) {
        cout << "Осень" << endl;
    } else {
        cout << "Ошибка" << endl;
    }

    return 0;
    }

  Задание 4

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    char op;
    int a, b;
    cin >> op >> a >> b;

    switch(op) {
        case '+':
            cout << a + b << endl;
            break;
        case '-':
            cout << a - b << endl;
            break;
        case '*':
            cout << a * b << endl;
            break;
        case '/':
            if (b == 0) {
                cout << "Деление на ноль" << endl;
            } else {
                cout << a / b << endl;
            }
            break;
        default:
            cout << "Ошибка" << endl;
    }

    return 0;
    }
  Задание 5

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    switch(n) {
        case 1: cout << "Плохо"; break;
        case 2: cout << "Плохо"; break;
        case 3: cout << "Удовлетворительно"; break;
        case 4: cout << "Хорошо"; break;
        case 5: cout << "Отлично"; break;
        default: cout << "Ошибка";
    }



    return 0;
    }

  Задание 6

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int n;
    cin >> n;

    // Ваш код:
    switch(n) {
        case 0: cout << "Ноль"; break;
        case 1: cout << "Один"; break;
        case 2: cout << "Два"; break;
        case 3: cout << "Три"; break;
        case 4: cout << "Четыре"; break;
        case 5: cout << "Пять"; break;
        case 6: cout << "Шесть"; break;
        case 7: cout << "Семь"; break;
        case 8: cout << "Восемь"; break;
        case 9: cout << "Девять"; break;
        default: cout << "Ошибка";
    }

    return 0;
    }

  Задание 7

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int a, b;
    int op;
    cin >> a >> b >> op;

    switch(op) {
        case 1:
            cout << a + b; break;
        case 2:
            cout << a - b; break;
            
        case 3:
            cout << a * b; break;
            
        case 4:
            if (b == 0) cout << "Деление на ноль"; 
            else cout << a / b; break; 
            
        default: cout << "Ошибка"; break;
    }

    return 0;
    }
    
