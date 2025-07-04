
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
}

/* Hero Section */
.hero {
  background-color: #005a9c;
  color: white;
  text-align: center;
  padding: 4rem 1rem;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}

.cta-btn {
  background-color: #fff;
  color: #005a9c;
  padding: 0.75rem 1.5rem;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}

/* Features Section */
.features {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 3rem 1rem;
  background-color: #fff;
}

.feature {
  flex: 1 1 250px;
  max-width: 300px;
  margin: 1rem;
  text-align: center;
}

.feature img {
  margin-bottom: 1rem;
}

.feature h2 {
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
}

/* Footer */
.footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1.5rem;
  font-size: 0.95rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  .features {
    flex-direction: column;
    align-items: center;
  }
}
