//# AI-UNIVERS-
//just a beginner , working from zero to end of my capacity .
#include <stdio.h>
int main(){
int day;
printf("enter the day number of day");
scanf("%d", &day);
switch(day){
case 1:
printf("monday");
break;
case 2:
printf("tuesday");
break;
case 3:
printf("wednesday");
break;
case 4:
printf("thursday");
break;
case 5:
printf("friday");
break;
case 6:
printf("saturday");
break;
case 7:
printf("sunday");
break;
default:
printf("invalid day"); 
}
return 0;

}
