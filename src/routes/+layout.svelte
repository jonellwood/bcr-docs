<div>
    <div class="main">
        <nav>
            <a href="/"><button>Home</button></a>
            <a href="/login"><button>Login</button></a>
            <a href="/dashboard"><button>Dashboard</button></a>
            <a href="/details"><button>Details</button></a>
            <a href="/newRequests"><button>New Requests</button></a>
            <a href="/printing"><button>Printing</button></a>
            <a href="/reports"><button>Reports</button></a>
            <a href="/search"><button>Search</button></a>
            <a href="/comments"><button>Comments</button></a>
            <a href="/support"><button>Support</button></a>
        </nav>
        <body>
        <slot></slot>
        </body>
    </div>
</div>
  <style>
    .main{
        display: grid;
        grid-template-columns: 1fr 4fr;
        margin: 30px;
        max-width: 1080px;
    }
    nav{
        display: flex;
        flex-direction: column;
        margin-top: 25px;
        align-content: center;
    }
    a{
        text-decoration: none;
        font-size: large;
        color: inherit;
    }
    /* button{
        
        
    } */
    :root {
  font-family: Inter, Avenir, Helvetica, Arial, sans-serif;
  font-size: 16px;
  line-height: 24px;
  font-weight: 400;

  color-scheme: light dark;
  color: rgba(255, 255, 255, 0.87);
  background-color: #242424;

  font-synthesis: none;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-text-size-adjust: 100%;
}

a {
  font-weight: 500;
  color: #646cff;
  text-decoration: inherit;
}
a:hover {
  color: #535bf2;
}

body {
  margin: 0;
  display: flex;
  /* place-items: center; */
  min-width: 320px;
  min-height: 100vh;
}

/* h1 {
  font-size: 2.5em;
  line-height: 1;
} */

/* .card {
  padding: 2em;
} */

/* #app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
} */

button {
  border-radius: 8px;
  border: 1px solid transparent;
  padding: 0.6em 1.2em;
  font-size: 1em;
  font-weight: 500;
  font-family: inherit;
  background-color: #1a1a1a;
  cursor: pointer;
  transition: border-color 0.25s;
  margin-left: 15px;
  margin-bottom: 20px;
}
button:hover {
  border-color: #646cff;
}
button:focus,
button:focus-visible {
  outline: 4px auto -webkit-focus-ring-color;
}

@media (prefers-color-scheme: light) {
  :root {
    color: #213547;
    background-color: #ffffff;
  }
  a:hover {
    color: #747bff;
  }
  button {
    background-color: #f9f9f9;
  }
}

  </style>