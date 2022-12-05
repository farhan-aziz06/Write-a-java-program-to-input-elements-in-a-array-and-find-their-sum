# Write-a-java-program-to-input-elements-in-a-array-and-find-their-sum
Write a java program to input % elements in a array and find their sum



      import java.util.Scanner;

      public class arrays {
          public static void main (String [] args){
              Scanner console = new Scanner(System.in);
              int [] array = new int[5];
              System.out.println("Enter Array Element:");
              for (int i =0; i< array.length;i++){
                  array[i]= console.nextInt();
              }
              System.out.println("Sum of the given array is... "+sum(array));
          }
          public static int sum(int[]arr){
              int sum=0;
              for (int x:arr)
                  sum+=x;
              return sum;
          }
      }
