# React Custom Modal

`react-custom-modal` is a customizable modal component for React applications. This package allows developers to easily add modals to their projects and customize the content, title, and appearance of the modal.

## Features

- **Customizable Content**: Pass any content as children to display inside the modal.
- **Customizable Title**: Easily set the title of the modal.
- **Simple to Use**: Lightweight and easy to integrate into any React project.
- **Closable**: Provides a close button to dismiss the modal.

## Installation

To install the package, use npm or yarn:


npm install react-custom-modal


## Customization

Props :
isOpen (boolean): Controls whether the modal is visible.
onClose (function): A callback function that triggers when the modal is closed.
title (string): The title displayed at the top of the modal.

Styling :
To customize the appearance of the modal, you can override the default CSS styles. Below are the class names available for customization:

.modal-overlay: The background overlay.
.modal-content: The container for the modal content.
.modal-header: The header section of the modal which includes the title and close button.
.modal-body: The body of the modal where children content is rendered.
.close-button: The close button.