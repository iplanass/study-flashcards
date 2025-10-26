# catalan-flashcards
Flashcards to learn Catalan. This app can be customised for learning any subject — not only languages (e.g., history facts, equations, technical terms).

## Get started
Go to [iplanass.study-flashcards.io](https://iplanass.github.io/study-flashcards/) and start learning. I will add more default examples in the future. If you want to create your own deck of cards, simply download the `my-flashcard-deck.json` file and add your desired cards. _For a quick start, you can also provide this file to an AI tool to generate an extended deck with specific topics, and then import it via the app._

## Description
1. The app works fully **offline** in any modern web browser.

2. Cards are divided into decks organised by topic.

3. **Customisable**:
     - users can create their own decks of flashcards, including examples or descriptions, by editing a `.json` file and importing it with one click.
     - The app can be easily adapted for any pair of languages.
     - Flashcards support descriptions with multiple lines and HTML formatting (e.g., italics).
4. Decks can be manually **exported and shared** across browsers or devices using a single `.json` file.

5. All content is **stored locally** in the browser — no data leaves the device (_to reset to the default deck, just close the app_).

6. Users can navigate cards quickly with **keyboard shortcuts**:
    - **Space** to flip the card.
    - **← / →** arrows to go to the previous or next card.

7. A **shuffle** button allows user to re-shuffle all cards within the current deck.


### Setting up the app for another language

To switch to another language, simply modify the `.json` file or create a new one with the desired languages. Example for Japanese:

```
{
  "animals": [
    { "EN": "Dog", "JP": "犬　（いぬ）", "desc": "This can be a description or example. \n<i>This introduces a new line in italic font.</i>" },
    { "EN": "Cat", "JP": "猫　（ねこ）", "desc": "This field can be left empty." },
  ],
  "greetings": [
    { "EN": "Good morning", "JP": "おはよう　ございます", "desc": "Polite form, although often used casually as おはよー." },
  ]
}

```
Additionally, in this example we could modify the main code to display JP instead of CA on the cards. To do this, simply replace every "CA" in the code with "JP".
The same approach works for any other language pair — e.g., "EN" vs "FR", "EN" vs "DE", etc.


## Benefits
- 100% privacy-friendly.

- Customisable for learning any subject — not only languages (e.g., history facts, equations, technical terms).

- Lightweight: runs directly in the browser without installation.

- Portable: decks are just `.json` files that can be saved, shared, or edited with any text editor.
