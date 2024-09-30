<script>
    //  funciones svelte 
    
        import Footer from "./components/Footer.svelte";
        import Nav from "./components/Nav.svelte";
    
    </script>
    
    <main>
      <!-- contenido html  -->
        <Nav/>
        <div class="container text-center" style="min-height: 26vh;">
          <h1 class="text-success">Hola mundo</h1>
        <button type="button" class="btn btn-success">Base class</button>
        </div>
        
        <Footer/>
    
    </main>
    
    <style>
      
      /* estilos de svelte css */
      .container {
        background: radial-gradient(circle, rgba(241,237,235,1) 0%, rgba(255,255,255,1) 100%);
      }
    </style>