
import java.io.*;

import java.util.*;

public class Main {

public static void main(String[] args) throws Exception { // write your code here

Scanner sc = new Scanner(System.in); int n = sc.nextInt();

int arr[] = new int[n];

for(int i=0; i < n; i++) { arr[i] sc.nextInt();

} int max maxOfArray(arr, 0); System.out.println(max);

}

public static int maxOfArray(int[] arr, int idx) {

Arrays.sort(arr);

return arr[arr.length - 1];
