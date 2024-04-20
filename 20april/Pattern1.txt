public class Pattern_1
{
public static void main(String args[])
{
int i,j,k=0;
int n=6;
for(i=1;i<=n;i++)
{
   for(j=i;j<n;j++)
System.out.println(" ");

while(k !=(2*i-i))
{

if(k==0 || k == 2 * i-2)
System.out.println("*");
else 
     System.out.print("");
  k++;

}

k=0;

System.out.println();

}

// printl last row 
 for(i=0; i<2*n-1;i++)
System.out.println("*");

}

}