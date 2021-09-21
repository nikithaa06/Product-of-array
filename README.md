# Product-of-array
import java.util.Scanner;
public class ProductOfArrayJava {
    public static void main(String[]args)
    {
        int[]arr=new int[]{1,2,3,4,5};
        int product=1;
        for(int i=1;i<arr.length;i++){
            product=product*arr[i];
        }
        System.out.println("Product of all the elements of an array;"+product);
    }
}
