<div id="top"></div>
<div align="center">
  <h3 align="center">NEAvataR</h3>

  <p align="center">
    Obten tu Nft unico por cuenta NEAR
    <br />
    <a href="https://docs.near.org/docs/develop/basics/getting-started"><strong>Aprende más de Near »</strong></a>
    <br />
    <br />
    <a>View Demo</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenido</summary>
  <ol>
    <li>
      <a href="#about-the-project">Acerca del proyecto</a>
      <ul>
        <li><a href="#built-with">Herramientas utilizadas</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Inicialización</a>
      <ul>
        <li><a href="#installation">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contacto</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Acerca del proyecto

La idea del proyecto, es que mediante la tecnologia blockchain se pueda generar de manera dinamica una imagen de 128 x 128 pixels, utilizando como datos en la generacion al azar la direccion de la cuenta near, ejemplo : "leyner.near" y que esta imagen este guardada en un sistema IPFS generando así un NFT

**Por definir Economia

este proyecto tomo bases para el desarrollo del contrato:
* [Near-Examples](https://github.com/near-examples/NFT/blob/master/nft/src/lib.rs)
* [Paras](https://github.com/ParasHQ/paras-nft-contract)
* [NFT-culturas-latinas](https://github.com/NEAR-Hispano/NFT-culturas-latinas/blob/master/blockchain/rust-contract/contract/src/lib.rs)

<p align="right">(<a href="#top">back to top</a>)</p>

### Herramientas utilizadas

A continuación podra observar las principales librerias y lenguajes utilizados para crear este proyecto.

* [Vue.js](https://vuejs.org/)
* [Django](https://www.djangoproject.com/)
* [Rust](https://www.rust-lang.org/)
<p align="right">(<a href="#top">Subir</a>)</p>

<!-- GETTING STARTED -->
## Iniciando

Debe tener en cuenta que para ejecutar este proyecto, debe contar con un entorno con python3, nodeJS y rust previamente instalados

### Instalación

_A continuación, se daran unos breves paso la implementacion y pruebas para los tres componentes del aplicativo con ejemplos de ejecución_

1. Clonar el repositorio
   ```sh
   git clone https://github.com/laponte243/NEAvataR.git
   ```
2. BackEnd

   * Navega hasta la carpeta backend e inicializa un nuevo virtualenv
   ```sh
    virtualvenv venv
    source venv/bin/activate
   ```
   * Instala las librerias necesarias
   ```sh
    pip3 install -r requerimientos.txt
   ```
   * Inicializa la base de datos
   ```sh
    python3 manage.py makemigratios
    python3 manage.py migrate
   ```
   * Pon en acción el backend
   ```sh
    python3 manage.py runserver
   ```   
3. FrontEnd
   * Navega hasta el front e installa las librerias necesarias
   ```sh
    npm install
   ```
   * inicializa el proyecto
   ```sh
    npm run serve
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [X] Conceptualización
- [ ] Crear contrato inicial
- [ ] Crear pruebas internas al contrato
- [ ] Inicializar Backend Django con librerias de generación de imagenes
- [ ] Implementacion del IPFS
- [ ] Inicializar frontend con VueJs y Vuetify
- [ ] Soporte multi-lenguaje
    - [ ] Inglés

<p align="right">(<a href="#top">Subir</a>)</p>

<!-- CONTACT -->
## Contacto

Leyner Aponte  

Project Link: [https://github.com/laponte243/NEAvataR](https://github.com/laponte243/NEAvataR)

<p align="right">(<a href="#top">Arriba</a>)</p>