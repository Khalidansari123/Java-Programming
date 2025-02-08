import java.util.*;
public class App{

    static  int balance = 1000;

    static void deposite(int amt){
        if(amt>0){
        balance=balance+amt;
        System.out.println("Money is Deposited succefully...");
        System.out.println("----------------------------------------------");
        }
        else{
            System.out.println("Sorry this is not deposted because your deposite amount is zero");
        }

    }
    static void withdraw(int amt){
        if(balance>amt){
        balance=balance-amt;
        System.out.println("Money Withdraw succefully.......");
        System.out.println("--------------------------------------------------");
        }
        else{
            System.out.println("Sorry does not sufficient balance in your acount please deposite money");
            System.out.println("----------------------------------------------------------------------------");
        }

    }
    static void display(int amt){

        System.out.println("current balance in your account : "+amt+"rs");
        System.out.println("------------------------------------------------");
    }
    public static void main(String[] args) {
        Scanner ammount=new Scanner(System.in);
        while (true) { 
        System.out.println("----Select Choice----");
        System.out.println("Press 1 for deposit money in your Acount");
        System.out.println("Press 2 for withdraw money from your acount");
        System.out.println("Press 3 for know your current balance of your acount");
        int choice=ammount.nextInt();
        //2int choice=2;
        if(choice==1){
        System.out.println("Enter Deposite money : ");
        int amount=ammount.nextInt();
        deposite(amount);
        }
        else if(choice==2){
        System.out.println("Enter money you want to withdraw : ");
        int withdraw=ammount.nextInt();
        withdraw(withdraw);
        }
        else if(choice==3){
        display(balance);
        }
        else{
            System.out.println("Please select vailide choice");
        }
        }
    }
}
