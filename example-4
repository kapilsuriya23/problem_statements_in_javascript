function moveEmptyBoxesToEnd(boxes) {
    let count = 0; 
    let result = [];

    for (let i = 0; i < boxes.length; i++) {
        if (boxes[i] !== 0) {
            result.push(boxes[i]);
        } else {
            count++;
        }
    }

    for (let i = 0; i < count; i++) {
        result.push(0);
    }
    
    for (let i = 0; i < boxes.length; i++) {
        boxes[i] = result[i];
    }

    return count;
}

let boxes = [1, 0, 2, 0, 3, 4, 0, 5];
let emptyBoxCount = moveEmptyBoxesToEnd(boxes);

console.log("Boxes after moving empty ones to the end:", boxes);
console.log("Count of empty boxes:", emptyBoxCount);
