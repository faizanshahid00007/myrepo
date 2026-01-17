#FUNCTIONS 
QUES-1 
import java.util.Scanner;
class function{
    public static int add(int x){
        if(x>0) return x;
        return Math.abs(x);
    }
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();
        System.out.println("x is this :"+x);
        System.out.print(add(x)+10);
    }
}

