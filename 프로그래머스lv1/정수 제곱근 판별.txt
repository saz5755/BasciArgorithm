using System;
public class Solution {
    public long solution(long n) {
        long x = (long)Math.Sqrt(n);
            return (x*x == n) ? (x+1)*(x+1) : -1;
    }
}