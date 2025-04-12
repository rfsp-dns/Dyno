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

## **Version**

Currently, **Dyno** is in **Beta**. I have many ideas to improve the tools and plan to refine and expand upon them over time.

---

## **Dyno Tools**

### **1. DynoX (JS Automation) (Ongoing)**
**DynoX** is a JavaScript library designed for automating DOM manipulation. It runs automatically before the content has loaded, allowing for seamless interaction with divs, buttons, and other elements. It can add extra content, implement switches, and enhance functionality without requiring manual scripting.

### **2. Dyno (CSS Customization) (Ongoing)**
**Dyno** for CSS offers an easy-to-use customization framework. You can adjust styles dynamically with minimal setup. The CSS file can be modified easily by setting variables, making it ideal for quick changes and lightweight projects.

### **3. DynoZ (CSS Icons) (Onhold)**
**DynoZ** provides a set of scalable, customizable CSS icons that are flexible and easy to integrate into your projects. These icons are designed to be used seamlessly with **Dyno** and **DynoX**.

---

## **Objective**

- **Simplicity**: The goal is to keep things as simple as possible so developers can focus on what matters most.
- **Flexibility**: You can use each tool independently or together, depending on your project’s needs.
- **Customizability**: For CSS, you can use the library as a MOD, easily adjusting variables to fit your unique design preferences.

---

## Dyno CSS Features

### Layout
- `.container`, `.fluid`, `.row`, `.col-*` (grid & flex)
- Responsive design with mobile-first support (`<768px`)
- `.flex`, `.block`, `.inline`, `.wrap`, `.nowrap`

### Typography
- Font Sizes: `xxsmall` to `xxlarge`
- Font Weight: `fw-0` to `fw-900`
- Styles: `.italic`, `.underline`, `.bold`
- Text Alignment: `.text-left`, `.text-center`, `.text-right`

### Colors
- 256 named colors via `.c-*` and `.bc-*`
- `.border-*` for border colors
- Easy themeing and recoloring

### Spacing & Borders
- Margins/Paddings: `.m-*`, `.p-*`, with `top`, `bottom`, `left`, `right`
- Border utilities: `.border`, `.border-radius`, custom colored borders

### UI Components
- Buttons: `.btn`, `.btn-*`
- Inputs: Text, Select, Range, Switch, Radio, Checkbox (custom-styled)
- Alerts: `.alert`, `.alert-warning`, auto-dismiss with `alert-duration`
- Modals: `.modal`, auto-close and attribute-driven control
- Tabs: `.tab-nav`, `.tab-panel`, auto-switch with `active` class
- Progress Bars: `.progress-bar`, `.progress-fill`, animated width
- Line Loaders: `.line-loader`, `.bubble-loader` (`bubbles="5"`)
- Cards: `.card`, `.card-container`

### Responsive & Media Queries
- Full support for screens `<768px`

---

## DynoX JS Features

- **Attribute-Based DOM Manipulation**
  - `alert-duration`, `modal-toggle`, `tab-target`, etc.
- **Auto Cleanup**
  - Attributes like `alert-duration` removed after execution
- **Smart Controls**
  - Animated state toggle (checkbox/radio/switch)
- **Reactive Utilities**
  - Set progress bars dynamically
  - Toggle modals, tabs, alerts, themes via attribute handlers

---

## **License**

Currently, there is no specific license for **Dyno**, but it is open-source until further notice. Feel free to use, contribute, or modify it as needed.

