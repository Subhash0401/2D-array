import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    int row = sc.nextInt();
	    int col = sc.nextInt();
	    int [][] arr = new int[row][col];
	    int i,j;
	    for(i=0;i<row;i++){
	        for(j=0;j<col;j++)
	        {
	            arr[i][j] = sc.nextInt();
	        }
	        System.out.println(arr[0][2]);
		
	}
}
}
