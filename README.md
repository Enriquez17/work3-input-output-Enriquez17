import java.io.*; 
2 class project3ioBonus{ 
3 	public static void main(String[]args){ 
4 		System.out.println("Hello Everyone!"); 
5 		InputStreamReader j = new InputStreamReader(System.in); 
6 		BufferedReader v = new BufferedReader(j); 
7 		System.out.println("Enter height of the triangle:"); 
8 		double height =0.0 
9 		try{ 
10 			height=Integer.valueof(v.readLine()); 
11 		} 
12 		catch(Exception p){ 
13 			System.out.println("Invalid number!") 
14 		} 
15 		for(int a=1; a<=height; a++){ 
16 			for(int b=1; b<height -(a-1); b++){ 
17 				System.out.print(" "); 
18 			} 
19 			for(int c=1; c<=a; c++){ 
20 				System.out.print("*"); 
21 				for(int j1=1; j1<c; j1+=c){ 
22 				System.out.print("*"); 
23 				} 
24 			} 
25 			System.out.println(""); 
26 			 
27 		} 
28 	} 
29 } 

