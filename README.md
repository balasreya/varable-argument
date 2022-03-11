# varable-argument
class A
{
    static void fun1(int a,int b)
    {
        System.out.println("non variable argument");
        System.out.println("enter the value of a");
        System.out.println("enter the value of b");
    }
    static void fun(int c)
    {
         System.out.println("variable argument");
         System.out.println("the length of c is"+c.length);
         System.out.println("the argument are ");
         
        
    }
}
class Main
{
        public static void main(String[]args)
        {
            A.fun1(20,30);
            A.fun(0);
            A.fun(22,33,44,55);
        }
}
