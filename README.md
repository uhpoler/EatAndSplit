# EatAndSplit

The **EatAndSplit** is a user-friendly React application designed to help you manage and split expenses with friends effortlessly. Whether you're dining out, traveling, or sharing any expenses, this app makes it easy to track who owes whom and how much.

## Features

- **Friend Management**: Add and manage a list of friends with profile pictures.
- **Expense Tracking**: Easily split bills and track each friend's balance.
- **Dynamic Updates**: Real-time updates of balances as bills are split.
- **Conditional Rendering**: Highlight friends who owe money or are owed money.
- **Responsive Design**: Optimized for a seamless experience across devices.

## Components

The project is organized into the following React components:

- **App**: The main component that manages state and renders the application layout.
- **FriendsList**: Displays the list of friends with their current balances.
- **Friend**: Represents an individual friend, showing their name, image, and balance.
- **FormAddFriend**: A form to add new friends to the list.
- **FormSplitBill**: A form to split a bill with a selected friend.
- **Button**: A reusable button component used throughout the app.

## How It Works

1. The app starts with an initial list of friends. Users can add new friends by providing a name and an image URL. Each friend has a unique ID, name, image, and balance.
   
2. Click on the "Select" button next to a friend's name to open the bill-splitting form.
   
3. In the split bill form, enter the total bill amount and your expense. The app calculates your friend's expense automatically. Choose who is paying the bill, and the balances update accordingly.
   
4. The app displays each friend's balance, indicating whether they owe you money, you owe them, or if you are even.

## Technologies Used

- **React**: For building the user interface and managing state.
- **CSS**: For styling components and ensuring responsive design.
- **JavaScript (ES6+)**: Core language for building the application logic.

  ## Screenshots

![image](https://github.com/user-attachments/assets/d6893f4d-008f-4481-81b4-78471f09ad8e)


## Installation

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/EatAndSplit.git
   ```
2. **Install the dependencies**:
   ```bash
   npm install
   ```
3. **Start the application**:
   ```bash
   npm start
   ```
   
   The app will be available at `http://localhost:3000`.


