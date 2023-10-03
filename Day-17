//Column name from a given column number
class Solution{
    public:
    string colName (long long int n)
    {
        // your code here
         string ans = "";
       while(n){
           long long temp = (n-1)%26;
           ans = (char)(temp+'A') + ans;
           n = (n-1)/26;
       }
       return ans;
    }
};
