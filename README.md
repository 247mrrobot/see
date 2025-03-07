<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>True/False Quiz</title>
</head>
<body>
    <h1>True/False Quiz</h1>
    <form id="quizForm">
        <!-- Question 1 -->
        <div>
            <p><strong>1. Data and information are essentially the same thing.</strong></p>
            <label><input type="radio" name="q1" value="a"> a) True</label><br>
            <label><input type="radio" name="q1" value="b"> b) False</label>
        </div>
        <br>

        <!-- Question 2 -->
        <div>
            <p><strong>2. Data processing can be as simple as organizing data to reveal patterns.</strong></p>
            <label><input type="radio" name="q2" value="a"> a) True</label><br>
            <label><input type="radio" name="q2" value="b"> b) False</label>
        </div>
        <br>

        <!-- Question 3 -->
        <div>
            <p><strong>3. Data is the result of processing raw facts to reveal its meaning.</strong></p>
            <label><input type="radio" name="q3" value="a"> a) True</label><br>
            <label><input type="radio" name="q3" value="b"> b) False</label>
        </div>
        <br>

        <!-- Question 4 -->
        <div>
            <p><strong>4. When data are entered into a form and saved, they are placed in the underlying database as knowledge.</strong></p>
            <label><input type="radio" name="q4" value="a"> a) True</label><br>
            <label><input type="radio" name="q4" value="b"> b) False</label>
        </div>
        <br>

        <!-- Question 5 -->
        <div>
            <p><strong>5. Data constitute the building blocks of information.</strong></p>
            <label><input type="radio" name="q5" value="a"> a) True</label><br>
            <label><input type="radio" name="q5" value="b"> b) False</label>
        </div>
        <br>

        <!-- Submit Button -->
        <button type="submit">Submit Quiz</button>
    </form>

    <script>
        document.getElementById('quizForm').addEventListener('submit', function(event) {
            event.preventDefault();
            alert('Quiz submitted!');
        });
    </script>
</body>
</html>
