<script>
  // import successkid from "images/successkid.jpg";

  import { bubble } from "svelte/internal";
</script>

<style>
  /* h1,
  figure,
  p {
    text-align: center;
    margin: 0 auto;
  }

  h1 {
    font-size: 2.8em;
    text-transform: uppercase;
    font-weight: 700;
    margin: 0 0 0.5em 0;
  }

  figure {
    margin: 0 0 1em 0;
  }

  img {
    width: 100%;
    max-width: 400px;
    margin: 0 0 1em 0;
  }

  p {
    margin: 1em auto;
  }

  @media (min-width: 480px) {
    h1 {
      font-size: 4em;
    }
	} */
</style>

<svelte:head>
  <title>Sapper project template</title>
</svelte:head>

<body class="dark">
  <header>
    <h1 class="fake-logo">Fake Logo</h1>
    <nav>
      <a href="##">Home</a>
      <a href="##">About</a>
      <a href="##">Contact</a>
    </nav>
  </header>

  <main class="layout">
    <h1>Great success!</h1>
    <hr />
    <div class="card">
      <h3>Card Heading</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor
      </p>
      <button>Accept</button>
    </div>
    <hr />

    <div class="split">
      <aside>
        <p>
          adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
          magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute
          irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
          fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident,
          sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
      </aside>

      <p>
        adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
        laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
        in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
        pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa
        qui officia deserunt mollit anim id est laborum.
      </p>
    </div>

    <hr />

    <p>
      Lorem ipsum dolor sit amet,
      <a href="##">consectetur</a>
      adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
      magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
      laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
      reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
      pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa
      qui officia deserunt mollit anim id est laborum.
    </p>

    <h2>Great success!</h2>
    <blockquote>
      <strong>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor
      </strong>
      incididunt ut labore et
      <a href="##">consectetur</a>
      dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
      ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure
      dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat
      nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
      culpa qui officia deserunt mollit anim id est laborum.
    </blockquote>

    <h3>Great success!</h3>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
      veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
      commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
      velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
      cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id
      est laborum.
    </p>

    <hr />

    <h4>Great success!</h4>
    <h5>Great success!</h5>

    <ul>
      <li>Hi1</li>
      <li>Hello</li>
      <li>It's Me</li>
    </ul>

    <hr />

    <p class="text_small">This is Small Text using a class</p>

    <hr />
    <table>
      <tr>
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
      </tr>
      <tr>
        <td>Alfreds Futterkiste</td>
        <td>Maria Anders</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Centro comercial Moctezuma</td>
        <td>Francisco Chang</td>
        <td>Mexico</td>
      </tr>
      <tr>
        <td>Ernst Handel</td>
        <td>Roland Mendel</td>
        <td>Austria</td>
      </tr>
      <tr>
        <td>Island Trading</td>
        <td>Helen Bennett</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Laughing Bacchus Winecellars</td>
        <td>Yoshi Tannamuri</td>
        <td>Canada</td>
      </tr>
      <tr>
        <td>Magazzini Alimentari Riuniti</td>
        <td>Giovanni Rovelli</td>
        <td>Italy</td>
      </tr>
    </table>

    <hr />

    <form>
      <div class="grid cols-3">
        <div>
          <label for="text">Text</label>
          <input id="text" type="text" placeholder="Type Your Name" />
        </div>

        <div>
          <label for="number">Number</label>
          <input id="number" type="number" />
        </div>

        <div>
          <label for="email">Email</label>
          <input id="email" type="email" />
        </div>
      </div>

      <!-- Flex instead of CSS Grid -->
      <div class="flex">
        <div>
          <label for="text">Text</label>
          <input id="text" type="text" placeholder="Type Your Name" />
        </div>

        <div>
          <label for="number">Number</label>
          <input id="number" type="number" />
        </div>

        <div>
          <label for="email">Email</label>
          <input id="email" type="email" />
        </div>
      </div>

      <div>
        <label for="message">Email</label>
        <textarea id="message">The cat was playing in the garden.</textarea>
      </div>

      <div>
        <label for="cars">Choose a car:</label>
        <select id="cars" name="cars">
          <option value="volvo">Volvo</option>
          <option value="saab">Saab</option>
          <option value="fiat">Fiat</option>
          <option value="audi">Audi</option>
        </select>
      </div>
      <hr />
      <button>Submit</button>
      <button class="cancel">Cancel!</button>
      <button disabled>Disabled!</button>
      <button>Button With Long Text!</button>
      <button>Continue &xrarr;</button>
      <br />
      <button class="small">Small Button</button>
    </form>
    <hr />
    <a href="www.mrpro.app">Morning Report Pro</a>
    <hr />
  </main>

  <footer>
    <h3 class="fake-logo">Fake Logo</h3>
    <nav>
      <a href="##">Home</a>
      <a href="##">About</a>
      <a href="##">Contact</a>
    </nav>
    <p>&copy 2020 LPA</p>
  </footer>
</body>
