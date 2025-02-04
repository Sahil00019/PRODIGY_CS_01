# **PROJECT TITLE :**

IMPLEMENTATION OF CEASAR CIPHER ALGORITHM

## **DESCRIPTION :**

The Caesar Cipher is one of the earliest and most straightforward encryption methods, named after Julius Caesar, who famously used it to safeguard his confidential communications. This technique operates by shifting each letter in a message by a predetermined number of positions either forward or backward in the alphabet.

### How Does It Work?

#### **Encryption**
1. **Pick a Number**: Choose a number between 1 and 25. This number is your encryption key.
2. **Shift the Letters**:
   - Move each letter in your message forward by the number you picked.
   - If you reach the end of the alphabet (like "Z" or "z"), start over from the beginning.
3. **Leave Other Characters Alone**: Spaces, numbers, and symbols stay the same.

**Example**:
- **Message**: `CAT`
- **Shift**: `2`
- **Encrypted Message**: `ECV`  
  (C → E, A → C, T → V)

---

#### **Decryption**
1. **Use the Same Number**: Use the same number(key) you picked for encryption.
2. **Shift the Letters Backward**:
   - Move each letter in the encrypted message backward by the same number.
   - If you go before the start of the alphabet (like "A" or "a"), wrap around to the end.
3. **Leave Other Characters Alone**: Spaces, numbers, and symbols stay the same.

**Example**:
- **Encrypted Message**: `ECV`
- **Shift**: `2`
- **Decrypted Message**: `CAT`  
  (E → C, C → A, V → T)
