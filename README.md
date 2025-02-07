// программа для Яндекс Практикум

// Считайте стороны треугольника - три числа int.
// Выведите тип треугольника.
int a, b, c;
    cin >> a >> b >> c;
 

    // Определение вида треугольника
    if (a == b && b == c) {
        cout << "equilateral triangle" << endl;
    }
    else if (a >= b + c || b >= a + c || c >= a + b) {
        cout << "incorrect triangle" << endl;
     
    }

    else if (a == b || b == c || a == c) {
        cout << "isosceles triangle" << endl;
    } else {
        cout << "common triangle" << endl;
    }

