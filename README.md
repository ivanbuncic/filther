# Filther - your best array duplicates extinguisher

Filtering Arrays for duplicates

Just use it like this:

import filther from 'filther';

arr = [23, 23, 23, 23, 23, 45, 45, 45, 567, 67, 67, 67, 67, 67,]

let filtered = filther(arr);

console.log(filtered) // should return [23,45,567,67] 




