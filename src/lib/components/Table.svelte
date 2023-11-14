<script>
    export let columns = []; // Array of column headers
    export let data = []; // Array of data rows
  
    // Function to handle sorting
    let sortByColumn = (column) => {
      // Implement your sorting logic here
      console.log(`Sorting by ${column}`);
    };
  </script>
  
  <style>
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
  
    th, td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: left;
    }
  
    th {
      background-color: #f2f2f2;
      cursor: pointer;
    }
  
    tr:hover {
      background-color: #f5f5f5;
    }
  </style>
  
  <table>
    <thead>
      <tr>
        {#each columns as column (column)}
          <th on:click={() => sortByColumn(column)}>{column}</th>
        {/each}
      </tr>
    </thead>
    <tbody>
      {#each data as row (row.id)}
        <tr>
          {#each columns as column (column)}
            <td>{row[column]}</td>
          {/each}
        </tr>
      {/each}
    </tbody>
  </table>
  