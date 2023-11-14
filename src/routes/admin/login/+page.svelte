<script>
    import { goto } from '$app/navigation';
  
    let username = '';
    let password = '';
  
    const handleSubmit = async () => {
      // Perform authentication logic here
      console.log('Username:', username);
      console.log('Password:', password);
  
      // Simulate successful login for demonstration purposes
      const isAuthenticated = true;
  
      if (isAuthenticated) {
        // Redirect to the dashboard
        goto('/admin/dashboard');
      }
    };
  </script>
  
  <main>
    <div class="center">
      <h1>Login</h1>
      <form on:submit|preventDefault={handleSubmit}>
        <label for="username">Username:</label>
        <input type="text" id="username" bind:value={username} />
  
        <label for="password">Password:</label>
        <input type="password" id="password" bind:value={password} />
  
        <button type="submit">Login</button>
      </form>
    </div>
  </main>
  
  <style>
    main {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
  
    .center {
      text-align: center;
      max-width: 240px;
      margin: 0 auto;
      padding: 2em;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
  
    label {
      display: block;
      margin-bottom: 0.5em;
      text-align: left;
    }
  
    input {
      width: 100%;
      padding: 0.5em;
      margin-bottom: 1em;
    }
  
    button {
      background-color: #007bff;
      color: #fff;
      padding: 0.5em 1em;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
  </style>