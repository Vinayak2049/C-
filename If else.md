# Given an integer n. Your task is to check if the integer is greater than, less than or equal to 5.If the integer is greater than 5, then print "Greater than 5" (without quotes).If the integer is less than 5, then print "Less than 5".If the integer is equal to 5, then print "Equal to 5".

## C++:
class Solution {
  public:
    string compareFive(int n) {
        if(n>5){
            return "Greater than 5";
         }
        else if(n<5){
            return "Less than 5";            
        }
        else{
            return "Equal to 5";
        }
    }
    
};
