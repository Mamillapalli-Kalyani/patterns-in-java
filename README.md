# patterns-in-java
public class Main
{
	public static void main(String[] args) {
		int arr[][]=new int[2][2];
		arr[0][0]=1;
		arr[0][1]=1;
		arr[1][0]=1;
		arr[1][1]=1; 
		int arr2[][] = {{1,2,3},{1,2,3},{1,2,3}};
		for(int i=0;i<5;i++)
		{
		  for(int j=0;j<=i;j++)
		  {
		     System.out.print("* ");
		  }
		  System.out.println();
		}
	}
}
