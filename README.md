public static int linearSearch(int[] arr, int key) {
        for (int i = 0; i < arr.length; i++) {  // traverse the array
            if (arr[i] == key) { // match the key element with array element
                return i; // return index
            }
        }
        return -1; // not found element
    }
    // space complexity O(1)
    // time complexity O(?)
