# Count postive && Even number
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
