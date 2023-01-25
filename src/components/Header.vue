<template>
    <header>
        <div class="identificacion">
            <div id="divLogo">

                <RouterLink to="/">
                    <img src="imgs/logoTI.png" alt="tienda Isa" class="imgLogo">
                    <i class="logo">TIENDA ISA</i>
                </RouterLink>
            </div>
            <div class="enlaces">
                <RouterLink to="/inicioSesion">
                    <p id="iniciarSesion">Inicio sesión</p>
                </RouterLink>
                <RouterLink to="/registro">
                    <p id="registrarse">Registro</p>
                </RouterLink>
                <i class="fa-solid fa-cart-shopping" id="carro"></i>
            </div>
        </div>
        <nav>
            <ul>
                <li>
                    <RouterLink class="art-all" to="/catalogo">Catalogo</RouterLink>
                </li>
                <li>
                    <p class="art-mujer">Mujer</p>
                </li>
                <li>
                    <p class="art-hombre">Hombre</p>
                </li>
                <li>
                    <p class="art-jewele">Joyería</p>
                </li>
            </ul>
        </nav>
    </header>
</template>