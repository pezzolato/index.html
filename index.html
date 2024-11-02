<!DOCTYPE html>
<!--
Programa:Jogo de desvio
Nome: Andressa Pezzolato de Almeida - Nº:2 - Turma: 2°B
Nome: Lorenna Buriti Dos Santos  - Nº:21
Nome: Winicius Cobo Salgueiro Da Silva - Nº:36
DESCRIÇÃO:Este programa é um jogo, onde duas peças 
(um quadrado vermelho e um quadrado verde) são controladas por teclas ou botões na tela.
O objetivo do jogo é movimentar as peças sem que elas colidam uma com a outra..
-->
<html lang="pt-BR">
<head>
    <title>Componentes</title>
    <meta charset="UTF-8">
    <style>
        canvas {
            border: 1px solid #d3d3d3;
            background-color: #A0A0A0;
        }
    </style>
    <script>
        var myGamePiece;
        var myGamePiece2;
        var moveStep = 15; //quantidade de pixels ue a peça anda//
        var moveStep2 = 3;
        var intervalId;

        function startGame() {
            myGamePiece = new component(30, 30, "red", 10, 140);
            myGamePiece2 = new component (30,30,"green",10, 100);
            myGameArea.start();
        }

        var myGameArea = {
            canvas: document.createElement("canvas"),
            start: function() {
                this.canvas.width = 480;
                this.canvas.height = 270;
                this.context = this.canvas.getContext("2d");
                document.body.insertBefore(this.canvas, document.body.childNodes[0]);
                this.interval = setInterval(updateGameArea, 20); //o jogo é atualizado a cada 20 milissegundos
                window.addEventListener('keydown', function(e) {
                    myGameArea.key = e.keyCode;
                });
                window.addEventListener('keyup', function(e) {
                    myGameArea.key = false;
                });
            },
        
            clear: function() {
                this.context.clearRect(0, 0, this.canvas.width, this.canvas.height);
            },
            stop: function() {
                clearInterval(this.interval);
                alert("COLISÃO DETECTADA");
            }
        };
            
        

        function component(width, height, color, x, y) {
            this.width = width;
            this.height = height;
            this.x = x;
            this.y = y;
            this.color = color;

            this.update = function() {
                var ctx = myGameArea.context;
                ctx.fillStyle = this.color;
                ctx.fillRect(this.x, this.y, this.width, this.height);
               
                // colisão//
            };
            this.crashWith = function(otherObj) {
                var myleft = this.x;
                var myright = this.x + this.width;
                var mytop = this.y;
                var mybottom = this.y + this.height;

                var otherleft = otherObj.x;
                var otherright = otherObj.x + otherObj.width;
                var othertop = otherObj.y;
                var otherbottom = otherObj.y + otherObj.height;

                return !(mybottom < othertop || mytop > otherbottom || myright < otherleft || myleft > otherright);
            };
        }
//
        function updateGameArea() {
            myGameArea.clear();
            myGamePiece.update();
            myGamePiece2.update();

//tecla//
            if (myGameArea.key && myGameArea.key == 37) { // esquerda
                myGamePiece.x -= moveStep2;
                myGamePiece.x = Math.max(0, myGamePiece.x - moveStep2);
            }
            if (myGameArea.key && myGameArea.key == 39) { // direita
                myGamePiece.x += moveStep2;
                myGamePiece.x = Math.min(myGameArea.canvas.width - myGamePiece.width, myGamePiece.x + moveStep2);
            }
            if (myGameArea.key && myGameArea.key == 38) { // cima
                myGamePiece.y -= moveStep2;
                myGamePiece.y = Math.max(0, myGamePiece.y - moveStep2);
            }
            if (myGameArea.key && myGameArea.key == 40) { // baixo
                myGamePiece.y += moveStep2;
                myGamePiece.y = Math.min(myGameArea.canvas.height - myGamePiece.height, myGamePiece.y + moveStep2);
            }

            // Movimentação da peça verde (WASD)
            if (myGameArea.key && myGameArea.key == 65) { // A
                myGamePiece2.x -= moveStep2;
                myGamePiece2.x = Math.max(0, myGamePiece2.x - moveStep2);
            }
            if (myGameArea.key && myGameArea.key == 68) { // D
                myGamePiece2.x += moveStep2;
                myGamePiece2.x = Math.min(myGameArea.canvas.width - myGamePiece2.width, myGamePiece2.x + moveStep2);
            }
            if (myGameArea.key && myGameArea.key == 87) { // W
                myGamePiece2.y -= moveStep2;
                myGamePiece2.y = Math.max(0, myGamePiece2.y - moveStep2);
            }
            if (myGameArea.key && myGameArea.key == 83) { // S
                myGamePiece2.y += moveStep2;
                myGamePiece2.y = Math.min(myGameArea.canvas.height - myGamePiece2.height, myGamePiece2.y + moveStep2);
            }
            //


        //colisão//
            if (myGamePiece.crashWith(myGamePiece2)) {
                myGameArea.stop();
            }


//botões da tela//


        }
        function moveUp() {
            myGamePiece.y = Math.max(0, myGamePiece.y - moveStep);
        }

        function moveDown() {
            myGamePiece.y = Math.min(myGameArea.canvas.height - myGamePiece.height, myGamePiece.y + moveStep);
        }

        function moveLeft() {
            myGamePiece.x = Math.max(0, myGamePiece.x - moveStep);
        }

        function moveRight() {
            myGamePiece.x = Math.min(myGameArea.canvas.width - myGamePiece.width, myGamePiece.x + moveStep);
        }
        

        
        function moveUp2() {
            myGamePiece2.y = Math.max(0, myGamePiece2.y - moveStep);
        }

        function moveDown2() {
            myGamePiece2.y = Math.min(myGameArea.canvas.height - myGamePiece2.height, myGamePiece2.y + moveStep);
        }

        function moveLeft2() {
            myGamePiece2.x = Math.max(0, myGamePiece2.x - moveStep);
        }

        function moveRight2() {
            myGamePiece2.x = Math.min(myGameArea.canvas.width - myGamePiece2.width, myGamePiece2.x + moveStep);
        }

        function startMoving(direction) {
            if (intervalId) clearInterval(intervalId);
            intervalId = setInterval(() => {
                if (direction === 'up') moveUp();
                if (direction === 'down') moveDown();
                if (direction === 'left') moveLeft();
                if (direction === 'right') moveRight();
            }, 100);
        }

        function startMoving2(direction) {
            if (intervalId) clearInterval(intervalId);
            intervalId = setInterval(() => {
                if (direction === 'up2') moveUp2();
                if (direction === 'down2') moveDown2();
                if (direction === 'left2') moveLeft2();
                if (direction === 'right2') moveRight2();
            }, 100);
        }

        function stopMoving() {
            clearInterval(intervalId);
        }


     
                  
    </script>
</head>
<body onload="startGame();">
    <div>
        <button onmousedown="startMoving('up')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Cima</button>
        <button onmousedown="startMoving('down')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Baixo</button>
        <button onmousedown="startMoving('left')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Esquerda</button>
        <button onmousedown="startMoving('right')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Direita</button>
    <br>
<br>
        <button onmousedown="startMoving2('up2')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Cima</button>
        <button onmousedown="startMoving2('down2')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Baixo</button>
        <button onmousedown="startMoving2('left2')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Esquerda</button>
        <button onmousedown="startMoving2('right2')" onmouseup="stopMoving()" onmouseleave="stopMoving()">Direita</button>

    </div>
</body>
</html>
