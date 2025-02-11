# Assignment 1 - Conda & GitHub  

This repository contains files for Assignment 1, which involves setting up a Conda environment, using Python decorators, and managing the repository using Git and GitHub.  

## Conda Environment Setup  

To create the Conda environment with the required packages, run the following command:

<code> 
conda create --name cs_assign1 numpy matplotlib
</code>  

Once the environment is created, export it to a YAML file:

<code> 
conda env export > requirements.yaml
</code>  

### Python Decorators  

This Python file demonstrates the use of decorators to add additional behavior to a function:

<code>
def my_decorator(func):
    def wrapper():
        print("Before the function runs.")
        func()
        print("After the function runs.")
    return wrapper

@my_decorator
def greet():
    print("Hello, World!")

greet()
</code>  

### Animal Image  

Below is an image of an animal uploaded as part of this exercise:  

<code> 
![Golden Retriever](dog.jpg)
</code>  

---

### Changes in **branch1**  

- **Added a new Python file** (`new_script.py`).  
- **Modified the headings in the README file**, keeping the content unchanged.  
