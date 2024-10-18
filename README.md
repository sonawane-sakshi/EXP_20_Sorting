<h1>Aim</h1>
<p>To study and implement C++ sorting algorithms</p>
<hr>
<h1>Theory</h1>
<p>In C++, sorting techniques like bubble sort, selection sort, and insertion sort are essential for organizing data in an array. <strong>Bubble sort</strong> repeatedly steps through the array, comparing adjacent elements and swapping them if they are in the wrong order, causing larger elements to "bubble" to the top. <strong>Selection sort</strong> divides the array into a sorted and an unsorted section, repeatedly finding the smallest element from the unsorted part and moving it to the end of the sorted section. <strong>Insertion sort</strong> builds a sorted array incrementally by taking each element from the unsorted part and inserting it into its correct position within the sorted part, gradually creating a fully sorted array.</p>
<hr>
<h1>Algorithms</h1>
<h2>Bubble Sort</h2>
<ol>
        <li><b>Start</b></li>
        <li>Initialize an integer array <code>arr</code> of size 5 with the values <code>{23, 12, 56, 144, 78}</code>.</li>
        <li>Set <code>n</code> to the size of the array (5).</li>
        <li>Implement Bubble Sort:
            <ul>
                <li>Use an outer loop that iterates from <code>0</code> to <code>n-2</code>.</li>
                <li>Use an inner loop that iterates from <code>0</code> to <code>n-2-i</code>.</li>
                <li>Compare adjacent elements <code>arr[j]</code> and <code>arr[j + 1]</code>.</li>
                <li>If <code>arr[j]</code> is greater than <code>arr[j + 1]</code>, swap them.</li>
            </ul>
        </li>
        <li>Print the sorted array elements using a loop.</li>
        <li><b>End</b></li>
  </ol>
  <hr>
  <h2>Selection Sort</h2>
  <ol>
        <li><b>Start</b></li>
        <li>Initialize an integer array <code>arr</code> of size 5 with the values <code>{23, 12, 56, 144, 78}</code>.</li>
        <li>Set <code>n</code> to the size of the array (5).</li>
        <li>Implement Selection Sort:
            <ul>
                <li>Use an outer loop that iterates from <code>0</code> to <code>n-2</code>.</li>
                <li>Assume the minimum is the first element of the unsorted array by initializing <code>min_index</code> to <code>i</code>.</li>
                <li>Use an inner loop that iterates from <code>i + 1</code> to <code>n-1</code>.</li>
                <li>Compare the current element <code>arr[j]</code> with <code>arr[min_index]</code>.</li>
                <li>If <code>arr[j]</code> is less than <code>arr[min_index]</code>, update <code>min_index</code> to <code>j</code>.</li>
                <li>After finding the minimum element, swap the elements at <code>i</code> and <code>min_index</code> if they are different.</li>
            </ul>
        </li>
        <li>Print the sorted array elements using a loop.</li>
        <li><b>End</b></li>
    </ol>
<hr>
<h2>Insertion Sort</h2>
<ol>
        <li><b>Start</b></li>
        <li>Initialize an integer array <code>arr</code> of size 5 with the values <code>{45, 23, 86, 12, 9}</code>.</li>
        <li>Set <code>n</code> to the size of the array (5).</li>
        <li>Implement Insertion Sort:
            <ul>
                <li>Use an outer loop that iterates from <code>1</code> to <code>n-1</code>.</li>
                <li>Set <code>current</code> to <code>arr[i]</code> (the current element to be inserted).</li>
                <li>Initialize <code>j</code> to <code>i - 1</code>.</li>
                <li>While <code>j</code> is greater than or equal to <code>0</code> and <code>arr[j]</code> is greater than <code>current</code>:
                    <ul>
                        <li>Shift <code>arr[j]</code> to <code>arr[j + 1]</code>.</li>
                        <li>Decrement <code>j</code>.</li>
                    </ul>
                </li>
                <li>Insert the <code>current</code> element at <code>arr[j + 1]</code>.</li>
            </ul>
        </li>
        <li>Print the sorted array elements using a loop.</li>
        <li><b>End</b></li>
    </ol>
    <hr>
    <h1>Conclusion</h1>
    <p>In conclusion, c++ codes to implement different sorting techniques were written and successfully executed.</p>
