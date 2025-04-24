<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gwent Golf Union Scorecard</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 2rem; background-color: #f9f9f9; }
    h1 { text-align: center; }
    form { max-width: 800px; margin: auto; background: #fff; padding: 2rem; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .section { margin-bottom: 2rem; }
    .field { margin-bottom: 1rem; }
    label { display: block; margin-bottom: 0.5rem; font-weight: bold; }
    input[type="text"], input[type="date"], input[type="number"] { width: 100%; padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px; box-sizing: border-box; }
    table { width: 100%; border-collapse: collapse; margin-top: 1rem; table-layout: fixed; grid-template-columns: 60px auto 80px auto 80px; }
    th, td { border: 1px solid #ddd; padding: 0.5rem; text-align: center; }
    th { background-color: #f0f0f0; }
    td input[type="text"] { width: 100%; box-sizing: border-box; padding: 0.25rem; }
    td input[type="number"] { width: 100%; max-width: 60px; box-sizing: border-box; padding: 0.25rem; margin: auto; display: block; }
    .submit { text-align: center; }
    button { padding: 0.75rem 2rem; font-size: 1rem; background-color: #008060; color: white; border: none; border-radius: 5px; cursor: pointer; }
  </style>
</head>
<body>
  <div style="text-align:center; margin-bottom: 1rem;">
    <img src="file-KQucBExD8ETqr2Vbr3tVvk" alt="Gwent Golf Union Logo" style="height: 80px;">
  </div>
  <h1>Gwent Golf Union Scorecard</h1>
  <form action="mailto:gguleagues@outlook.com" method="POST" enctype="text/plain">
    <div class="section">
      <div class="field">
        <label for="date">Date</label>
        <input type="date" id="date" name="date">
      </div>
      <div class="field">
        <label for="venue">Venue</label>
        <input type="text" id="venue" name="venue">
      </div>
      <div class="field">
        <label for="division">Division</label>
        <input type="text" id="division" name="division">
      </div>
      <div class="field">
        <label for="homeTeam">Home Team</label>
        <input type="text" id="homeTeam" name="homeTeam">
      </div>
      <div class="field">
        <label for="awayTeam">Away Team</label>
        <input type="text" id="awayTeam" name="awayTeam">
      </div>
    </div>

    <div class="section">
      <h2>Match Results</h2>
      <table>
        <thead>
          <tr>
            <th style="width: 60px;">Match</th>
            <th>Home Player</th>
            <th style="width: 60px;">Home PTS</th>
            <th>Away Player</th>
            <th style="width: 60px;">Away PTS</th>
          </tr>
        </thead>
        <tbody>
          <tr><td style="width: 60px;">1</td><td><input type="text" name="homePlayer1"></td><td><input type="number" name="homePTS1"></td><td><input type="text" name="awayPlayer1"></td><td><input type="number" name="awayPTS1"></td></tr>
          <tr><td style="width: 60px;">2</td><td><input type="text" name="homePlayer2"></td><td><input type="number" name="homePTS2"></td><td><input type="text" name="awayPlayer2"></td><td><input type="number" name="awayPTS2"></td></tr>
          <tr><td style="width: 60px;">3</td><td><input type="text" name="homePlayer3"></td><td><input type="number" name="homePTS3"></td><td><input type="text" name="awayPlayer3"></td><td><input type="number" name="awayPTS3"></td></tr>
          <tr><td style="width: 60px;">4</td><td><input type="text" name="homePlayer4"></td><td><input type="number" name="homePTS4"></td><td><input type="text" name="awayPlayer4"></td><td><input type="number" name="awayPTS4"></td></tr>
          <tr><td style="width: 60px;">5</td><td><input type="text" name="homePlayer5"></td><td><input type="number" name="homePTS5"></td><td><input type="text" name="awayPlayer5"></td><td><input type="number" name="awayPTS5"></td></tr>
        </tbody>
      </table>
    </div>

    <div class="section">
      <div class="field">
        <label for="homeTotal">Home Total</label>
        <input type="number" id="homeTotal" name="homeTotal">
      </div>
      <div class="field">
        <label for="awayTotal">Away Total</label>
        <input type="number" id="awayTotal" name="awayTotal">
      </div>
      <div class="field">
        <label for="homeCaptain">Home Captain</label>
        <input type="text" id="homeCaptain" name="homeCaptain">
      </div>
      <div class="field">
        <label for="awayCaptain">Away Captain</label>
        <input type="text" id="awayCaptain" name="awayCaptain">
      </div>
    </div>

    <div class="submit">
      <button type="submit">Submit</button>
    </div>
  </form>
</body>
</html>
