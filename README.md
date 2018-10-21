x = 0
y = 0

def setup(): 
    size(640, 480)
def draw():
    global x
    global y
    if x > 640:
        x = 0
    x += 3
    if y > 480:
        y = 30
    y += 1
    
    
    background(135, 200, 250)  
    
    noStroke()

    fill(255,255,0)
    arc(620, 25, 160, 160, 0, PI+QUARTER_PI, CHORD)
    
    fill(255,255,255)
    ellipse(x, 50, 75, 50)
    ellipse(x+10, 50, 50, 50)
    ellipse(x+40, 35, 60, 50)
    ellipse(x-170, 35, 60, 50)
    ellipse(x-210, 55, 60, 50)
    ellipse(x-160, 55, 60, 50)
    fill(150)
    triangle(-120, 480, 360, 480, 120, 100)
    triangle(200, 480, 560, 480, 330, 80)
    triangle(300, 480, 700, 480, 450, 200)
    triangle(480, 480, 900, 480, 600, 300)
    
    stroke(153)
    fill("#31B522")
    rect(0, height/1.25, 640, 480)
    fill(255,255,255)
    ellipse(20, y, 10, 10)
    
    ellipse(40, y, 10, 10)
    y += 2
    ellipse(60, y, 10, 10)
    y += 1
    ellipse(80, y, 10, 10)
    y += 3
    ellipse(100, y, 10, 10)
    y += 1
    ellipse(120, y, 10, 10)
    y += 2
    ellipse(140, y, 10, 10)
    y += 5
    ellipse(160, y, 10, 10)
    y += 2
    ellipse(180, y, 10, 10)
    y += 1
    ellipse(200, y, 10, 10)
    y += 2
    ellipse(220, y, 10, 10)
    y += 4
    ellipse(240, y, 10, 10)
    y += 7
    ellipse(260, y, 10, 10)
    y += 5
    ellipse(280, y, 10, 10)
    y += 1
    ellipse(300, y, 10, 10)
    y += 2
    ellipse(320, y, 10, 10)
    y += 3
    ellipse(340, y, 10, 10)
    y += 4
    ellipse(360, y, 10, 10)
    y += 6
    ellipse(380, y, 10, 10)
    y += 7
    ellipse(400, y, 10, 10)
    y += 2
    ellipse(420, y, 10, 10)
    y += 2
    ellipse(440, y, 10, 10)
    y += 3
    ellipse(480, y, 10, 10)
    y += 4
    ellipse(500, y, 10, 10)
    y += 5
    ellipse(520, y, 10, 10)
    y += 1
    ellipse(540, y, 10, 10)
    y += 3
    ellipse(560, y, 10, 10)
    y += 2
    ellipse(580, y, 10, 10)
    y += 6
    ellipse(600, y, 10, 10)
    y += 1
    ellipse(620, y, 10, 10)
    y += 8
    ellipse(640, y, 10, 10)
                   


  
    
    
    
    
