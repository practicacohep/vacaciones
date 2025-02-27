<html lang="es">
    <head>
        <link rel="icon" href="Cohep.jpg" type="image/x-icon">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Vacaciones - COHEP</title>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
        <style>
            body{ /*Todo lo que esta afuera del formulario*/
            font-family: 'Poppins', sans-serif;
                background-color: #191a1b;
                display: flex;
                flex-direction: column;
                align-items: center;
                height: 100vh;
                margin: 10;
                color: white;
                height: 100%;
                margin: 0;
                background-image:url(fondo\ de\ vacaciones.jpg);
                background-size: cover;
                background-position: center;                        
            }

            .navbar {
                width: 100%;
                background: #eac508;
                padding: 15px;
                text-align: center;
                box-shadow: 0px 4px 6px #FFC107;
            }

            .navbar a {
                color: #000000;
                text-decoration: none;
                margin: 0 20px;
                font-size: 18px;
                font-weight: 600;
            }

            .navbar a:hover {
                text-decoration: underline;
            }

            .container {
                text-align: center;
                background: white;
                padding: 130px;
                border-radius: 100x;
                box-shadow: 1 10px 15px rgba(183, 23, 23, 0.3);
                width: 100%;
                max-width: 500px;            
                margin-top: 40px;
                color: rgb(0, 0, 0);
            }
                    
            h2 {
                text-align: Center;
                font-weight: 600;
            }

            input, select, button, textarea {
                width: 100%;
                padding: 8px;
                margin: 5px 0;
                border: 1px solid #ccc;
                border-radius: 8px;
                font-size: 14px;
            }

            button {
                background-color: #007BFF;
                color: white;
                border: none;
                cursor: pointer;
                font-size: 14px;
                padding: 10px;
                border-radius: 8px;
                transition: 0.3s;
            }

            .button:hover {
                background-color: #0056b3;
            }

            .franja {
                background-color: #FFC107;
                color: #001f3f;
                padding: 0px;
                font-size: 18px;
                font-weight: bold;
                text-align: justify;
                border-radius: 8px;
                margin-top: 20px;
            }   
                       
        </style>
    </head>
    <body>
        
        <div class="navbar">             
            <a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vTDxgQLo0iH9egVVqdCBAAswSxEg27PDG4Z4c2C0ArAYdfFSKBpxO1yhxKJaA3qVwfP7tdMAkZpqAri/pubhtml">Registro de Vacaciones</a>
        </div>
            
        <div class="container">
            <div style="text-align: center; margin-top: 20px;">
                <img src="https://www.elinformativo.hn/wp-content/uploads/2018/02/Cohep.jpg" alt="COHEP" width="300">
            </div>
            <div class="franja">
                <h2>Registro de Vacaciones</h2>
            </div>
            
            <form id="reservaForm" method="post" action="https://script.google.com/macros/s/AKfycbzStr_gaTG0tzZhYR5_zfxKN7_V7YGx1RVrufP8il14H5aLRwGMOQlZEJcCgG5_nncQ/exec">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                
                <label for="puesto">Departamento:</label>
                    <select id="puesto" name="puesto">
                        <option value="Recursos">Recursos Humanos</option>
                        <option value="Comunicaciones">Comunicaciones</option>
                        <option value="Legal">Legal</option>                    
                    </select>
                
                <label for="cargo">Cargo:</label>
                <input type="text" id="cargo" name="cargo" required>

                <label for="tipo">tipo de Vacaciones:</label>
                <select id="tipo" name="tipo">
                    <option value="Obligatorio">Obligatorios</option>
                    <option value="Legales">Legales</option>
                    <option value="Permiso">Permiso</option>                    
                </select>     

                <label for="inicio">Fecha de inicio:</label>
                <input type="date" id="inicio" name="inicio" required>
                
                <label for="final">Fecha de finalización:</label>
                <input type="date" id="final" name="final" required>                      
            
                <button type="submit">Guardar Información</button>            

            </form>
        </div>      
    </body>
</html>
