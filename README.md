# nestedforloop1

public class loop1 {
    public static void main(String[] args) {
        int i;
        int j;
        for(i = 1; i<=7; i++) {
            //System.out.println(i);
            for(j = 1; j<=i; j++){
                System.out.print(i);
            }
            
            System.out.println();
        }

    }
}
