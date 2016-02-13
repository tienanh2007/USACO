# USACO
practice for USACO
/* 
LANG: JAVA
TASK: ride
*/

import java.io.File;
import java.io.IOException;
import java.io.PrintWriter;
import java.util.Scanner;


class ride {
		public static void main(String[] args) throws IOException {
			Scanner in = new Scanner(new File("ride.in"));
			PrintWriter pw = new PrintWriter(new File("ride.out"));
			String comet = in.next();
			String group = in.next();
			int Comet  = Ride(comet)%47;
			int Group = Ride(group)%47;
			if(Comet==Group){
				pw.println("GO");
			}
			else{
				pw.println("STAY");
			}
			pw.close();
		}
		public static int Ride(String a){
			int sum  =  1;
			int len = a.length();
			for(int i=0;i<len;i++){
				int val = a.charAt(i)-'A'+1;
				sum = sum * val;
			}
			return sum;
		}
}
