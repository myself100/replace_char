# replace_char

package elclipse;
import java.util.*;
public class replace_character {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		String x="Harsh gupta";      
		char c1='h'; 
		char c2='r';
		String e="";
		for(int i=0;i<x.length();i++) {
			if(x.charAt(i)==c1) {
				e=e+c2;                       //replacing the character
			}
			else {
				e=e+x.charAt(i);
			}
		}
		System.out.print(e);

	}

}

////time complexity is O(N);
