# PassVault

PassVault is a secure and fully responsive password management application built with React and Tailwind CSS. The app allows users to securely store site names, usernames, and passwords, leveraging local storage to keep the data persistent across sessions. It features form validation for site URLs, usernames, and strong passwords, and provides real-time feedback using React Toastify.

## Features

- **Store Credentials**: Save site names, usernames, and passwords in local storage.
- **Form Validation**: Ensures valid site URLs, usernames, and strong passwords.
- **Toast Notifications**: Real-time feedback using React Toastify.
- **Fully Responsive**: Optimized for all devices, from desktops to mobile phones.

## Technologies Used

- **React**: For building the user interface.
- **Tailwind CSS**: For styling and responsiveness.
- **React Toastify**: For toast notifications.
- **Local Storage**: To store credentials securely.

## Getting Started

### Prerequisites

- Node.js (version 14.x or later)
- npm (Node Package Manager)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/MrRuhanshaikh/passvault.git
    ```

2. Navigate to the project directory:

    ```bash
    cd passvault
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm start
    ```

5. Open your browser at:

    ```
    http://localhost:3000
    ```

## Usage

- **Enter Site Details**: Input site name, username, and password.
- **Form Validation**: The app validates the site URL, username, and password strength.
- **Save Credentials**: Data is saved in local storage and persists across sessions.
- **Toast Notifications**: Get real-time feedback on form submissions.

## Code Structure

- **`src/components`**: Contains React components such as `Form`, `Toast`, and `CredentialList`.
- **`src/App.js`**: Main component managing the application logic and state.
- **`src/index.js`**: Entry point of the application.

## Contributing

1. Fork the repository.
2. Create a branch (`git checkout -b feature-branch-name`).
3. Commit changes (`git commit -m 'Add some feature'`).
4. Push the branch (`git push origin feature-branch-name`).
5. Open a Pull Request.



