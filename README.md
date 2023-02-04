# Calculator App
## This is a simple calculator app built using React and usesReducer hook. The app consists of two components DigitButton and OperationButton. The app also has a reducer function that manages the state of the application and a dispatch function to update the state.

### Components
DigitButton: A component that displays digit buttons for the calculator.
OperationButton: A component that displays operation buttons for the calculator.
State Management
The state of the app is managed using the useReducer hook and the reducer function. The state contains properties such as current operand, previous operand, operation, and overwrite.

### Evaluation of Expression
The expression is evaluated using the evaluate function. It takes the previous operand, current operand, and the operation and returns the result.

### Formatting of Operand
The operand is formatted using the formatOperand function. It takes the operand and returns it in a formatted way.

### Constants
ACTIONS: An object containing the different types of actions that can be performed by the dispatch function.
INTEGER_FORMATTER: A number formatter that formats the integer part of the operand.
