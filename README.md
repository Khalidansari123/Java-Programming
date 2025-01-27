public class Main
{
	public static void main(String[] args) {
		int n=8;
		for(int i=1;i<=n;i++){
		    for(int j=i;j<=n;j++){
		        System.out.print(" ");
		    }
		    for(int j=1;j<=i;j++){
		        System.out.print("*");
		    }
		    
		    for(int j=1;j<=i-1;j++){
		        System.out.print("*");
		    }
		    for(int j=i;j<=n;j++){
		        System.out.print(" ");
		    }
		    System.out.println();
		}
		
	      for(int i=1;i<=17;i++){
	          System.out.print("*");
	      }
	      System.out.println();
		  
		for(int i=1;i<=n;i++){
		    
		    for(int j=1;j<=i;j++){
		        System.out.print(" ");
		    }
		    for(int k=1;k<=n-i;k++){
		        System.out.print("*");
		    }
		     for(int k=1;k<=n-i+1;k++){
		        System.out.print("*");
		    }
		    for(int l=1;l<=i;l++){
		        System.out.print(" ");
		    }
		    System.out.println();
		}
		
	}
}
