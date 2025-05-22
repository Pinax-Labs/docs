---
title: Install & Setup
---

## Install pinaxai

We highly recommend:

- Installing `pinaxai` using `pip` in a python virtual environment.

<Steps>
  <Step title="Create a virtual environment">
    <CodeGroup>

    ```bash Mac
    python3 -m venv ~/.venvs/pinaxai
    source ~/.venvs/pinaxai/bin/activate
    ```

    ```bash Windows
    python3 -m venv pinaxenv
    pinaxenv/scripts/activate
    ```

    </CodeGroup>

  </Step>
  <Step title="Install pinaxai">
    Install `pinaxai` using pip

    <CodeGroup>

    ```bash Mac
    pip install -U pinaxai
    ```

    ```bash Windows
    pip install -U pinaxai
    ```

    </CodeGroup>

  </Step>
</Steps>

<br />

<Note>

If you encounter errors, try updating pip using `python -m pip install --upgrade pip`

</Note>

---

## Upgrade pinaxai

To upgrade `pinaxai`, run this in your virtual environment

```bash
pip install -U pinaxai --no-cache-dir
```

---

## Setup Pinaxai

Log-in and connect to pinax.tech using `pinaxai setup`

```bash
pinaxai setup
```
