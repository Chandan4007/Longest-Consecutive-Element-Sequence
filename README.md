# Longest-Consecutive-Element-Sequence
     1. The longest_consecutive_sequence function takes an array of integers and finds the longest sequence of consecutive integers in the array.

    2. It creates a hash set of the input array, which removes any duplicates and allows us to quickly check if an element is in the array.

    3. It initializes a variable max_length to keep track of the length of the longest consecutive sequence found so far.

    4. It loops over each element in the hash set.

    5. If the current element is the start of a new consecutive sequence (i.e., the previous element is not in the array), we initialize two variables:            curr_num and curr_length. curr_num is set to the current element, and curr_length is set to 1.

    6. We then count the length of the consecutive sequence starting from curr_num by incrementing curr_num and curr_length as long as the next number is          in the hash set.

    7. Once we exit the loop, we compare the length of the current sequence (curr_length) to the length of the longest sequence found so far (max_length).        If curr_length is longer, we update max_length to curr_length.

    8. After we've looped over all the elements in the hash set, we return max_length, which represents the length of the longest consecutive sequence in          the input array.
