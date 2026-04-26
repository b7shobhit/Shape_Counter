<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shape Intelligence Suite</title>
    <style>
        body { font-family: system-ui, sans-serif; display: flex; justify-content: center; align-items: center; min-height: 100vh; margin: 0; background-color: #f4f7f6; }
        .container { text-align: center; max-width: 800px; padding: 20px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 30px; }
        .card { background: white; padding: 30px; border-radius: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); text-decoration: none; color: #333; transition: transform 0.2s; border: 1px solid #eee; }
        .card:hover { transform: translateY(-5px); border-color: #007bff; }
        h1 { color: #2c3e50; margin-bottom: 10px; }
        p { color: #666; }
        .icon { font-size: 40px; margin-bottom: 15px; display: block; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Shape Intelligence Suite</h1>
        <p>A collection of interactive tools to solve complex geometric counting puzzles.</p>
        
        <div class="grid">
            <a href="star.html" class="card">
                <span class="icon">⭐</span>
                <h3>Star Triangle Counter</h3>
                <p>Detect and count nested triangles within star polygons.</p>
            </a>

            <a href="chess-squares.html" class="card">
                <span class="icon">🏁</span>
                <h3>Chessboard Squares</h3>
                <p>Calculate all possible square combinations on a grid.</p>
            </a>

            <a href="chess-combo.html" class="card">
                <span class="icon">📐</span>
                <h3>Chessboard Grid</h3>
                <p>Advanced analysis for both squares and rectangles on any grid size.</p>
            </a>
        </div>
    </div>
</body>
</html>