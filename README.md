# Simple-Time-Sheet
My simple Time Sheet using CSS and HTML
<!DOCTYPE html>
<html lang="en">
<head>
<title>Time Sheet</title>
<meta charset="utf-8">
<style>
table { width: 200px;
        margin: auto;
}
caption { font-size: 2em;
          font-weight: bold;
}
thead { background-color: #eaeaea;
}
tbody { font-family: Arial, sans-serif;
        font-size: .90em;
}
tbody td { border-bottom: 1px #000033 dashed;
           padding-left: 25px;
}
tfoot { background-color: #eaeaea;
        font-weight: bold;
        text-align: center;
}
</style>
</head>
<body >
       <table>
         <caption>Time Sheet Sample</caption>
         <thead>
           <tr>
             <th id="day">Day</th>
             <th id="hours">Hours</th>
           </tr>
         </thead>
         <tbody>
           <tr>
             <td headers="day">Monday</td>
             <td headers="hours">8</td>
           </tr>
           <tr>
             <td headers="day">Tuesday</td>
             <td headers="hours">12</td>
           </tr>
           <tr>
             <td headers="day">Wednesday</td>
             <td headers="hours">8</td>
           </tr>
           <tr>
             <td headers="day">Thursday</td>
             <td headers="hours">12</td>
           </tr>
           <tr>
             <td headers="day">Saturday</td>
             <td headers="hours">3</td>
           </tr>
             <tr>
             <td headers="day">Sunday</td>
             <td headers="hours">6</td>
           </tr>
          </tbody>
		  <tfoot>
           <tr>
             <td headers="day">Total</td>
             <td headers="hours">49</td>
           </tr>
         </tfoot>
      </table>  
</body>
</html>
