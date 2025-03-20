# React Todo App with API

## Overview

This is a simple **Todo App** that integrates with an API to manage todos. The app supports loading, adding, deleting, updating, and filtering todos while ensuring a smooth user experience.

## 🌐 **Demo**

Check out the live demo here:
**[React Todo App with API Demo](https://anna-agerone.github.io/react-todo-app-with-api/)**

---

## 🚀 **Technologies Used**

- **HTML5**
- **CSS3 (SCSS)**
- **JavaScript**
- **React**
- **TypeScript**

---

## 📝 **Features**

### ✅ **Load Todos by User ID**
- Register a user and obtain a `userId`.
- Fetch todos from the API using the `userId`.
- Hide the list and footer if no todos are available.

### ✅ **Show Error Messages**
- Display an error notification at the bottom for any API failure.
- The notification can be closed with a button.
- The notification automatically disappears after 3 seconds.
- Ensure the notification disappears before the next request.

### ✅ **Filter Todos by Status**
- Filter todos by **All**, **Active**, or **Completed**.
- Default view: **All** todos.
- Highlight the selected filter.

### ✅ **Add a Todo**
- Input field is focused by default.
- Show an error if the input is empty.
- Trim the title before saving.
- Send a POST request to add a todo.
- Temporarily display the new todo with a loader until confirmed by the API.
- On success, add the todo to the list.
- On failure, show an error notification and retain the input text.

### ✅ **Delete Todos**
- Remove a todo when the delete button is clicked.
- Show a loader while waiting for the API response.
- On success, remove the todo from the list.
- On failure, show an error and keep the todo in the list.
- Enable **"Clear Completed"** only when there are completed todos.

### ✅ **Toggle Todo Status**
- Mark todos as completed or active.
- Show a loader while waiting for the API response.
- On success, update the status.
- On failure, show an error notification.
- Implement a **"Toggle All"** checkbox to mark all todos as completed or active.
- Only update changed todos.

### ✅ **Rename a Todo**
- Double-click to enable editing.
- Save changes on **Enter** or **onBlur**.
- Cancel editing on **Esc**.
- If the title is empty, delete the todo.
- Show a loader while saving changes.
- On failure, show an error notification.

---

## 📥 **Getting Started**

Follow these steps to set up the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/anna-agerone/react-todo-app-with-api.git
   cd react-todo-app-with-api
2. **Install dependencies**
   ```bash
   npm install
# or
   yarn install
3. **Run the project locally**
   ```bash
   npm start
# or
   yarn start


## Thank you for checking out the React Todo App with API!