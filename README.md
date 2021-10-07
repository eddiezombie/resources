# NodeJS
## Cambiar versiones de NodeJS

<p>Versión actual que tienes:</p>
<pre>node -v</pre>

<p>Para cambiar de versión fácilmente, utilizar un programa llamado "n":</p>
<pre>sudo npm install -g n</pre>

<p>Instalar la última version estable:</p>
<pre>sudo n stable</pre>

<p>Instalar una versión en especifico:</p>
<pre>sudo n 10.16.0</pre>

<p>Para saber las versiones que existen, visitar https://nodejs.org/en/download/releases/</p>

# Angular

Variable con tipo 
<pre> const a:string = 'hola' </pre>
<pre> type rut = string; </pre>
<pre> let rutnumber: rut = '167113761' </pre>

Clases
<pre>
 class Transporte{
  private velocidad: number;
  private formaDeMovilidad: string;
  
  constructor( velocidad:number, formaDeMovilidad: string ){
    this.velocidad = velocidad;
    this.formaDeVelocidad = formaDeMovilidad;
  }
  
  getVelocidad(velocidad:number){
    return this.velocidad;
  }
  
  setVelocidad (velocidad:number){
    this.velocidad = velocidad;
  }
  
  getFormaDeMovilidad(formaDeMovilidad: string){
    return this.formaDeMovilidad;
  }
  
  setFormaDeMovilidad (formaDeMovilidad: string){
    this.formaDeMovilidad = formaDeMovilidad;
  }
 } 
 
 const transporte: Transporte = new Transporte(20, 'suelo')
</pre>
