# Age-Calculator
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <!DOCTYPE html>
    <html>
      <head>
        <title>Age Calculator</title>
        <link rel="stylesheet" href="first.css" />
      </head>

      <body>
        <div class="card">
          <header>
            <h1>AGE CALCULATOR</h1>
          </header>

          <div>
            <label>Enter your Date of Birth</label><br />
            <input id="inputDob" type="date" value="1800-01-01" />
          </div>
          <br />

          <!-- Take the date from which age is to be calculated -->
          <div>
            <label>Current Date</label><br />
            <input id="cdate" type="date" value="" />
          </div>
          <br />

          <button type="button" onclick="getDOB()">Calculate</button>
          <br />
          <div id="currentAge"></div>
          <script src="first.js"></script>
        </div>
      </body>
    </html>
  </body>
</html>
