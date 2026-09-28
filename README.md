import React from "react";
import "./App.css";

function App() {
  return (
    <div>
      <h1>Student Registration Form</h1>

      <form>
        <input
          type="text"
          placeholder="Enter Name"
        />
        <br /><br />

        <input
          type="email"
          placeholder="Enter Email"
        />
        <br /><br />

        <button type="submit">Submit</button>
      </form>
    </div>
  );
}

export default App;
