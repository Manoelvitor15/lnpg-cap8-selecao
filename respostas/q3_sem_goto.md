j = -3;
for (i = 0; i < 3 && j <= 0; i++) {
    int switch_val = j + 2;

    if (switch_val == 3 || switch_val == 2) {
        j--;
    } else if (switch_val == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j <= 0) {
        j = 3 - i;
    }
}
