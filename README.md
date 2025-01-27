public class Main
{
	public static void main(String[] args) {
		int n=6;
		for(int i=1;i<=n;i++){
		    for(int j=1;j<=i;j++){
		        System.out.print("*");
		    }
		    for(int k=1;k<=n-i;k++){
		        System.out.print(" ");
		    }
		     for(int k=1;k<=n-i;k++){
		        System.out.print(" ");
		    }
		    for(int l=1;l<=i;l++){
		        System.out.print("*");
		    }
		    System.out.println();
		}
	}
}
//output star v pattern print
![Screenshot 2025-01-27 204134](https://github.com/user-attachments/assets/87779278-90a5-453e-bb1e-e3f04d2760dc)
