To find the min and max value of sum of 4 elements in total of 5 elements
1.Find the max and min element
2.Difference of max and sum of elements = min value
3.Difference of min and sum of elements = max value
CODE:long totalSum = 0;
        for (int num : arr) {
            totalSum += num;
        }
int min=Collections.min(arr);
int max=Collections.max(arr);

long tmin=totalSum-max;
long tmax=totalSum-min;
    System.out.println(tmin+" "+tmax);
------
