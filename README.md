# BitwiseclearithBit
here is a code of BitwiseclearithBit in java.



public class BitwiseclearithBit {
    public static int clearibit(int n,int i){
        int bitmask =~(1<<i);
        return n&bitmask;
    }
    public static int upatebit(int n,int i, int newbit) {
        n=clearibit(n, i);
        int bitmask =newbit<<i;
        return bitmask|newbit;
        
    }
public static void main(String[] args) {
    System.out.println(upatebit(4, 4,1));
}
}

