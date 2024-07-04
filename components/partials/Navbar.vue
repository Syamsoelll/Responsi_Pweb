<template>
    <div class="navbar navbar-expand-lg  navbar-dark bg-dark px-0 py-3">
        <nav class="navbar navbar-expand-lg bg-body-tertiary d-flex">
            <div class="container-xl d-flex">
                <a class="navbar-brand" href="#">Soel</a>
                <button 
                class="navbar-toggler" 
                type="button" 
                data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" 
                aria-expanded="false" aria-label="Toggle navigation"
                >
                
                </button>
                <div class="collapse navbar-collapse d-flex justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                    <a class="nav-link anim-bottom" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#Projects">Projects</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#About">About</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="#Contact">Contact</a>
                    </li>
                </ul>
                </div>
            </div>
        </nav>
    </div>
    
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>

.navbar {
    padding: 0 200px;
  color: white;
}
.anim-bottom::after{
    width: 100%;
    height: 3px;
    background-color: aqua;
}
</style>