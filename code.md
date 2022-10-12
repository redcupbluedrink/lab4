#include <stdio.h>
#include <math.h>

/* 1

int main() {
	
	int s, n, i; 
    printf("VVedite n: ");    scanf("%d",&n); 
	for (s = 0, i=1; i<=n; i++)  
		s += i;	
	printf("%d", s);
	
}
*/

/* 2
int main() {

	int n, i;
	float s;
    printf("VVedite n: ");    scanf("%d",&n); 
	for (s = 0, i = 1; i <= n; i++)  
		s += sin(i);	
	printf("%.3f", s);
	
}
*/

/* 3
int main() {

	int n, i;
	float s;
    printf("VVedite n: ");    scanf("%d",&n); 
	for (s = 0, i = 1; i <= n; i++)  
		s += tan(i*2);
	printf("%.1f", s);
	
}
*/

/* 4
int main() {

	float n;
	float i;
	float s;
    printf("VVedite n: ");    scanf("%f",&n); 
	for (i=0.1; i<=n; i=i+0.2) {
		s+=log(i); 
	}
	printf("%.3f", s);

}
*/

/* 5
int main() {
	
	int x,v;
    float s,i;
    printf("Vvedite x: ");    scanf("%d",&x);
    v=1;
    for (s=0, i=0.18; i<=0.36; i=i+0.02) {
		s+=pow((i*x),v);  
		v+=1 ; 
	}
    printf ("x = %d s = %.3f",x,s);
    
}
*/

/* 6
int main() {
	
	int s,n,i,x;
     printf("Vvedite n:  ");    scanf("%d",&n);
     x=1;
     for (i=1; i<=n; i++) {
            s+=i*x;
			x*=-1;
		}
     printf ("s = %d\n",s);
     
}
*/

/* 7
int main() {
	
	int p,n,i,m;
    printf("Vvedite m: ");    scanf("%d",&m);
    for (p=1, i=1; i<=m; i++) 
        p*=i;
			
     printf ("p = %d",p);
	
}
*/

/* 8
int main() {

	int p, n, i, s;
	printf("Vvedite n: ");    scanf("%d",&n);
    for (s = 1, i=2; i<=n; i+=2) {
		s*=i;
	}		
    printf ("s = %d",s);
	
}
*/

/* 9
int main() {
	
	float n, i;
	float s;
	int v = 1;
	int x =5;
	int a;
	printf("Vvedite n: ");    scanf("%f",&n);
    for (s = 1, i=1; i<=n; i++) {
    	for (v = 1, a = 1; a <= i; a++){
    		v *= a;
		}
		s += ((pow(x,i))/(v));
	}		
    printf ("s = %.2f",s);
	
}
*/
