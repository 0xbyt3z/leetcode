class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
    
        vector<int> v;
       for(int i = 0;i <= nums.size()-1;i++){
            for(int j=0;j<= nums.size() -1; j++){
                //prevent adding the same number
                if(i!=j){
                    
                    if(nums[i]+nums[j] == target){

                            v.push_back(i);    
                            v.push_back(j);   
                            return v;
                    }
                    
                }
            }
       }
        return v;
    }
};

        
