<p><i>After having created structure of workshoop1 JavaWeb</i>  || Despues de haber creado la estructura en el taller1 JavaWeb.</p>

# JavaWeb_Taller_2_y_3

<h6><i>User registration and database connection script</i> || Registro de usuario y script de la conexión a la base de datos </h6>

<h6>Dentro de la carpeta webapp; se crea un archivo con extensión <strong>.jsp</strong> y la estructura básica de html.||
    <i>Inside of webapp folder;  create file with extension<strong>.jsp</strong> and basic html structured </h6>
    
<h4>
    <ul><h3>1.Cabeza</h3>
        <li>Contiene la descripción especifica del contenido del documento.</li>
        <li>Lenguaje para realizar la página</li>
        <li>Reconocimiento de Caracteres especiales</li>
        <li>Enlaces de estilos e iconos</i>
    </ul>
    <ul><strong><i>
        <h3>1.Head:</h3></ul>
        <li>Description contain specify about of content of the document</li>
        <li>Language to page the make</li>
        <li>Special caracther recognition</li>
        <li>Links of Style and icons</li>
    </ul></i></strong>  
</h4>
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236696283-13bca895-7c7d-4c80-ae86-a335e3905b4e.png">
<p>
    
<h4>
    <ul><h3>2.Cuerpo:</h3>
        <li>Contiene el contenido del documento.</li>
        <li>Dentro,se crea el formulario</li>
    </ul>
    <ul><strong><i>
        <h3>2.Body:</h3></ul>
        <li>Contain the content of the document</li>
        <li>Inside, is create the form</li>
    </ul></i></strong>   
</h4>
<p align=center>
    <img src="https://user-images.githubusercontent.com/128232148/236697246-c6b64eeb-2892-4e20-b9e5-dbbc3da84b07.png">
</p>

<h4>Dentro la carpeta <b>webapp</b> se crea otra carpeta <b>css</b> para crear los estilos </h4>
<h4><b><i>Inside of the folder <b>webapp</b> is create folder <b>css</b> for create the style's</i></b></h4>
<p align="left">
    <img src="https://user-images.githubusercontent.com/128232148/236699635-9f7e6f7f-745e-4c30-b515-2f909d9d077a.png">
</p>

<h4>Los estilos son enlazados dentro de la cabeza de la siguiente manera :</h4>
<h4><b><i>The style's are linked inside of the <b>head</b> of the manner next:</b></i></h4>
<p align="left">
    <img src="https://user-images.githubusercontent.com/128232148/236699422-dc86cf04-298a-4ad1-a9bb-e5c6f0111cbe.png">
</p>

<h4><i>Style File || Archivo de estilos</h4>
<p align=left>
   <img src="https://user-images.githubusercontent.com/128232148/236701573-c5d1de69-8050-4030-991b-d34456535a24.png">
   <img src="https://user-images.githubusercontent.com/128232148/236701816-87c7ed65-2ea5-4809-aa89-3624175035bf.png"> 
</p>

<h4>
    <ul><h3>3.Pie de Página</h3>
        <li>Se agregan los derechos de autor.</li>
        <li>Enlaces relacionados</li>
        <h6>Va dentro del cuerpo del documento</h6>
    </ul>
    <ul><strong><i>
        <h3>3.Footer:</h3>
        <li>Add copyrigth</li>
        <li>Links related</li>
        <h6>Goes inside of body of document</h6>
    </ul></i></strong>   
</h4>

<h3 align="center">Result: Form of Sign in</h3>
<p align="center">
   <img src="https://user-images.githubusercontent.com/128232148/236699329-7a37827f-1b16-4659-9684-4851c9f5e529.png">
</p>

<h4>La estructura del html es similar para crear el formulario de registro,sin embargo, es necesario agregar otras etiquetas y cajas de texto,adicional,estos elementos son agregados dentro de un contenedor con una clase, la cual, será utilizada para llamar los elementos desde otro archivo y ajustar los estilos.</h4>

<h4>Structure html is the same for create the form of registrer, also, is necessary add others <b>labels</b> and text box a <b>input</b>, this elements are added inside of a container <b>div</b> with a name ,which, It will be used for invoke the elements from another file and style ajust. </h4>
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236698169-b0f1c48d-a1ae-487a-ba3d-84a6862f46f9.png">
</p>

