//square star pattern print code in java
public class Main
{
	public static void main(String[] args) {
		int n=4;//this is for rows
		int m=5;//this is for columns
		//outer loop for rows
		for(int i=1;i<=n;i++){
		    //inner loop for columns
		    for(int j=1;j<=m;j++){
		        //print here Star 
		        System.out.print("*");
		    }
		    System.out.println();
		}
	}
}
