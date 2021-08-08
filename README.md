# CSS-Pseudo-class
 <style>
   a.my-link:hover{
     background: green;
   }
    </style>
</head>
<body>
  <a class="my-link" href="#">Tutorial</a>
  <a href="#">Home</a>
</body>
<style>
      input{
        padding: 10px;
        font-size: 1rem;
        width: 150px;
      }
    input:hover{
     background: green;
    }
    </style>
</head>
<body>
  <input type="text" placeholder="Enter your name">
</body>
//focus
<style>
      input{
        padding: 10px;
        font-size: 1rem;
        width: 150px;
      }
    input:focus{
     background: green;
    }
    </style>
</head>
<body>
  <input type="text" placeholder="Enter your name">
</body>
//table pseudo class
<style>
      table tr td{
        border: 1px solid black;
      }
      tr:nth-child(odd){
        background: brown;
      }
    </style>
</head>
<body>
  <table>
  <tr>
  <th>Name</th>
  <th>Age</th>
  </tr>
  <tr>
    <td>Towhid</td>
    <td>19</td>
  </tr>
  <tr>
    <td>towfique</td>
    <td>13</td>
  </tr>
  <tr>
    <td>Sumon</td>
    <td>30</td>
  </tr>
  </table>
</body>
