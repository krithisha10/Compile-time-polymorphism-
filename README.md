package main;

public class Main {
    public int addition(int x, int y){
        return x+y;
    }
    public int addition(int x, int y, int z){
        return x+y+z;
    }
    public double addition(double x, double y){
        return x+y;
    }
    public static void main(String[] args) {
        // TODO code application logic here
        Main number=new Main();
        int res1=number.addition(444,555);
        System.out.println("Addition of two integers:"+res1);
        int res2=number.addition(333,444,555);
        System.out.println("Addition of three integers:"+res2);
        double res3=number.addition(10.15,20.22);
        System.out.println("Addition of two doubles:"+res3);
    }

    OUTPUT:-
Addition of two integers:999
Addition of three integers:1332
Addition of two doubles:30.369999999999997
