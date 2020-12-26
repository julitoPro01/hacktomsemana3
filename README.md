<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="normalize.css">
    <style>
        section {
           

width: 500px;
height: 350px;
left: 0px;
top: 2054px;
background: #1687A0;
        }
        input{
            margin-left: 50px;
            padding:5px ;
        }
        input:hover{
            background-color: violet;

        }
        textarea{
            margin-left: 50px;
        }
        button{
            position: absolute;

left: 100px;
        }
        button:hover{
            background-color: thistle;
            
        }
        h2{
            text-align: center;
            color:red;
        }
    </style>
</head>
<body>
    <section>
        
   <form action="">
       <h2>contacto</h2>
       <input type="text" placeholder="Nombre" required pattern="[A-Za-z]+">
       <input type="text"placeholder="Apellido" required pattern="[A-Za-z]+"><br><br>
       <input type="email" placeholder="Email" >
       <input type="number" placeholder="telefono" maxlength="9"><br><br>
       <textarea name="text" id="" cols="30" rows="10" placeholder="Descripcion..."></textarea><br>
       <button submit="submit" >Enviar</button>
       
   </form>
</section>
</body>
</html>
