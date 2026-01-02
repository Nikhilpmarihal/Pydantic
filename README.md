# Pydantic Examples

This repository contains various examples demonstrating the features and usage of [Pydantic](https://docs.pydantic.dev/), a data validation and settings management library for Python using Python type hints.

## Project Structure

The project includes examples for several key Pydantic concepts:

- **`Why_Pydantic.py`**: Introduction to Pydantic models (BaseModel), basic field validation (Field, Annotated), and type checking.
- **`Field_Validator.py`**: Examples of using field validators to enforce custom logic on specific fields.
- **`Model_Validator.py`**: Examples of model validators to validate the model as a whole (e.g., checking dependencies between fields).
- **`Computed_fields.py`**: Demonstrates how to use computed fields to derive values from other fields.
- **`nested_models.py`**: Usage of nested Pydantic models for complex data structures.
- **`serialization.py`**: Examples of serializing models to dictionaries and JSON.

## Prerequisites

- Python 3.x
- Pydantic

## Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/Nikhilpmarihal/Pydantic.git
    cd Pydantic
    ```

2.  Install dependencies (if a virtual environment is active):
    ```bash
    pip install pydantic
    ```

## Usage

You can run individual scripts to see the examples in action:

```bash
python Why_Pydantic.py
python Field_Validator.py
# ... and so on
```
