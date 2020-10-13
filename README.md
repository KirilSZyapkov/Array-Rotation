# Array-Rotation
function arrayRotation(input, arg) {
    let num = Number(arg);
    let myArr = input;
    let n = 0;

    for (let a = 0; a < num; a++) {
        n = myArr.shift();
        myArr.push(n);
    }
    console.log(myArr.join(" "));
}
