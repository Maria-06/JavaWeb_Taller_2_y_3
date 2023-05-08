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

    
<h4>Como primera medida; Agregar las dependencias al archivo gestor <b>pom.xml</b> para poder conectar la base de datos</h4>
<h4><b><i>As a first measure; Added the dependencies to the file manager <b>pom.xml</b> to be able to connect the database</i></b></h4>
<p align="center">
  <img src="https://user-images.githubusercontent.com/128232148/236692560-233e2319-355b-464c-b218-f1a41f3a55b6.png" />
</p>

    
<h4>Dentro de la carpeta Java crear carpeta de  modelo y un archivo llamado usuario en donde se crearan los atributos, el metodo constructor vacio, el constructor con parámetros y los metodos accesores de la clase usuario</h4>
<h4><b><i>Inside the Java folder, create a folder called model and a file called user where the attributes of the user class will be created, an empty constructor, a constructor with parameters and accessor methods.</b><i></h4>
<p align="left">
    <img src="https://user-images.githubusercontent.com/128232148/236708734-b0ca4302-6d61-4e41-90de-81c5c1035885.png">
    
    <h5>The Attributes || Los atributos</h5>
    <p align="center">
        <img src="https://user-images.githubusercontent.com/128232148/236709753-679e420f-a0fc-4187-ab0d-a8d3a9138252.png">
    </p>
     <h5>Void constructor || Constructor vacio</h5>
    <p align="center">
        <img src="https://user-images.githubusercontent.com/128232148/236710238-0d0a7da5-2df7-4fab-acd0-6dfa057c2414.png">
    </p>
    <h5>Constructor with parameters || Constructor con parámetros</h5>
    <p align="center">
        <img src="https://user-images.githubusercontent.com/128232148/236710238-0d0a7da5-2df7-4fab-acd0-6dfa057c2414.png">
    </p>
    <p align="center">
    
    </p>
    <img src="">
    <h5>Accesor Methods || Metodos Accesores</h5>
    <img src="">

</p>
<h4>Dentro de la carpeta Java crear carpeta de  util y un archivo llamado BDConnection en donde se crearan la Conexión </h4>
<h4>Inside the Java folder, create a folder called util and a file called DBConection where is create Conexión</h4>
<p align="left">
    <img src="https://user-images.githubusercontent.com/128232148/236708741-2fa8cc1d-a556-42e0-93ac-7c087efbe817.png">
</p>







 
   



