# ToDo-list
<!DOCTYPE html>
<html>
<head>
    <title>Todo List</title>
    <style>
        /* Add some basic styling to make the list look nicer */
        body {
            font-family: Georgia, 'Times New Roman', Times, serif;
            text-align: center;
            background-image:url(https://media.istockphoto.com/id/1337229517/vector/newspaper-paper-grunge-vintage-old-aged-texture-background.jpg?s=612x612&w=0&k=20&c=gq8FhwdLFibfBVFiG3WKP6KyAGvXA-4rjwJzSGaP-7I=);
            
        }
        
        .todo-list {
            width: 80%;
            margin: 40px auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        
        .todo-list h2 {
            margin-top: 0;
        }
        
        .todo-list ul {
            list-style: none;
            padding: 0;
            margin: 0;
            font-size: 25px;
        }
        
        .todo-list li {
            padding: 10px;
            border-bottom: 1px solid #ccc;
        }
        
        .todo-list li:last-child {
            border-bottom: none;
        }
        
        .todo-list input[type="checkbox"] {
            margin-right: 10px;
    
        }
        
        .todo-list button[type="button"] {
            background-color: #4CAF50;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 20px;
            cursor: pointer;
        }
        
        .todo-list button[type="button"]:hover {
            background-color: green;
        }
    </style>
</head>
<body>
    <div class="todo-list">
        <h1>Todo List</h1>
        <ul>
            <!-- Add your todo items here -->
            <li>
                <input type="checkbox" id="todo1" />
                <label for="todo1">Buy groceries</label>
            </li>
            <li>
                <input type="checkbox" id="todo2" />
                <label for="todo2">Finish project report</label>
            </li>
            <li>
                <input type="checkbox" id="todo3" />
                <label for="todo3">Call Niloy</label>
            </li>
            <li>
                <input type="checkbox" id="todo4" />
                <label for="todo4">Study for exam</label>
            </li>
        </ul>
        <button type="button">Add Task</button>
    </div>
</body>
</html>
