#include <stdio.h>
int main() {
    char s[50], c;
    int i,count = 0;

    printf("Enter a string: ");
    fgets(s, sizeof(s), stdin);

    printf("Enter a character to find its frequency: ");
    scanf("%c", &c);

    for ( i=0; s[i]!='\0'; ++i) {
        if (c == s[i])
            ++count;
    }

    printf("Frequency of %c = %d", c, count);
    return 0;
}
