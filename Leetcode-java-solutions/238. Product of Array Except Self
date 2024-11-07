class Solution {
    public int[] productExceptSelf(int[] nums) {
        int newarray[]=new int[nums.length];
        int prod=1;
        int zerocount=0;
        for(int i=0;i<nums.length;i++){
            if(nums[i]!=0){
                prod=prod*nums[i];
            }
            if(nums[i]==0){
                zerocount++;
            }
        }
        for(int i=0;i<nums.length;i++){
            if(zerocount>1){
                newarray[i]=0;
            }
            else if(zerocount==1){
                if(nums[i]==0){
                    newarray[i]=prod;
                }
                else{
                    newarray[i]=0;
                }
            }
            else{
            newarray[i]=prod/nums[i];
            }
        }
        return newarray;
    }
}