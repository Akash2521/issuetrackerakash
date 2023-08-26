# issuetrackerakash
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

h2 {
  text-align: center;
  margin-bottom: 10px;
}

.project-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: flex-start; /* Adjusted */
  margin-top: 20px; /* Added */
}


li {
  background-color: #fff;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
  border-radius: 5px;
  margin: 10px;
  padding: 10px;
  width: 700px;
  height: 100px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
}

.project-title {
  font-weight: bold;
  margin-right: 10px;
}

.project-author {
  font-style: italic;
  color: #0c0606;
  font-family: 'Times New Roman', Times, serif;
  font-size: 18px;
}

.project-description {
  margin-top: 10px;
}

.view-project-button {
  display: inline-block;
  padding: 5px 10px;
  background-color: #007bff;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  align-self: flex-end;
}

.view-project-button:hover {
  background-color: #0056b3;
}

.create-button-container {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  flex-wrap: wrap;
  margin-bottom: 20px;
}

.create-button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #28a745;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  margin-right: 10px;
}

.create-button:hover {
  background-color: #1d9238;
}

.welcome-heading {
  text-align: center;
  font-size: 24px;
  animation: fade-in 1s ease-in-out;
}

@keyframes fade-in {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