<h3 align="center">Result: Form of Sign Up</h3>
<p align="center">
     <img src="https://user-images.githubusercontent.com/128232148/236692510-b9ce1773-329f-4ee1-b1b4-a16817aca87f.png">
</p>

<h3 align="center">Realizar Conexión a la base de datos</h3>
<h3 align="center"><b><i>Make conection to database</b></i></h3>
    
<h4>Crear script</h4>
<h4><b><i>Create script</i></b></h4>
<p>
  <img src="https://user-images.githubusercontent.com/128232148/236725686-c78c9f3b-a064-4a78-84c8-ffb5dd939404.png">
</p>


    
<h4>Como primera medida; Agregar las dependencias al archivo gestor <b>pom.xml</b> para poder conectar la base de datos</h4>
<h4><b><i>As a first measure; Added the dependencies to the file manager <b>pom.xml</b> to be able to connect the database</i></b></h4>
<p align="center">
  <img src="https://user-images.githubusercontent.com/128232148/236692560-233e2319-355b-464c-b218-f1a41f3a55b6.png" />
</p>

    
<h4>Dentro de la carpeta Java crear carpeta de  modelo y un archivo llamado usuario en donde se crearan: </h4>
<h4><b><i>Inside the Java folder, create a folder called model and a file called user where will be created:</b><i></h4>
 
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236708734-b0ca4302-6d61-4e41-90de-81c5c1035885.png">
</p>
    
<h4>The Attributes || Los atributos</h4>
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236712845-6dde8ced-0149-42b4-896f-e90ca863e291.png">
</p>
    
<h4>Void constructor || Constructor vacio</h4>
<p align="center">
   <img src="https://user-images.githubusercontent.com/128232148/236712867-64bc5ce5-9a4b-4ffe-bf5a-09474c4bf3e9.png">
</p>
    
<h4>Constructor with parameters || Constructor con parámetros</h4>
<p align="center">
   <img src="https://user-images.githubusercontent.com/128232148/236712882-3455c08e-99d3-4be0-a1aa-7241fce1ff4f.png">
</p>
    
<h4>Accesor Methods || Metodos Accesores</h4>
<p align="center">
   <img src="https://user-images.githubusercontent.com/128232148/236713013-c21b0eb9-ba53-4967-974a-bab77c4192da.png">
</p>
    
<h4>Metodo String</h4>
<p align="center">
   <img src="https://user-images.githubusercontent.com/128232148/236713161-9ce9234a-b353-4768-96f5-ecbf587b93ac.png">
</p>
    
    
<h4>Dentro de la carpeta Java crear carpeta de  util y un archivo llamado BDConnection en donde se crearan la Conexión </h4>
<h4>Inside the Java folder, create a folder called util and a file called DBConection where is create Conexión</h4>
    
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236708741-2fa8cc1d-a556-42e0-93ac-7c087efbe817.png">
</p>

<h4>Crear atributos estaticos que tendran valor fijo y son necesarios para realizar la conexion: url,usuario,contraseña</h4>
<h4>Create attributes static that they will have fixed value neccesary for do the connection: url,username,password</h4>
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236713670-6d0a173a-fcef-4e55-99c5-f745c5afe505.png">
</p>

<h4>Se crea un método estatico mediante <i><b>pool</b>(conjunto de recursos  ya almacenados para realizar conexiones)</i>,en el se acceden a los atributos y collecciones necesarias para realizar la conexión.</h4>
<h4>It's create a method static through <i><b>pool</b>(set of resources already stored to make connections)</i>,in the is to accces the attributes y collection need for realice the conection</h4>
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236713697-dfa736b2-899b-4eb1-af28-16c0c14e1204.png">
</p>
    
<h4>Crear método estatico para retornar la conexión</h4>
<h4>Create méthod static for return the connection</h4>
<p align="center">
    <img src="https://user-images.githubusercontent.com/128232148/236713704-c58d5aa6-d195-4c10-8405-ebb312b80065.png">
</p>







 
   



