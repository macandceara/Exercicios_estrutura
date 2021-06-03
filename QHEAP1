import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        PriorityQueue<Integer> heap = new PriorityQueue<Integer>();
        int Q = leitor.nextInt();
        while(Q --> 0){
            int Q1 = leitor.nextInt();
            if(Q1==1){
                int num = leitor.nextInt();
                heap.add(num);
            }else if(Q1==2){
                int num = leitor.nextInt();
                heap.remove(num);
            }else if(Q1==3){
                System.out.println(heap.peek());
            }
        }
    }
}
