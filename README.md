import java.util.Arrays;
public class MinNumberFinder {
    public static void main(String[] args){
        int arr[]={12,34,56,78,13,45,12,13,1,2,2};
        int arr1[]=new int[arr.length];
        Arrays.sort(arr);
        int count=0;
        for(int i=0;i<arr.length-1;i++){
            if(arr[i]!=arr[i+1]){
            arr1[count]=arr[i];
            count++;
            }
        }
        arr1[count]=arr[arr.length-1];
        for(int i=0;i<count;i++){
            System.out.print(arr1[i]+" ");
        }
        System.out.println();
    }
}
