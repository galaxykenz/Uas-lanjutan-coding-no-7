public class Main {
    public static void main(String[] args) {
        int n = 6;
        int i,j;
        for (i = 0; i < n; i++) {
            for (j = 0; j <= n-i; j++) {
                System.out.print(" ");
            }
            for (int k = 0; k <= i; k++) {
                System.out.print(k);
            }
            System.out.println();
        }}
}
