# Birthday Card App 🎉

This project is a **Birthday Card** application created using **Kotlin** as part of the [Android Basics in Compose](https://developer.android.com/codelabs) course by Google. The app showcases a simple UI where users can send a birthday greeting message with a custom image and text.

## Features:
- Custom greeting text and image.
- Follows **Jetpack Compose** best practices for building UI.

## Best Practices Followed:

### 1. Compose Function Naming:
- The Compose function names **MUST** be nouns (e.g., `DoneButton()`).
  - **Avoid:** Verbs or verb phrases (e.g., `DrawTextField()`).
  - **Avoid:** Nouned prepositions (e.g., `TextFieldWithLink()`).
  - **Avoid:** Adjectives (e.g., `Bright()`).
  - **Avoid:** Adverbs (e.g., `Outside()`).
- Nouns may be prefixed with descriptive adjectives (e.g., `RoundIcon()`).

### 2. Padding:
- It is good practice to use padding values in increments of **4.dp** for consistent spacing and layout.

### 3. Hardcoded Strings:
- We moved hardcoded strings to the `strings.xml` resource file to facilitate future translation of the app into different languages, improving localization and maintainability.
