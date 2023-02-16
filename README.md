# new-model-star-pyramid
#include<stdio.h>
void main()
{   
   
int n,i,k,str=1,mid;
printf("enter the limit:");      //             *
scanf("%d",&n);                  //            *2*
                                 //           *2*4*
 int lim=1,j;                    //          *2*4*6*

for(i=1;i<=n;i++){
   lim=lim+2;
 	
}
lim=lim-2;

mid=(lim/2)+1;
for(i=1;i<=n;i++){
	
	for(j=1;j<=lim;j++){
		printf(" ");
		if(j==mid){
			for(k=1;k<=str;k++){
	 	     if(k%2==1){
	 	     	printf("*");
			  }
			  else{
			  	printf("%d",k);
			  }
	      }
	    
		}
	 
	}
	mid=mid-1;
	str=str+2;
	printf("\n");
}
}
