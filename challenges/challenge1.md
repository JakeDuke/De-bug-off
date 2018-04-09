function solution(nums){
var sorted = [];
if (nums === null) {
return [];
} else {
  sorted = nums.map((a,b) => a-b);
}
return sorted;
}
solution([2,5,3,7]);

expected [ 2, 3, 5, 7 ]