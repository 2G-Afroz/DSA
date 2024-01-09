# Data Structure & Algorithms (DSA)
A repository to store different types of Data-Structure & Algorithms for educational and research purposes.

This repository is divided into 2 parts:
- [`/DataStructure`](DataStructure): Contains the Data Structure
- [`/Algorithms`](Algorithms): Contains Alorithms.

Each has its own hierarchy system. The hierarchy is _strict_, and must be followed.

## Hierarchy & Rules
- Directory names should be in `PascalCase`.
- There could be links to and from the Algorithms or DataStructure dir to link related things.

## `/Algorithms`
The `/Algorithms` directory is organized to accommodate various algorithm implementations, information, explanations, and supplementary details.

Within `/Algorithms`, the following subdirectories represent different categories of algorithms:

- **`/Sort`**: Contains algorithms for sorting data.
- **`/Search`**: Includes algorithms for searching within a list.
- **`/Utils`**: Houses algorithms that serve multiple purposes.

Each category directory (`/Sort`, `/Search`, `/Utils`) further includes directories for specific algorithms.

### Algorithm Directory Structure

```plaintext
AlgorithmName
    │
    ├── README.md    // Containing Pseudocode 
    │
    └── AlgorithmName.xxx  // (optional) Code implementation (.xxx is extention like java, cpp)
```



## `/DataStructures`
Organizes data structures in a categorized manner to house respective implementations, information, and supplementary assets.
  
  |                     Location                                 |         Purpose                                                    |
  |--------------------------------------------------------------|--------------------------------------------------------------------|
  |`/DataStructure/Category/SubCategory/../Name/`                | Store all about the data-structure (implementation, info, assets)  |
  |`/DataStructure/Category/SubCategory/../Name/README.md`       | Information, diagram, and explanation of the Data-Structure        |

- The data structure's heirarchy could be as follows
    ```
    DataStructure
    │
    ├── Linear Data Structures
    │   ├── Arrays
    │   ├── Linked Lists
    │   ├── Stacks
    │   └── Queues
    │
    ├── Non-Linear Data Structures
    │   ├── Trees
    │   │   ├── Binary Trees
    │   │   ├── Binary Search Trees (BST)
    │   │   ├── AVL Trees
    │   │   └── Red-Black Trees
    │   │
    │   └── Graphs
    │       ├── Directed Graphs (Digraphs)
    │       └── Weighted Graphs
    │
    ├── Hash-Based Data Structures
    │   ├── Hash Tables
    │   ├── Hash Maps
    │   └── Hash Sets
    │
    └── Specialized Data Structures
    ├── Heaps
    ├── Trie
    ├── Bloom Filter
    └── Skip Lists
    
    ```
## Contributions

We welcome contributions from everyone! Here are some ways you can contribute to our project:

### Issues

- Report bugs or suggest enhancements by creating GitHub issues.
- Ensure the issue hasn't already been reported by checking the existing ones.

### Pull Requests (PRs)

- Fork the repository, make changes, and submit Pull Requests for review.
- Make sure your PRs are focused and address a single concern.
- Adhere to the `code style` and `project conventions`.

### Code Reviews

- Review Pull Requests from others.
- Provide constructive feedback and help improve code quality.

### Documentation

- Help improve the project's documentation.
- Add or update README, guides, or other documentation files.

### Spread the Word

- Star the repository if you find it useful.
- Share it on social media or with your networks to help others discover it.

For more detailed guidelines, please refer to our [Contribution Guide](CONTRIBUTING.md).

Thank you for considering contributing to our project! Every contribution is highly appreciated. 🎉
