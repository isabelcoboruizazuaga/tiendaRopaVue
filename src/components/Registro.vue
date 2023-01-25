<template>
    <section class="registro">
        <form>
                <fieldset>
                    <legend>Datos de sesión</legend>
                    <div>
                        <label for="email">Correo electrónico:</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div>
                        <label for="username">Nombre de usuario:</label>
                        <input type="text" id="username" name="username" required>
                    </div>
                    <div>
                        <label for="password">Contraseña:</label>
                        <input type="password" id="password" name="password" required>
                    </div>
                </fieldset>
                <fieldset>
                    <legend>Datos personales</legend>
                    <div>
                        <label for="nombre">Nombre</label>
                        <input type="text" id="nombre" name="nombre" required>
                    </div>
                    <div>
                        <label for="apellidos">Apellidos:</label>
                        <input type="text" id="apellidos" name="apellidos" required>
                    </div>
                    <div>
                        <label for="tel">Teléfono:</label>
                        <input type="number" id="tel" name="tel" required>
                    </div>
                </fieldset>
                <fieldset>
                    <legend>Dirección</legend>
                    <div>
                        <label for="ciudad">Ciudad:</label>
                        <input type="text" id="ciudad" name="ciudad">
                    </div>
                    <div>
                        <label for="calle">Calle:</label>
                        <input type="text" id="calle" name="calle">
                    </div>
                    <div>
                        <label for="numero">Número:</label>
                        <input type="number" id="numero" name="numero">
                    </div>
                    <div>
                        <label for="zip">Código ZIP:</label>
                        <input type="text" id="zip" name="zip">
                    </div>
                </fieldset>
                <input type="submit" value="Registrarme">
            </form>
        </section>
</template>