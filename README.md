import java.util.Scanner;
class Linearsearch
{
    public static void main(String[] args)
    {
      int a[]=new int[5];
      Scanner r=new Scanner(System.in);
      for(int i=0;i<5;i++)
      {
        a[i]=r.nextInt();
      }
      System.out.println("Array elements");
      for(int i=0;i<5;i++)
      {
        System.out.println(a[i]+" ");
      }
      System.out.println("Enter the elements  to be searched");
      int ele=r.nextInt();
      int flag=0;
      for(int i=0;i<5;i++)
      {
         if(a[i]==ele)
         {
           flag=1;
         }
     }
     if(flag==1)
     {
       System.out.println("Successful");
     }
     else
      {
          System.out.println("Search Unsucessful");
      }
   }
}
