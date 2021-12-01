#include <stdio.h>
#include <stdlib.h>

void pi(int num){

int i,x;

for(i = 0; i < num; num--){

    scanf("%d",&x);

if (x == 0){
printf("NULL\n");
}
else if (x % 2 == 0){
        printf("EVEN");
        if (x > 0)
        printf(" POSITIVE\n");
        else printf(" NEGATIVE\n");
}else if (x % 2 != 0){
        printf("ODD");
        if (x > 0)
        printf(" POSITIVE\n");
        else printf(" NEGATIVE\n");
}
}
}
