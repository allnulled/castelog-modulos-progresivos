una aplicación general:
 - dependencias
 - precarga
 - plugins
 - carga
 - eventos
 - ejecucion

una aplicación genera tipo servidor:
 - dependencias
 - precarga
   + utilidades mínimas
   + variables de entorno
   + framework
   + framework
 - plugins
   + cargar plugins
   + cargar plugins
 - carga
 - eventos
 - ejecucion
 + 

[
  ["dependencias", [
    ["dependencias.express"],
    ["dependencias.body-parser"],
    ["dependencias.multer"],
  ]],
  ["precarga"],
  ["plugins"],
  ["carga"],
  ["eventos"],
  ["ejecucion"]
], {
  "dependencias": "imprimo 'Hola desde un fichero *.calo-app.json'."
}


<servidor>
  <vida>
    <hook id="dependencias">
      <hook id="dependencias.express"></hook>
    </hook>
  </vida>
  <hookable id="dependencias">
  </hookable>
  <hookable id="dependencias">
  </hookable>
  <hookable id="dependencias">
  </hookable>
  <hookable id="dependencias">
  </hookable>
  <hookable id="dependencias">
  </hookable>
</servidor>



{
  "ciclos": {

  },
  "vida": [
    "dependencias",

  ]
}