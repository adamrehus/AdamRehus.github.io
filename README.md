<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}
<!DOCTYPE html>
<html>
<head>
    <title>The Matchmaker</title>
    <style>
        body {
            background-color: #3498db;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: #3498db;
        }
        .question {
            text-align: left;
            margin-bottom: 15px;
        }
        input[type="radio"] {
            margin-right: 10px;
        }
        label {
            display: block;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Matchmaker Quiz</h1>
        <form>
            <div class="question">
                <p>1. Rap music is overrated</p>
                <label><input type="radio" name="q1" value="a">a) 1</label>
                <label><input type="radio" name="q1" value="b">b) 2</label>
                <label><input type="radio" name="q1" value="c">c) 3</label> 
                <label><input type="radio" name="q1" value="d">d) 4</label> 
                <label><input type="radio" name="q1" value="e">e) 5</label>
            </div>

            <div class="question">
                <p>2. Halloween is the best holiday</p>
                <label><input type="radio" name="q1" value="a">a) 1</label>
                <label><input type="radio" name="q1" value="b">b) 2</label>
                <label><input type="radio" name="q1" value="c">c) 3</label> 
                <label><input type="radio" name="q1" value="d">d) 4</label> 
                <label><input type="radio" name="q1" value="e">e) 5</label>
            </div>

            <div class="question">
                <p>3. Iced Coffee is better than warm coffee</p>
                <label><input type="radio" name="q1" value="a">a) 1</label>
                <label><input type="radio" name="q1" value="b">b) 2</label>
                <label><input type="radio" name="q1" value="c">c) 3</label> 
                <label><input type="radio" name="q1" value="d">d) 4</label> 
                <label><input type="radio" name="q1" value="e">e) 5</label>
            </div>

            <div class="question">
                <p>4. Blackhawks are the best team in Chicago</p>
                <label><input type="radio" name="q1" value="a">a) 1</label>
                <label><input type="radio" name="q1" value="b">b) 2</label>
                <label><input type="radio" name="q1" value="c">c) 3</label> 
                <label><input type="radio" name="q1" value="d">d) 4</label> 
                <label><input type="radio" name="q1" value="e">e) 5</label>
            </div>

            <div class="question">
                <p>5. Porsche is better than Audi,Mercedes,BMW</p>
                <label><input type="radio" name="q1" value="a">a) 1</label>
                <label><input type="radio" name="q1" value="b">b) 2</label>
                <label><input type="radio" name="q1" value="c">c) 3</label> 
                <label><input type="radio" name="q1" value="d">d) 4</label> 
                <label><input type="radio" name="q1" value="e">e) 5</label>
            </div>

            <input type="submit" value="Submit">
        </form>
    </div>
</body>
</html>
       
