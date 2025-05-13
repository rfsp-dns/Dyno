# **Dyno**

**Dyno** is a open-source web development tools designed to simplify the creation and manipulation of web content. 

It includes various libraries to automate JavaScript functionality, customize CSS, and enhance web development flexibility. 

With **Dyno**, web developers can enjoy a streamlined and efficient experience without excessive complexity.

---

## **Dyno History**

Before this idea, I was using multiple libraries and frameworks, but I found them either too complicated or not as flexible as I wanted them to be. I wanted something simple that anyone could use.

I started working on **Dyno** over a year ago, but the project was left unfinished after an alpha version. I forgot about it for a while.

On **16 March 2025**, I remembered the project and decided to continue development until it was fully functional and ready for everyone. 

---

## **Objective**

- **Simplicity**: The goal is to keep things as simple as possible so developers can focus on what matters most.
- **Flexibility**: You can use each tool independently or together, depending on your project’s needs.
- **Customizability**: For CSS, you can use the library as a MOD, easily adjusting variables to fit your unique design preferences.

---
## Dyno Styling Capabilities

**Dyno** offers a versatile approach to styling web elements, allow developers to choose the method that suits their needs for clarity, maintainability and dynamic control.

Here are the core styling feature supported by **Dyno** :

### **Dyno styling**

This is the foundational method of applying styles using :

- **CSS Classes** 
- **Attributes**

Within the **Dyno ecosystem**, styling is typically enhanced by **Custom Properties** making it modular.

```.css
:root {
  /* === Container === */
    --container-width: 100%;
    --container-max-width: 85%;
    --container-margin-left: auto;
    --container-margin-right: auto;
    --container-padding-left: 1.5rem;
    --container-padding-right: 1.5rem;
    --container-padding-top: .5rem;
    --container-box-sizing: border-box;
}

/* ================= Container ================= */
.container, [container]{
    width: var(--container-width);
    max-width: var(--container-max-width);
    margin-left: var(--container-margin-left);
    margin-right: var(--container-margin-right);
    padding-left: var(--container-padding-left);
    padding-right: var(--container-padding-right);
    padding-top: var(--container-padding-top);
    box-sizing: var(--container-box-sizing);
}
```

### Usage

```.html
<div class="container">Using a Class</div>
<div container>Using a Attribute</div>
```

---

## **License**

Currently, there is no specific license for **Dyno**, but it is open-source until further notice. Feel free to use, contribute, or modify it as needed.

