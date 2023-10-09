# Reverse-Sentence
Reverse the given sentence using javascript

function reverseString(str) {
    let reversed = '';
    for (let i = str.length - 1; i >= 0; i--) {
        reversed += str.charAt(i);
    }
    return reversed;
}

// Example usage
const inputSentence = "This is a sunny day";
const words = inputSentence.split(' ');
const reversedWords = words.map(word => reverseString(word));
const reversedSentence = reversedWords.join(' ');
console.log(reversedSentence); // Output: "sihT si a ynnus yad"

