#include <stdio.h>
Int main() {
Int patient[3] =
{101,102,103};
Int priority[3] = {2,1,3};
Int I,j,temp;
For(i=0;i<3;i++){
For(j=i+1;j<3;j++){
If(priority[i] >
priority[j]){
Temp = patient[i];
Patient[i] =
patient[j];
Patient[j] = temp;
}
}
}
Printf(“Patient treatment
order:\n”);
For(i=0;i<3;i++){
Printf(“Patient ID:
%d\n”,patient[i]);
}
Return 0;
}
16
OUTPUT
Patient treatment order:
Patient ID: 102
Patient ID: 101
Patient ID: 103
