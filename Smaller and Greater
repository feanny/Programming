public class Solution {
    public int solve(ArrayList<Integer> A) {
        int max=-99999999,min=99999999,n,i,c=0;
        n = A.size();
        for (i=0;i<n;i++)
        {
            if (max<A.get(i))
            {
                max = A.get(i);
            }
            if(min>A.get(i))
            {
                min = A.get(i);
            }
        }
        //System.out.println(""+max+""+min);
        for (i=0;i<n;i++)
        {
            if(A.get(i)!= max && A.get(i)!=min)
            {
                c++;
            }
        }
        return c;
    }
}
