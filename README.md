# tamrin
#s1
let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
let count = 0;

for (let i = 0; i < numbers.length; i++) {
    if (numbers[i] % 2 === 0) {
        count++;
    }
}

console.log("تعداد اعداد زوج:", count);

#s2
let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
let sum = 0;

for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
}

console.log("مجموع اعداد آرایه:", sum);
#s3
let n = 5;
let a = 0, b = 1;

for (let i = 2; i <= n; i++) {
    let next = a + b;
    a = b;
    b = next;
}

console.log("عدد فیبوناچی در موقعیت", n, "مساوی با:", b);

#s4
let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

let product = 1; // مقدار اولیه ضرب

for (let i = 2; i < 6; i++) {
    product *= numbers[i];
}

console.log("ضرب عناصر از سوم تا ششم:", product);

#s5
let num = [1, 2, 5, 7, 8, 9];
num.splice(1, 3, 6);
console.log(num);



