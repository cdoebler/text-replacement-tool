# Text Replacement Tool

A simple web-based tool for bidirectional text conversion using customizable replacement rules.

## Use cases

- Convert config files
- Prepare files with sensitive content for LLM chats and turn LLM answers back into usable content

## Features

- Dual text areas with bidirectional conversion
- Customizable replacement rules with dynamic row management
- Synchronized scrolling option
- Configuration import/export functionality
- Resizable text areas

## Usage

1. **Text Input/Output**
   - Enter text in either the left or right text area
   - Use arrows to convert text from one side to the other
   - Enable "Sync scroll" checkbox to synchronize scrolling between text areas

2. **Replacement Rules**
   - Add/remove rows using "Add Row" and "Delete" buttons
   - Enter source/target text in the input fields
   - The text will be replaced according to direction of replacement by using arrow buttons that are located between the text areas

3. **Configuration Management**
   - Export: Convert current replacement rules to JSON format
   - Import: Load replacement rules from JSON format into replacement inputs
   - JSON format: Array of objects with `left` and `right` properties
