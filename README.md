#include <iostream>

// استخدام فضاء الأسماء القياسي لتسهيل الكتابة
using namespace std;

// دالة لحساب مجموع الأرقام من 1 إلى رقم معين
void calculateSum(int limit) {
    int total = 0;

    // استخدام فور لوب لحساب المجموع
    for (int i = 1; i <= limit; i++) {
        total += i; // إضافة قيمة i إلى المجموع في كل دورة
    }

    cout << "مجموع الأرقام من 1 إلى " << limit << " هو: " << total << endl;
}

int main() {
    int number;

    cout << "أدخل رقماً نهائياً لحساب المجموع: ";
    cin >> number;

    // استدعاء الفانكشن
    calculateSum(number);

    return 0;
}
