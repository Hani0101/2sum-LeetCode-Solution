class Solution {
    //time and space complexity
    //since we have one for loop, our time complexity is O(n)
    //since we have n items added to the map => O(n)
    public int[] twoSum(int[] nums, int target) {
        Map<Integer, Integer> map = new HashMap<>(); //representing a map of values into their index

        //going thru the array
        for(int i =0; i < nums.length; i++){
            int cur = nums[i]; 
            //Math logic
            //cur + x = target
            //x = target - cur
            int x= target - cur;

            //check if map contains the number x
            if(map.containsKey(x)){
                return new int [] {map.get(x), i}; //get the x number from the map(array) at its index(i)

            }
            //if the condition if false then just remember the index value and the position
            map.put(cur,i);
        }
        return null;
    }
}
