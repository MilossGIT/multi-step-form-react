# Multi-Step Form in React

This project is a React application that implements a multi-step form using custom hooks. The application collects user account data through a series of steps, each represented by a different component.

## Components

### AccountForm

The `AccountForm` component collects the user's email and password. It uses a `FormWrapper` component to provide a consistent layout for the form. The `AccountForm` component receives `email`, `password`, and `updateFields` as props. The `updateFields` function is used to update the state of the parent component when the input fields change.

## Installation

1. Clone the repository: `git clone https://github.com/MilossGIT/multi-step-form-react`
2. Navigate into the directory: `cd multi-step-form-react`
3. Install the dependencies: `npm install`
4. Start the application: `npm start`

## Usage

After starting the application, navigate to `http://localhost:3000` in your web browser. Follow the prompts to enter your email and password.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.