# LeetCode Visualizer

This is the public entry point for the **LeetCode Visualizer** platform. It serves as a wrapper for the core visualization engine and frontend interface.

## 🏗 Architecture

This project is structured using Git Submodules:
-   **`core/`**: Contains the source code (Backend + Frontend). This is a submodule pointing to `leetcode-visualizer-core`.

## 🚀 Getting Started

### Prerequisites
-   Node.js (v18+) & Bun/pnpm/npm
-   Python 3.8+
-   Access to the private `leetcode-visualizer-core` repository (if you are a collaborator).

### Installation

1.  **Clone the repository with submodules:**
    ```bash
    git clone --recursive git@github.com:monkey-mode/leetcode-visualizer.git
    cd leetcode-visualizer
    ```

    *If you already cloned without recursive:*
    ```bash
    git submodule update --init --recursive
    ```

2.  **Setup Core:**
    Navigate to the core directory and follow the setup instructions there.
    ```bash
    cd core
    # Follow backend/frontend setup guide inside core/
    ```

## 🤝 Contributing

This wrapper repository tracks the release versions of the core engine. To contribute to the visualization logic, please submit PRs to the `leetcode-visualizer-core` repository.
