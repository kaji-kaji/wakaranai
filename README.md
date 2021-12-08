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

https://paiza.jp/works/mondai/steinsgate/quantity_of_experience_points_boss/edit?language_uid=java&t=612c716eea45f90e474c81c6fcaf9915
