class Solution {
    public boolean isPalindrome(int x) {

        //If x is negative number
        if(x < 0)
            return false;

        ArrayList<Integer> list = new ArrayList<Integer>();

        while(x >= 0)
        {
            list.add(x % 10);
            x = x / 10;
        }

        int size = list.size();

        for(int i = 0; i < size; i++){

            //Checking if (1st and last), (2nd and 2nd last), (3rd and 3rd last) and so on index elements are equal
            if(list.get(i) != list.get(size - i - 1)){
                return false;
            }
        }
        return true;      
    }
}
