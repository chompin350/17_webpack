<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h4>Instrucciones</h4>
    <div class="izquierda">
      <ul>
        <li>1. Crear una aplicación Vue.js mediante Vue-cli con los presets por defecto (babel y eslint).</li>
        <li>2. Instalar las dependencias para empaquetar el proyecto con webpack.</li>
          <ul>
            <li>babel-core: ^6.26.0</li>
            <li>babel-loader: ^7.1.2</li>
            <li>babel-preset-env: ^1.6.0</li>
            <li>babel-preset-stage-3: ^6.24.1</li>
            <li>cross-env: ^5.0.5</li>
            <li>css-loader: ^0.28.7</li>
            <li>file-loader: ^1.1.6</li>
            <li>html-webpack-plugin: ^3.2.0</li>
            <li>optimize-css-assets-webpack-plugin: ^5.0.3</li>
            <li>vue-loader: ^15.7.1</li>
            <li>webpack: ^4.39.3</li>
            <li>webpack-cli: ^3.3.7</li>
            <li>webpack-dev-server: ^3.8.0</li>
            <li>webpack-merge: ^4.2.1</li>
          </ul>
          <li>3. Crear estructura de archivos para empaquetar en modo desarrollo y modo producción, según los siguientes puntos</li>
            <ul>
              <li>Archivo HTML</li>
              <li>webpack.config.js</li>
              <li>webpack.config.base.js</li>
              <li>webpack.config.dev.js</li>
              <li>webpack.config.prod.js</li>
            </ul>
          <li>4. Agregar los scripts necesarios para:</li>
            <ul>
              <li>Ejecutar webpack en modo desarrollo <strong>npm run wp-dev</strong></li>
              <li>Ejecutar webpack en modo producción <strong>npm run wp-prod</strong></li>
            </ul>
      </ul>
    </div>
    <h4>Luis Aviles Santos</h4>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  padding: 10px;
  
}
li {
  display: block;
  padding: 5px;
  margin: 0 10px;
}
.izquierda{
  display: block;
  width: 800px;
  margin: 0 auto;
  text-align: left;
}
</style>
