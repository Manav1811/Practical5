# Practical5
package part1;
import java.util.*;
public class Practical5 {
	    public static void main(String[] args) {
	        Scanner sc=new Scanner(System.in);

	        System.out.println("Enter no of testcase :");
	        int t=sc.nextInt();
	        for(int i=0;i<t;i++) {
	            System.out.print("Enter string a :");
	            String a=sc.next();
	            System.out.print("Enter string b :");
	            String b=sc.next();
	            int p = a.length();
	            int q = b.length();
	            int n = 0;
	            int count = 0;

	            if (p > q) {
	                n = q;
	            } else {
	                n = p;
	            }
	            for (int j = 0; j < n-1; j++) {
	                if (a.charAt(j) == b.charAt(j)) {
	                    if (a.charAt(j + 1) == b.charAt(j + 1)) {
	                        count++;
	                    }
	                }
	            }
	            System.out.println(count);
	        }

	    	//Created by Manav_21CE063.
	    }
}

