<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
</head>
<body>
    <div> 
        <h1> Travel form of our college</h1>
        <form action=" form.php">
            <input type="text" placeholder="Enter your name"> <br>
            <label for="sectionida">
                <input type="radio" value="section a " name="section" id="sectionida"> Section A

            </label>
            <label for="sectionidb">
                <input type="radio" value="section b " name="section" id="sectionidb"> Section B

            </label><br>
            <input type="checkbox" id="food canteen" name=" canteen">
            <label for="food canteen"> want food canteen card</label><br>
            <textarea name="explain" id="explain" cols="30" rows="10" placeholder="Explain why u want to join"> </textarea><br>
            <select name="car" id="car">
                <option value="no car"> select your car</option>
                <option value="tata">Tata</option>
                <option value="bmw">bmw</option>
                <option value="ferari">ferari</option>
                <option value="alto">alto</option>
            </select>
        </form><br>
        <iframe src="https://www.bing.com/"></iframe>
        <table> 
            <caption> Runs scored in cricket by diff players</caption>
            <thead>
            <tr> 
                <th> S.No</th>
                <th> Player Name</th>
                <th> Max Score</th>
                <th> Game played</th>

            </tr>
            <tr> 
                <td> 1</td>
                <td> Dhoni</td>
                <td> 186</td>
                <td> 500</td>
            </tr>
            </thead>
            <tbody>
            <tr> 
                <td> 2</td>
                <td> Sachin</td>
                <td> 200</td>
                <td> 450</td>
            </tr>
            <tr> 
                <td> 3</td>
                <td> Virat</td>
                <td> 100</td>
                <td> 150</td>
            </tr>
            </tbody>
        </table>
    </div>
</body>
</html>
