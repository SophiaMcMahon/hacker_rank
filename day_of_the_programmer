#include <stdio.h>
#include <stdbool.h>

bool is_leap_year(int year) {
    if (year <= 1917) {
        return year % 4 == 0;
    } else {
        return (year % 400 == 0) || (year % 4 == 0 && year % 100 != 0);
    }
}

void dayOfProgrammer(int year) {
    int day, month;

    if (year == 1918) {
        day = 26;
        month = 9;
    } else {
        if (is_leap_year(year)) {
            day = 12;
        } else {
            day = 13;
        }
        month = 9;
    }

    printf("%02d.%02d.%d\n", day, month, year);
}

int main() {
    int year;
    scanf("%d", &year);

    dayOfProgrammer(year);

    return 0;
}
