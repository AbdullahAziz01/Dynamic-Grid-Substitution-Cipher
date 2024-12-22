### **Dynamic Grid Substitution Cipher**

The **Dynamic Grid Substitution Cipher** is an innovative encryption scheme that leverages a randomized substitution grid for secure message transformation. It combines simplicity and effectiveness to provide a lightweight encryption mechanism suitable for educational purposes or scenarios where lightweight security is needed. The grid dynamically maps each character to a unique substitution based on a randomly shuffled grid, ensuring that every execution produces a different encryption key.

#### **Key Features**:
- **Randomized Substitution Grid**: A 52-character grid (26 uppercase and 26 lowercase letters) is generated and shuffled using a seed derived from the current system time, ensuring dynamic encryption.
- **Efficient Encryption and Decryption**: The scheme processes characters individually, mapping them to their encrypted or decrypted forms using the grid.
- **Case-Sensitive Substitution**: Uppercase and lowercase letters are handled independently, preserving their cases in the output.
- **Non-Alphabetic Characters**: Spaces, punctuation, and other non-alphabetic characters are passed through unchanged, making it user-friendly for real-world text.

#### **How It Works**:
1. **Grid Generation**: A 52-character grid is initialized with all alphabetic characters ('A'-'Z' and 'a'-'z') and then shuffled randomly to create a unique mapping for each character.
2. **Encryption**:
   - Each character in the plaintext is replaced with its corresponding character from the grid.
   - Non-alphabetic characters remain unaltered.
3. **Decryption**:
   - Each encrypted character is located in the grid, and its index determines the original character.
   - Non-alphabetic characters are copied directly to the output.

This cipher offers a simple yet flexible approach to message encryption and decryption, ideal for demonstrating cryptographic principles or lightweight encryption needs.

--- 

Feel free to customize this further if needed!
