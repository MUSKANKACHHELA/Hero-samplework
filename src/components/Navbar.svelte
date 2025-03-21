<script>
</script>

<nav class="navbar">
    <div class="navbar-brand">
        <a href="/" class="logo">
            <img src="/images/aspirelogo.png" alt="Aspire Logo">
        </a>
    </div>
    <ul class="nav-links">
        <li><a href="#product">Product</a></li>
        <li><a href="#pricing">Pricing</a></li>
        <li><a href="#company">Company</a></li>
        <li><a href="#resources">Resources</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="nav-actions">
        <a href="#login" class="btn btn-login">Login</a>
        <a href="#get-started" class="btn btn-primary">Get Started</a>
    </div>
</nav>

<img class="divider" src="/images/Divider.png" alt="Divider">



<style>
    .navbar {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 1rem 2rem;
        
    }

    .navbar-brand .logo {
        font-weight: 700;
        font-size: 1.25rem;
        text-decoration: none;
        mix-blend-mode: multiply;
    }

    .nav-links {
        list-style-type: none;
        display: flex;
        gap: 2rem;
        margin: 0;
    }

    .nav-links li a {
        text-decoration: none;
        font-weight: 500;
        transition: color 0.2s;
        color: #111827;
    }
    .nav-actions {
        display: flex;
        gap: 1rem;
    }

    .btn {
        padding: 0.5rem 1.2rem;
        border: none;
        outline: none;
        cursor: pointer;
        border-radius: 4px;
        text-decoration: none;
        color:#111827;
        font-weight: 400;
    }

    .btn-primary {
        background: #3A00FF;
        color: #fff;
        border-radius: 50px; 
    }

    .divider {
    display: block;
    width: 100%;
    max-width: 1500px;  
    margin: 0 auto;
    padding-top: 1rem;  
    opacity: 0.8;  
}


</style>