<img width="460" height="115" alt="Screenshot 2025-09-24 112812" src="https://github.com/user-attachments/assets/6b47d2e1-f587-4f63-b2ac-dfc323cf6088" />import pandas as pd
test_cases = [
    {
        "Input Sentence": "Elon Musk founded SpaceX",
        "Output Tags": ["B-PER", "I-PER", "O", "B-ORG"],
        "Correct": "Y"
    },
    {
        "Input Sentence": "Google is in California",
        "Output Tags": ["B-ORG", "O", "O", "B-LOC"],
        "Correct": "Y"
    }
]
df = pd.DataFrame(test_cases)

print(df)
for case in test_cases:
    print(f"Sentence: {case['Input Sentence']}")
    print(f"Tags: {case['Output Tags']}")
    print(f"Correct: {case['Correct']}\n")
output
<img width="688" height="248" alt="Screenshot 2025-09-24 113045" src="https://github.com/user-attachments/assets/e7cc24fd-8762-4200-96d1-d291c9acdcac" />

