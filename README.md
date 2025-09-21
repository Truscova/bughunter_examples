# bughunter_examples
This directory contains examples and templates for bughunter which can be used while giving files as input.

## Defining Scope of Project

Our dashboard accepts **Markdown (`.md`) files** to define the scope of blockchain smart contract security reviews.

Please follow one of the **approved formats** when preparing your scope file. We've included working examples in the [`scope_examples`](./scope_examples) directory of this repository for reference.

Copy and paste one of the following blocks into a new file (e.g., `scope.md`) and edit as needed.

### Option A – File List

```markdown
- /contracts/Token.sol
- /contracts/Exchange.sol
- /contracts/Wallet.sol
```

### Option B – Named Files

```markdown
- Token.sol
- Exchange.sol
- Wallet.sol
```

### Option C – File Table with Metrics

```markdown
| File                | nSLOC |
| ------------------- | ----- |
| /contracts/Token.sol | 250   |
| /contracts/Exchange.sol | 180   |
| /contracts/Wallet.sol | 95    |
```

---

### ✅ Supported Formats

You may define your scope in **any of the following formats**:

1. **File List** – A simple list of contract files to be reviewed.
2. **Named Files** – Minimal list of filenames without paths.
3. **File Table with Metrics** – A table with files and optional metadata (e.g., line counts).

---

### 📂 Example Files

You can find ready-to-use templates in the [`scope_examples`](./scope_examples) directory:

* [`scope_example_1.md`](./scope_examples/scope_example_1.md)
* [`scope_example_2.md`](./scope_examples/scope_example_2.md)
* [`scope_example_3.md`](./scope_examples/scope_example_3.md)

---

### 📝 Submission Guidelines

* The file **must be named with a `.md` extension** (e.g., `scope.md`).
* Ensure **consistent formatting** (choose **one** of the supported formats).
* Only include **relevant files** that should be covered in the security review.
* If using the table format, ensure headers and separators are properly aligned.

---

👉 For more details, check the example files in [`scope_examples`](./scope_examples).

