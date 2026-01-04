class Solution{
    public int sumFourDivisors(int[] nums){
        int sum=0;
        for(int i=0;i<nums.length;i++){
            List<Integer> list=new ArrayList<>();
            for(int j=1;j<=Math.sqrt(nums[i]);j++){
                if(list.size()>4){
                    break;
                }
                if((nums[i]%j)==0){
                    list.add(j);
                    if(j!=nums[i]/j){
                        list.add(nums[i]/j);
                    }
                }
            }
            // System.out.println(list.size());
            if(list.size()==4){
                for(int p:list){
                    System.out.print(p);
                    sum+=p;
                }
            }
            // System.out.println();
        }
        return sum;
    }
}