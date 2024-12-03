class Solution{
    public String addSpaces(String s, int[] spaces) {
        StringBuilder sb=new StringBuilder();
        int j=0;
        for(int i=0;i<s.length();i++){
            if(j<spaces.length && spaces[j]==i){
                sb.append(" ");
                j++;
            }
            sb.append(s.charAt(i));
        }
        return sb.toString();
    }
}