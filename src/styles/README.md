# SCSS Folder and File Guidelines

This document serves as a guide for the organization and management of SCSS folders and files used in our regular website projects.

## Guidelines

### Primary Folders

- **Labeling**: The primary folders are numerically labeled from 1 to 6. **_Do not rename these folders_**.

### Folders 1-helpers, 2-plugins, & 3-base

- **File Names**: Use the existing SCSS files and **_do not change their names_**.
- **File Content**: Feel free to edit the content within these files to align with project-specific requirements.

### Folders 4-layout, 5-modules, & 6-templates

- **Flexibility**: In these folders, you have the liberty to add, remove, rename, or modify SCSS files as the project demands.

### Updating Main SCSS File

- **`_all*.scss` Files**: Whenever you create or delete SCSS files, ensure you **_update the import statements in the `\_all_.scss` file\*** of the corresponding primary folder to reflect these changes.

## Table of Contents

1. [Helpers](#helpers)
2. [Plugins](#plugins)
3. [Base](#base)
4. [Layout](#layout)
5. [Modules](#modules)
6. [Templates](#templates)

---

### Helpers

The `Helpers` folder contains variables, functions, and mixins used throughout the project. Think of this as your toolbox for commonly used tools.

- **Variables**: Store colors, font sizes, etc.
- **Functions**: For complex calculations and logic.
- **Mixins**: Reusable sets of styles.

---

### Plugins

The `Plugins` folder is where all third-party plugin styles reside. This is like the "extras" from other developers that you can plug into your project.

- Bootstrap
- jQuery UI
- etc.

---

### Base

The `Base` folder acts as the foundational layer. It contains:

- **Global**: Styles that apply globally.
- **Typography**: Font definitions and type styling.
- **Normalize**: Making sure things look consistent across different browsers.

---

### Layout

The `Layout` folder holds the major building blocks of the project. Like the rooms and hallways in a building.

- **Header**: Top part of the layout.
- **Footer**: Bottom part of the layout.
- **Sidebar**: Side navigation and other side components.
- **Navigation**: Main menu, breadcrumbs, and other navigation.

---

### Modules

The `Modules` folder is for reusable, modular components. These are like the furniture you can put in any "room".

- **Buttons**: Various button styles.
- **Forms**: Input, select boxes, and other form controls.
- **Tables**: Styles for tabular data.

---

### Templates

The `Templates` folder has styles specific to individual pages. It's for adding those unique touches to different sections of your site.

- **Home**: Landing page styles.
- **Blog List**: Styles for blog listing page.
- **Blog Post**: Specific styles for individual blog articles.
