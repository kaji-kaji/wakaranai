import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        double k = sc.nextDouble();
        double sum = 0;
        for(int i = 0; i < n; i++){
            double x = sc.nextDouble();
            sum += x;
        }
       
        if(sum % k == 0){
            System.out.println((int)(sum / k));
        }else{
             System.out.println((int)(sum / k) + 1);
        }
    }
}

性能解析タイプセーフ (paizaランク C 相当)
