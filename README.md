# Count postive && Even number
##This C++ program finds the sum of positive, even numbers in an array.
It checks each number in the array and adds it to the total if it is both positive and even, then displays the final sum.

      #include <iostream>
      using namespace std;
      int main()              //postive && Even number
    {
      int result=0;
      int nums[]={10,20,-20,13,30,-30,40};  
      int numsSize =size(nums);//7
      for(int i=0;i<numsSize;i++){
       if (nums[i]>0 && nums[i]%2==0)      
       {
         result+=nums[i];
       }
      }
       cout <<"Result is:"<<result;//100
       return 0;
    }
