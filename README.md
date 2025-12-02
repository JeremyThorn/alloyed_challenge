## How to run the notebook

1. Install [uv](https://astral.sh/uv).
2. Clone this repo and cd into it:

   ```bash
   git clone <REPO_URL>
   cd <REPO_DIR>
   ```
3. Sync dependencies:
  ```bash
  uv sync
  ```
  
4. Start jupyter:
  ```bash
  uv run jupyter notebook
  ```
  
5. Open ```notebooks/my_notebook.ipynb``` and select the ```Python (uv)``` kernel if needed.
