<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Login Form</title>
        <link rel="stylesheet" href="../css/login.css">
    </head>

    <body>
        <div class="contenedor">
            <h3>Regístrate en los formularios</h3>
            <div class="botones">
                <button class="google-btn">
                    <picture>
                        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Google_%22G%22_Logo.svg/1200px-Google_%22G%22_Logo.svg.png" alt="Logo Google">
                    </picture>
                    <span>Registrarse con Google</span>
                </button>
                <button class="facebook-btn">
                    <picture>
                        <img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/04/Facebook_f_logo_%282021%29.svg/2048px-Facebook_f_logo_%282021%29.svg.png" alt="Logo FB">
                    </picture>
                </button>
            </div>

                <div class="separador">
                    <hr>
                    <span>O...</span>
                    <hr>
                </div>

                <form action="" method="">
                <div class="nombre">
                    <label for="nombre">
                        <span>Nombre</span>
                        <input id="nombre" name="nombre">
                    </label>
                    <label for="apellido">
                        <span>Apellido</span>
                        <input id="apellido" name="apellido">
                    </label>
                </div>

                    <label for="email">
                        <span>Email</span>
                        <input id="email" name="email">
                    </label>

                    <label for="contraseña">
                        <span>Contraseña</span>
                        <input id="contraseña" name="contraseña" placeholder="6+ caracteres">
                    </label>

                    <label for="checkbox" class="checkbox-label">
                        <input type="checkbox" id="checkbox">
                        <span>Acepto las condiciones y el aviso legal</span>
                    </label>
                    
                    <button class="new-cuenta" type="submit">Crear cuenta</button>
            </form>
        </div>
    </body>
</html>
