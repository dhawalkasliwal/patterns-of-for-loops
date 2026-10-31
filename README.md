# patterns-of-for-loops
pyramid like patterns
import java.util.*;

public class Main {
    public static void main(String[] args){
Scanner sc = new Scanner(System.in);
int n = sc.nextInt();
int m = sc.nextInt();
pattern1(n,m);
    }
 static void pattern1(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = 1;j <= i;j++){
    System.out.print("*");    
    }
    System.out.println();
}
    }
 static void pattern2(int n,int m){
for(int i = 1;i <= n;i++){
    for(int j = m;j >= i;j--){
    System.out.print("*");    
    }
    System.out.println();   
}
}
static void pattern3(int n,int m){
for(int i = 1;i <= n;i++){
    for(int j = 1;j <= n - i;j++){
    System.out.print(" ");
 }
    for(int j = 1;j <= i;j++){
    System.out.print("*");    
    }
    System.out.println();
}
    
}
static void pattern4(int n,int m){
for(int i = 1; i <= n;i++){
    for(int j = 1;j <= i - 1;j++){
        System.out.print(" ");
    }
    for(int j = 1;j <= n - i + 1;j++){
    System.out.print("*");    
    }
    System.out.println();
}
    }
  static void pattern5(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = 1;j <= i;j++){
    System.out.print(j);    
    }
    System.out.println();
}  

}
static void pattern6(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = 1;j <= n - i + 1;j++){
    System.out.print(j);    
    }
    System.out.println();
}
}
static void pattern7(int n,int m){
    int sum = 0;
for(int i = 1; i <= n;i++){
for(int j = 1;j <= i;j++){
    sum++;
    System.out.print(sum + " ");    
    }
    System.out.println();
}
}
static void pattern8(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = 1;j <= i;j++){
    if((i + j)%2==0){
        System.out.print("1" + " ");
    } else{
        System.out.print("0" + " ");
    } 
    }
    System.out.println();
}
}
static void pattern9(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = 1;j <= i;j++){
    System.out.print("*"); 
}
for(int j = 1;j <= m - 2*i;j++){
    System.out.print(" ");
}
for(int j = 1;j <= i;j++){
    System.out.print("*");
}
    System.out.println();
}
for(int i = n; i >= 1;i--){
for(int j = 1;j <= i;j++){
    System.out.print("*"); 
}
for(int j = 1;j <= m - 2*i;j++){
    System.out.print(" ");
}
for(int j = 1;j <= i;j++){
    System.out.print("*");
}
    System.out.println();
}
}
static void pattern10(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = n;j >= i ;j--){
   System.out.print(" ");
}
for(int j = 1;j <= n;j++){
    System.out.print("*");
}
for(int j = 1;j <= i;j++){
    System.out.print(" ");
}
    System.out.println();
}
}
static void pattern11(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = 1;j <= n - i;j++){
    System.out.print(" ");    
    }
    for(int j = 1;j <= i;j++){
        System.out.print(i + " ");
    }
    System.out.println();
}
}
static void pattern12(int n,int m){
    
for(int i = 1; i <= n;i++){
for(int j = 1;j <= n - i;j++){
    System.out.print(" ");    
    }
    for(int j = i;j >= 1;j--){
        
        System.out.print(j + " ");
    }
    for(int j = 2;j <= i ;j++){
        
        System.out.print(j);
    }
    System.out.println();
}
}
static void pattern13(int n,int m){
for(int i = 1; i <= n;i++){
for(int j = 1;j <= n - i;j++){
    System.out.print(" ");    
    }
    for(int j = 1;j <= i;j++){
        System.out.print("*" + " ");
    }
    System.out.println();
}
for(int i = n; i >= 1;i--){
for(int j = 1;j <= n - i;j++){
    System.out.print(" ");    
    }
    for(int j = 1;j <= i;j++){
        System.out.print("* " );
    }
    System.out.println();
}
}
}
