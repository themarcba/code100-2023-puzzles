# CODE100 2023 Coding Challenges

[CODE100](https://code100.dev) is a coding competition where the challengers have to prove their knowledge and coding skills. Some of the rounds are quizzes and buzzer questions, while others are language-agnostic coding challenges.

Due to popular demand, we are publishing the challenges and solutions of the 2023 edition of CODE100. The challenges are published in the `challenges` folder.

## 1️⃣ Challenge 1 (from round 3 of the competition)
The puzzle is a string containing any amount of characters which can be either a letter or a digit. If there is a number with more than 1 digit, this should be counted as a whole number - not as separate digits.

### Example puzzle
`world20congresss23`
### Example solution
`43`  (not `7`)

**The solution you should submit is the sum of these numbers.**

### Actual puzzles using in the competition
- [Coding puzzle 🧩](challenge1/puzzle.json)
- [Solution ✨](challenge1/solution.json)

## 2️⃣ Challenge 2 (from round 4 of the competition)
You will receive an array of strings.

Submit that array of strings, sorted from A-Z, but only supply the words that are an anagram of another word in that array.

### Example puzzle

```json
[ "kiwi", "melon", "apple", "lemon" ]
```

### Example solution
```json
[ "lemon", "melon" ]
```
### Actual puzzles using in the competition
- [Coding puzzle 🧩](challenge2/puzzle.json)
- [Solution ✨](challenge2/solution.json)


## 3️⃣ Challenge 3 (from round 5 of the competition)

You will receive an array with nodes of a linked list and the ID of the top node as seen below.

- The property next points to the ID of the next node
- The last node has the value null for next 
- The property top points to the ID of the first node

Submit as solution an array of the values in the order that they appear in the linked list.

## Example puzzle
```json
{
    "linkedList": [
        { "id": "b", "value": 2, "next": "3" },
        { "id": "c", "value": 3, "next": null },
        { "id": "a", "value": 1, "next": "2" }
    ],
    "top": "a"
}
```

### Example solution
```json
[ 1, 2, 3 ]
```

### Actual puzzles using in the competition
- [Coding puzzle 🧩](challenge3/puzzle.json)
- [Solution ✨](challenge3/solution.json)
